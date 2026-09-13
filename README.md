============================================================
SHOOTERGAME - ANALYSE STATIQUE V18
============================================================
Objectif : déterminer la provenance de l'objet
passé à GetWorldLocation dans chaque caller.

Chaîne recherchée :
caller -> RCX -> objet -> champs -> sous-structures
-> GetWorldLocation -> vecteur +0/+4/+8

Aucune lecture mémoire runtime.

============================================================
GETWORLDLOCATION
============================================================
NAME  : GetWorldLocation
ENTRY : 0x14021EB40

INPUT REGISTER = RCX

VECTOR SOURCE ACCESSES:
  0x14021EB74 | MOVSS XMM0,dword ptr [RAX + 0x8]
  0x14021EB84 | MOVSS XMM0,dword ptr [RAX + 0x4]
  0x14021EB94 | MOVSS XMM0,dword ptr [RAX]
  0x14021EBEA | MOVAPS XMM0,xmmword ptr [RAX]
  0x14021EC22 | MULPS XMM0,xmmword ptr [RAX]
  0x14021EC97 | MOVUPS XMM0,xmmword ptr [RAX]
  0x14021EC9A | SHUFPS XMM0,xmmword ptr [RCX],0xff
  0x14021ECE3 | MOVUPS XMM0,xmmword ptr [RAX]
  0x14021ECE6 | SHUFPS XMM0,xmmword ptr [RCX],0x0
  0x14021ED5E | MOVUPS XMM0,xmmword ptr [RAX]
  0x14021ED61 | SHUFPS XMM0,xmmword ptr [RCX],0x55
  0x14021EDD9 | MOVUPS XMM0,xmmword ptr [RAX]
  0x14021EDDC | SHUFPS XMM0,xmmword ptr [RCX],0xaa
  0x14021F0B9 | MOVAPS xmmword ptr [RAX],XMM0
  0x14021F0DE | MOVSS dword ptr [RAX],XMM0
  0x14021F0F3 | MOVSS dword ptr [RAX + 0x4],XMM0
  0x14021F109 | MOVSS dword ptr [RAX + 0x8],XMM0

INTERPRETATION:
  +0/+4/+8 = vecteur source/resultat.
  Le script ne les declare pas automatiquement comme XYZ.

============================================================
CALLERS DE GETWORLDLOCATION
============================================================

------------------------------------------------------------
CALLER #1
FUNCTION : GetClosestSurfacePoint
ENTRY    : 0x14021FEA0
CALL     : 0x14021FF80
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x14021FEC0 | LEA RCX,[RSP + 0x1a8]
  RCX_SETUP @ 0x14021FF25 | LEA RCX,[0x1449fcf28]
  RCX_SETUP @ 0x14021FF41 | LEA RCX,[0x1449fcf28]
  RCX_SETUP @ 0x14021FF78 | MOV RCX,qword ptr [RSP + 0x2b0]

2) CALL_CONTEXT
  0x14021FF25 | LEA RCX,[0x1449fcf28]
  0x14021FF2C | MOV RDI,RAX
  0x14021FF2F | MOV RSI,RCX
  0x14021FF39 | LEA RAX,[RSP + 0xa8]
  0x14021FF41 | LEA RCX,[0x1449fcf28]
  0x14021FF48 | MOV RDI,RAX
  0x14021FF4B | MOV RSI,RCX
  0x14021FF55 | MOV RAX,qword ptr [RSP + 0x2b0]
  0x14021FF5D | MOVZX EAX,byte ptr [RAX + 0x68]
  0x14021FF78 | MOV RCX,qword ptr [RSP + 0x2b0]
  0x14021FF80 | CALL 0x14021eb40
  0x14021FF85 | MOV RAX,qword ptr [RSP + 0x2c0]
  0x14021FF8D | MOVSS XMM0,dword ptr [RAX + 0x8]
  0x14021FFA4 | MOV RAX,qword ptr [RSP + 0x2c0]
  0x14021FFAC | MOVSS XMM0,dword ptr [RAX + 0x4]
  0x14021FFC3 | MOV RAX,qword ptr [RSP + 0x2c0]
  0x14021FFCB | MOVSS XMM0,dword ptr [RAX]

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,qword ptr [RSP + 0x2b0]

4) OBJECT_FIELD_CANDIDATES
  RAX+0x68 @0x14021FF5D | MOVZX EAX,byte ptr [RAX + 0x68]
  RAX+0x8 @0x14021FF8D | MOVSS XMM0,dword ptr [RAX + 0x8]
  RAX+0x4 @0x14021FFAC | MOVSS XMM0,dword ptr [RAX + 0x4]
  RAX+0x0 @0x14021FFCB | MOVSS XMM0,dword ptr [RAX]

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

------------------------------------------------------------
CALLER #2
FUNCTION : GetAvoidanceDirection
ENTRY    : 0x140220ED0
CALL     : 0x140220EFD
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x140220EF5 | MOV RCX,qword ptr [RSP + 0x170]

2) CALL_CONTEXT
  0x140220EF5 | MOV RCX,qword ptr [RSP + 0x170]
  0x140220EFD | CALL 0x14021eb40
  0x140220F07 | MOV RAX,qword ptr [RSP + 0x180]
  0x140220F0F | MOV RCX,qword ptr [RSP + 0x68]
  0x140220F14 | MOVSS XMM0,dword ptr [RAX + 0x8]
  0x140220F19 | SUBSS XMM0,dword ptr [RCX + 0x8]
  0x140220F24 | MOV RAX,qword ptr [RSP + 0x180]
  0x140220F2C | MOV RCX,qword ptr [RSP + 0x68]
  0x140220F31 | MOVSS XMM0,dword ptr [RAX + 0x4]
  0x140220F36 | SUBSS XMM0,dword ptr [RCX + 0x4]
  0x140220F41 | MOV RAX,qword ptr [RSP + 0x180]

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,qword ptr [RSP + 0x170]

4) OBJECT_FIELD_CANDIDATES
  RAX+0x8 @0x140220F14 | MOVSS XMM0,dword ptr [RAX + 0x8]
  RCX+0x8 @0x140220F19 | SUBSS XMM0,dword ptr [RCX + 0x8]
  RAX+0x4 @0x140220F31 | MOVSS XMM0,dword ptr [RAX + 0x4]
  RCX+0x4 @0x140220F36 | SUBSS XMM0,dword ptr [RCX + 0x4]

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

------------------------------------------------------------
CALLER #3
FUNCTION : DrawDebug
ENTRY    : 0x140221220
CALL     : 0x140221247
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x14022123F | MOV RCX,qword ptr [RSP + 0x1f0]

2) CALL_CONTEXT
  0x14022123F | MOV RCX,qword ptr [RSP + 0x1f0]
  0x140221247 | CALL 0x14021eb40
  0x14022124C | MOV RAX,qword ptr [RSP + 0x1f0]
  0x140221254 | MOVZX EAX,byte ptr [RAX + 0x68]
  0x140221265 | LEA RAX,[RSP + 0x70]
  0x14022126A | MOV RCX,qword ptr [RSP + 0x1f0]
  0x140221272 | MOVUPS XMM0,xmmword ptr [RCX + 0x20]
  0x140221276 | MOVAPS xmmword ptr [RAX],XMM0

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,qword ptr [RSP + 0x1f0]

4) OBJECT_FIELD_CANDIDATES
  RAX+0x68 @0x140221254 | MOVZX EAX,byte ptr [RAX + 0x68]
  RCX+0x20 @0x140221272 | MOVUPS XMM0,xmmword ptr [RCX + 0x20]
  RAX+0x0 @0x140221276 | MOVAPS xmmword ptr [RAX],XMM0

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

------------------------------------------------------------
CALLER #4
FUNCTION : GetAvoidanceAreaWorldLocation
ENTRY    : 0x140229D70
CALL     : 0x140229D88
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x140229D83 | MOV RCX,qword ptr [RSP + 0x38]

2) CALL_CONTEXT
  0x140229D83 | MOV RCX,qword ptr [RSP + 0x38]
  0x140229D88 | CALL 0x14021eb40
  0x140229D8D | MOV RAX,qword ptr [RSP + 0x30]

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,qword ptr [RSP + 0x38]

4) OBJECT_FIELD_CANDIDATES
  NONE_FOUND

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

------------------------------------------------------------
CALLER #5
FUNCTION : TickPersistentFlockData
ENTRY    : 0x14022A030
CALL     : 0x14022A57D
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x14022A44F | LEA RCX,[0x14456d790]
  RCX_SETUP @ 0x14022A477 | MOV RCX,qword ptr [RSP + 0x3e8]
  RCX_SETUP @ 0x14022A53C | LEA RCX,[0x14456d790]
  RCX_SETUP @ 0x14022A564 | MOV RCX,qword ptr [RSP + 0x4e0]
  RCX_SETUP @ 0x14022A57A | MOV RCX,RAX

2) CALL_CONTEXT
  0x14022A511 | MOV RAX,qword ptr [RSP + 0x358]
  0x14022A519 | MOV EAX,dword ptr [RAX + 0x8]
  0x14022A53C | LEA RCX,[0x14456d790]
  0x14022A548 | MOV RAX,qword ptr [RSP + 0x358]
  0x14022A550 | MOV RAX,qword ptr [RAX]
  0x14022A564 | MOV RCX,qword ptr [RSP + 0x4e0]
  0x14022A56F | MOV RAX,RCX
  0x14022A57A | MOV RCX,RAX
  0x14022A57D | CALL 0x14021eb40
  0x14022A58A | MOV RAX,qword ptr [RSP + 0x220]
  0x14022A592 | MOVSS XMM0,dword ptr [RAX]
  0x14022A5A5 | MOV RAX,qword ptr [RSP + 0x220]
  0x14022A5AD | MOVSS XMM0,dword ptr [RAX + 0x4]
  0x14022A5C1 | MOV RAX,qword ptr [RSP + 0x220]
  0x14022A5C9 | MOVSS XMM0,dword ptr [RAX + 0x8]

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,RAX

4) OBJECT_FIELD_CANDIDATES
  RAX+0x8 @0x14022A519 | MOV EAX,dword ptr [RAX + 0x8]
  RAX+0x0 @0x14022A550 | MOV RAX,qword ptr [RAX]
  RAX+0x0 @0x14022A592 | MOVSS XMM0,dword ptr [RAX]
  RAX+0x4 @0x14022A5AD | MOVSS XMM0,dword ptr [RAX + 0x4]
  RAX+0x8 @0x14022A5C9 | MOVSS XMM0,dword ptr [RAX + 0x8]

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

------------------------------------------------------------
CALLER #6
FUNCTION : operator()
ENTRY    : 0x14022CBD0
CALL     : 0x14022CD1F
------------------------------------------------------------

1) RCX_PROVENANCE
  RCX_SETUP @ 0x14022CCDE | LEA RCX,[0x14456d790]
  RCX_SETUP @ 0x14022CD06 | MOV RCX,qword ptr [RSP + 0x88]
  RCX_SETUP @ 0x14022CD1C | MOV RCX,RAX

2) CALL_CONTEXT
  0x14022CCB3 | MOV RAX,qword ptr [RSP + 0x80]
  0x14022CCBB | MOV EAX,dword ptr [RAX + 0x8]
  0x14022CCDE | LEA RCX,[0x14456d790]
  0x14022CCEA | MOV RAX,qword ptr [RSP + 0x80]
  0x14022CCF2 | MOV RAX,qword ptr [RAX]
  0x14022CD06 | MOV RCX,qword ptr [RSP + 0x88]
  0x14022CD11 | MOV RAX,RCX
  0x14022CD1C | MOV RCX,RAX
  0x14022CD1F | CALL 0x14021eb40
  0x14022CD29 | MOV RAX,qword ptr [RSP + 0xb8]
  0x14022CD31 | MOV RCX,qword ptr [RSP + 0x70]
  0x14022CD36 | MOVSS XMM0,dword ptr [RAX]
  0x14022CD3A | SUBSS XMM0,dword ptr [RCX]
  0x14022CD44 | MOV RAX,qword ptr [RSP + 0xb8]
  0x14022CD4C | MOV RCX,qword ptr [RSP + 0x70]
  0x14022CD51 | MOVSS XMM0,dword ptr [RAX + 0x4]
  0x14022CD56 | SUBSS XMM0,dword ptr [RCX + 0x4]
  0x14022CD61 | MOV RAX,qword ptr [RSP + 0xb8]

3) RCX_SOURCE_CANDIDATE
  PRIMARY_SOURCE = MOV RCX,RAX

4) OBJECT_FIELD_CANDIDATES
  RAX+0x8 @0x14022CCBB | MOV EAX,dword ptr [RAX + 0x8]
  RAX+0x0 @0x14022CCF2 | MOV RAX,qword ptr [RAX]
  RAX+0x0 @0x14022CD36 | MOVSS XMM0,dword ptr [RAX]
  RCX+0x0 @0x14022CD3A | SUBSS XMM0,dword ptr [RCX]
  RAX+0x4 @0x14022CD51 | MOVSS XMM0,dword ptr [RAX + 0x4]
  RCX+0x4 @0x14022CD56 | SUBSS XMM0,dword ptr [RCX + 0x4]

5) SUBSTRUCTURE_POINTER_CANDIDATES
  NONE_FOUND

6) STATIC_CONFIDENCE
  RCX_OBJECT_SOURCE = HIGH_CONFIDENCE
  VECTOR +0/+4/+8 = CONFIRMED_VECTOR_ACCESS
  ROOTCOMPONENT_TRANSFORM_RELATION = NOT_PROVEN

TOTAL_CALLERS=6

============================================================
FONCTIONS RELEVANTES
============================================================

KEYWORD = RootComponent
  0x1400D8540 : `dynamic_initializer_for_'ENGINE_BPAttachedRootComponent''
  0x1400DA580 : `dynamic_initializer_for_'ENGINE_NetAttachRootComponentTo''
  0x1400DA5C0 : `dynamic_initializer_for_'ENGINE_NetDetachRootComponentFromAny''
  0x1409BCEA0 : AttachRootComponentTo
  0x142862BD0 : IsRootComponentCollisionRegistered
  0x142863C70 : AttachRootComponentTo
  0x142863F40 : AttachRootComponentToActor
  0x142864080 : DetachRootComponentFromParent
  0x142864940 : IsRootComponentStatic
  0x142864970 : IsRootComponentStationary
  0x1428649B0 : IsRootComponentMovable
  0x14286AD50 : SetRootComponent
  0x142874420 : NetAttachRootComponentTo_Implementation
  0x1428745D0 : NetDetachRootComponentFromAny_Implementation
  0x142F97AE0 : BPAttachedRootComponent
  0x142F988B0 : NetAttachRootComponentTo
  0x1430349E0 : Z_Construct_UFunction_AActor_BPAttachedRootComponent
  0x14303D480 : Z_Construct_UFunction_AActor_DetachRootComponentFromParent
  0x14304F340 : Z_Construct_UFunction_AActor_K2_AttachRootComponentTo
  0x14304FAC0 : Z_Construct_UFunction_AActor_K2_AttachRootComponentToActor
  0x143050F20 : Z_Construct_UFunction_AActor_K2_GetRootComponent
  0x14305D5D0 : Z_Construct_UFunction_AActor_NetAttachRootComponentTo
  0x14305DCC0 : Z_Construct_UFunction_AActor_NetDetachRootComponentFromAny
  0x14306D540 : Z_Construct_UFunction_AActor_SnapRootComponentTo
  0x1433434B0 : execSnapRootComponentTo
  0x143344F90 : execNetAttachRootComponentTo
  0x143347A10 : execK2_GetRootComponent
  0x143347C30 : execK2_AttachRootComponentToActor
  0x143347DC0 : execK2_AttachRootComponentTo
  0x143349EB0 : execDetachRootComponentFromParent
  FOUND=30

KEYWORD = SceneComponent
  0x1400CF990 : `dynamic_initializer_for_'AutoInitializeUSceneComponent''
  0x1400DBB40 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_USceneComponent''
  0x14015A390 : TSubobjectPtr<USceneComponent>
  0x14015A3C0 : CreateDefaultSubobject<USceneComponent>
  0x14015A4A0 : CreateDefaultSubobject<USceneComponent,USceneComponent>
  0x14015B0E0 : Get<USceneComponent,USceneComponent>
  0x14015B520 : ConstructObject<USceneComponent>
  0x140166B70 : ~USceneComponent
  0x1402F76D0 : TSubobjectPtr<USceneComponent><USceneComponent>
  0x14077E940 : Cast<USceneComponent>
  0x140B93080 : GetComponents<USceneComponent>
  0x142864160 : DetachSceneComponentsFromParent
  0x142873EB0 : GetAllSceneComponents
  0x142894C40 : Emplace<USceneComponent_*___ptr64_const_&___ptr64>
  0x142B0C490 : USceneComponent
  0x142F936E0 : StaticRegisterNativesUSceneComponent
  0x143012CC0 : Z_Construct_UEnum_USceneComponent_ERelativeTransformSpace
  0x1430130F0 : Z_Construct_UEnum_USceneComponent_EDetailMode
  0x143013520 : Z_Construct_UScriptStruct_USceneComponent_FOverlapInfo
  0x1430137C0 : Z_Construct_UFunction_USceneComponent_AddLocalOffset
  0x143013DA0 : Z_Construct_UFunction_USceneComponent_AddLocalRotation
  0x143014380 : Z_Construct_UFunction_USceneComponent_AddLocalTransform
  0x143014960 : Z_Construct_UFunction_USceneComponent_AddRelativeLocation
  0x143014F40 : Z_Construct_UFunction_USceneComponent_AddRelativeRotation
  0x143015520 : Z_Construct_UFunction_USceneComponent_AddWorldOffset
  0x143015B00 : Z_Construct_UFunction_USceneComponent_AddWorldRotation
  0x1430160E0 : Z_Construct_UFunction_USceneComponent_AddWorldTransform
  0x1430166C0 : Z_Construct_UFunction_USceneComponent_BP_GetCollisionEnabled
  0x1430169F0 : Z_Construct_UFunction_USceneComponent_DetachFromParent
  0x143016E60 : Z_Construct_UFunction_USceneComponent_DoesSocketExist
  0x1430173C0 : Z_Construct_UFunction_USceneComponent_GetAllSocketNames
  0x1430177E0 : Z_Construct_UFunction_USceneComponent_GetAttachParent
  0x143017B10 : Z_Construct_UFunction_USceneComponent_GetChildComponent
  0x143017F30 : Z_Construct_UFunction_USceneComponent_GetChildrenComponents
  0x1430185C0 : Z_Construct_UFunction_USceneComponent_GetComponentVelocity
  0x143018960 : Z_Construct_UFunction_USceneComponent_GetForwardVector
  0x143018D00 : Z_Construct_UFunction_USceneComponent_GetNumChildrenComponents
  0x143019020 : Z_Construct_UFunction_USceneComponent_GetParentComponents
  0x143019460 : Z_Construct_UFunction_USceneComponent_GetPhysicsVolume
  0x1430197B0 : Z_Construct_UFunction_USceneComponent_GetRelativeTransform
  ...
  FOUND=40

KEYWORD = USceneComponent
  0x1400CF990 : `dynamic_initializer_for_'AutoInitializeUSceneComponent''
  0x1400DBB40 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_USceneComponent''
  0x14015A390 : TSubobjectPtr<USceneComponent>
  0x14015A3C0 : CreateDefaultSubobject<USceneComponent>
  0x14015A4A0 : CreateDefaultSubobject<USceneComponent,USceneComponent>
  0x14015B0E0 : Get<USceneComponent,USceneComponent>
  0x14015B520 : ConstructObject<USceneComponent>
  0x140166B70 : ~USceneComponent
  0x1402F76D0 : TSubobjectPtr<USceneComponent><USceneComponent>
  0x14077E940 : Cast<USceneComponent>
  0x140B93080 : GetComponents<USceneComponent>
  0x142894C40 : Emplace<USceneComponent_*___ptr64_const_&___ptr64>
  0x142B0C490 : USceneComponent
  0x142F936E0 : StaticRegisterNativesUSceneComponent
  0x143012CC0 : Z_Construct_UEnum_USceneComponent_ERelativeTransformSpace
  0x1430130F0 : Z_Construct_UEnum_USceneComponent_EDetailMode
  0x143013520 : Z_Construct_UScriptStruct_USceneComponent_FOverlapInfo
  0x1430137C0 : Z_Construct_UFunction_USceneComponent_AddLocalOffset
  0x143013DA0 : Z_Construct_UFunction_USceneComponent_AddLocalRotation
  0x143014380 : Z_Construct_UFunction_USceneComponent_AddLocalTransform
  0x143014960 : Z_Construct_UFunction_USceneComponent_AddRelativeLocation
  0x143014F40 : Z_Construct_UFunction_USceneComponent_AddRelativeRotation
  0x143015520 : Z_Construct_UFunction_USceneComponent_AddWorldOffset
  0x143015B00 : Z_Construct_UFunction_USceneComponent_AddWorldRotation
  0x1430160E0 : Z_Construct_UFunction_USceneComponent_AddWorldTransform
  0x1430166C0 : Z_Construct_UFunction_USceneComponent_BP_GetCollisionEnabled
  0x1430169F0 : Z_Construct_UFunction_USceneComponent_DetachFromParent
  0x143016E60 : Z_Construct_UFunction_USceneComponent_DoesSocketExist
  0x1430173C0 : Z_Construct_UFunction_USceneComponent_GetAllSocketNames
  0x1430177E0 : Z_Construct_UFunction_USceneComponent_GetAttachParent
  0x143017B10 : Z_Construct_UFunction_USceneComponent_GetChildComponent
  0x143017F30 : Z_Construct_UFunction_USceneComponent_GetChildrenComponents
  0x1430185C0 : Z_Construct_UFunction_USceneComponent_GetComponentVelocity
  0x143018960 : Z_Construct_UFunction_USceneComponent_GetForwardVector
  0x143018D00 : Z_Construct_UFunction_USceneComponent_GetNumChildrenComponents
  0x143019020 : Z_Construct_UFunction_USceneComponent_GetParentComponents
  0x143019460 : Z_Construct_UFunction_USceneComponent_GetPhysicsVolume
  0x1430197B0 : Z_Construct_UFunction_USceneComponent_GetRelativeTransform
  0x143019B50 : Z_Construct_UFunction_USceneComponent_GetRightVector
  0x143019EF0 : Z_Construct_UFunction_USceneComponent_GetSocketLocation
  ...
  FOUND=40

KEYWORD = GetRootComponent
  0x143050F20 : Z_Construct_UFunction_AActor_K2_GetRootComponent
  0x143347A10 : execK2_GetRootComponent
  FOUND=2

KEYWORD = GetActorLocation
  0x1430507E0 : Z_Construct_UFunction_AActor_K2_GetActorLocation
  0x143347AA0 : execK2_GetActorLocation
  FOUND=2

KEYWORD = SetActorLocation
  0x140C79700 : DoSetActorLocation
  0x14286A1D0 : SetActorLocation
  0x14286A450 : SetActorLocationAndRotation
  0x143051C40 : Z_Construct_UFunction_AActor_K2_SetActorLocation
  0x143068DF0 : Z_Construct_UFunction_AActor_SetActorLocationAndRotation
  0x1433440E0 : execSetActorLocationAndRotation
  0x1433478D0 : execK2_SetActorLocation
  FOUND=7

KEYWORD = GetComponentLocation
  0x14301CF30 : Z_Construct_UFunction_USceneComponent_K2_GetComponentLocation
  FOUND=1

KEYWORD = SetWorldLocation
  0x142B0DA10 : SetWorldLocation
  0x142B0E170 : SetWorldLocationAndRotation
  0x142B0E1B0 : SetWorldLocationAndRotation
  0x142B0E470 : SetWorldLocationAndRotationNoPhysics
  0x142B10A20 : InternalSetWorldLocationAndRotation
  0x142B8E340 : SetWorldLocationAtSplinePoint
  0x142F53630 : execSetWorldLocationAtSplinePoint
  0x143021FB0 : Z_Construct_UFunction_USceneComponent_SetWorldLocation
  0x143022590 : Z_Construct_UFunction_USceneComponent_SetWorldLocationAndRotation
  0x14334B960 : execSetWorldLocationAndRotation
  0x14334BAE0 : execSetWorldLocation
  0x14335D780 : Z_Construct_UFunction_USplineComponent_SetWorldLocationAtSplinePoint
  FOUND=12

KEYWORD = GetWorldLocation
  0x14021EB40 : GetWorldLocation
  0x142B12F80 : GetWorldLocation
  0x142B8E570 : GetWorldLocationAtSplinePoint
  0x142B8E9D0 : GetWorldLocationAtDistanceAlongSpline
  0x142B8EFD0 : GetWorldLocationAtTime
  0x142F53EA0 : execGetWorldLocationAtTime
  0x142F53FE0 : execGetWorldLocationAtSplinePoint
  0x142F540A0 : execGetWorldLocationAtDistanceAlongSpline
  0x14301B5D0 : Z_Construct_UFunction_USceneComponent_GetWorldLocation
  0x14334C770 : execGetWorldLocation
  0x14335A170 : Z_Construct_UFunction_USplineComponent_GetWorldLocationAtDistanceAlongSpline
  0x14335A600 : Z_Construct_UFunction_USplineComponent_GetWorldLocationAtSplinePoint
  0x14335AA90 : Z_Construct_UFunction_USplineComponent_GetWorldLocationAtTime
  FOUND=13

KEYWORD = GetWorldLocationAtTime
  0x142B8EFD0 : GetWorldLocationAtTime
  0x142F53EA0 : execGetWorldLocationAtTime
  0x14335AA90 : Z_Construct_UFunction_USplineComponent_GetWorldLocationAtTime
  FOUND=3

KEYWORD = RelativeLocation
  0x14286A730 : SetActorRelativeLocation
  0x142B0D0C0 : SetRelativeLocationAndRotation
  0x143014960 : Z_Construct_UFunction_USceneComponent_AddRelativeLocation
  0x14301FC80 : Z_Construct_UFunction_USceneComponent_SetRelativeLocation
  0x143020260 : Z_Construct_UFunction_USceneComponent_SetRelativeLocationAndRotation
  0x143069760 : Z_Construct_UFunction_AActor_SetActorRelativeLocation
  0x143343FA0 : execSetActorRelativeLocation
  0x14334BFE0 : execSetRelativeLocationAndRotation
  0x14334C160 : execSetRelativeLocation
  0x14334D9D0 : execAddRelativeLocation
  FOUND=10

KEYWORD = WorldLocation
  0x14007EDE0 : `dynamic_initializer_for_'SHOOTERGAME_GetCompanionWorldLocation''
  0x14021EB40 : GetWorldLocation
  0x140229D70 : GetAvoidanceAreaWorldLocation
  0x140283320 : GetPingWorldLocation
  0x140283350 : GetPingWorldLocation
  0x1402865F0 : GetPointOfInterestWorldLocation
  0x140287660 : GetPointWorldLocation
  0x1402FA010 : FindLocationAndDirectionClosestToWorldLocation
  0x140307F60 : GetMissionWorldIndicatorWorldLocation
  0x140451570 : GetCompanionWorldLocation_Implementation
  0x140485300 : GetGrappleAnchorWorldLocation
  0x140567D70 : AttachedToOtherCharacterUpdateWorldLocation
  0x1415C4200 : ActorHasLineOfSightToWorldLocation
  0x1416475D0 : ProjectWorldLocationToScreenOrScreenEdgePosition
  0x141717670 : GetCompanionWorldLocation
  0x1419FBAC0 : execProjectWorldLocationToScreenOrScreenEdgePosition
  0x141A139A0 : execActorHasLineOfSightToWorldLocation
  0x141A3AC40 : execGetPointOfInterestWorldLocation
  0x141A3B530 : execGetPingWorldLocation
  0x141A4A090 : execGetGrappleAnchorWorldLocation
  0x141A6BA90 : execAttachedToOtherCharacterUpdateWorldLocation
  0x141A6F790 : execGetCompanionWorldLocation
  0x141A80210 : execGetMissionWorldIndicatorWorldLocation
  0x141A8C660 : execFindLocationAndDirectionClosestToWorldLocation
  0x141A96D10 : execGetAvoidanceAreaWorldLocation
  0x141AE38C0 : Z_Construct_UFunction_UFlockingBehavior_GetAvoidanceAreaWorldLocation
  0x141B11C30 : Z_Construct_UFunction_AMissionSpline_FindLocationAndDirectionClosestToWorldLocation
  0x141B79DB0 : FDetermineBitMask_MissionType_eventAddPlayersInRadiusToMission_Parms_bPrioritizeByDistanceToWorldLocation
  0x141B8FCF0 : Z_Construct_UFunction_AMissionType_GetMissionWorldIndicatorWorldLocation
  0x141C2E0A0 : Z_Construct_UFunction_APrimalBuff_Companion_GetCompanionWorldLocation
  0x141C543F0 : Z_Construct_UFunction_APrimalCharacter_AttachedToOtherCharacterUpdateWorldLocation
  0x141DCB250 : Z_Construct_UFunction_APrimalBuff_Grappled_GetGrappleAnchorWorldLocation
  0x141E53290 : Z_Construct_UFunction_UHUDPingWidget_GetPingWorldLocation
  0x141E56A20 : Z_Construct_UFunction_UHUDPointOfInterestWidget_GetPointOfInterestWorldLocation
  0x141FBF840 : Z_Construct_UFunction_UVictoryCore_ActorHasLineOfSightToWorldLocation
  0x1420178C0 : Z_Construct_UFunction_UVictoryCore_ProjectWorldLocationToScreenOrScreenEdgePosition
  0x142ABF0D0 : ProjectWorldLocationToScreen
  0x142ABF100 : ProjectWorldLocationToScreen
  0x142B0DA10 : SetWorldLocation
  0x142B0E170 : SetWorldLocationAndRotation
  ...
  FOUND=40

KEYWORD = Location
  0x140040C40 : compute_allocation
  0x140060170 : `dynamic_initializer_for_'GForceCameraLocation''
  0x14006A730 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FAliveNameAndLocation''
  0x140074370 : `dynamic_initializer_for_'SHOOTERGAME_BP_OverrideCameraTargetOriginLocation''
  0x140075660 : `dynamic_initializer_for_'SHOOTERGAME_BPCheckCanDinoSpawnFromLocation''
  0x140075690 : `dynamic_initializer_for_'SHOOTERGAME_BPCheckCanSpawnFromLocation''
  0x1400763B0 : `dynamic_initializer_for_'SHOOTERGAME_BPGetBoidSpawnLocationAndVelocity''
  0x140076440 : `dynamic_initializer_for_'SHOOTERGAME_BPGetCrosshairLocation''
  0x1400767A0 : `dynamic_initializer_for_'SHOOTERGAME_BPGetFPVViewLocation''
  0x140076B90 : `dynamic_initializer_for_'SHOOTERGAME_BPGetMissionStartLocation''
  0x140076E30 : `dynamic_initializer_for_'SHOOTERGAME_BPGetRiderUnboardLocation''
  0x140076F20 : `dynamic_initializer_for_'SHOOTERGAME_BPGetSocketLocation''
  0x140077C10 : `dynamic_initializer_for_'SHOOTERGAME_BPModifyAimOffsetTargetLocation''
  0x140079620 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideFloatingHUDLocation''
  0x1400796B0 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideFPVViewLocation''
  0x140079920 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideLandingLocation''
  0x140079AD0 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideRandomWanderLocation''
  0x140079CB0 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideTargetLocation''
  0x14007B900 : `dynamic_initializer_for_'SHOOTERGAME_BuffOverrideFinalWanderLocation''
  0x14007C6B0 : `dynamic_initializer_for_'SHOOTERGAME_ClientGetAllPlayerNamesAndLocations''
  0x14007D6A0 : `dynamic_initializer_for_'SHOOTERGAME_ClientRequestSpectatorLocationAndRotation''
  0x14007DB20 : `dynamic_initializer_for_'SHOOTERGAME_ClientSetSpectatorLocation''
  0x14007EDE0 : `dynamic_initializer_for_'SHOOTERGAME_GetCompanionWorldLocation''
  0x14007F380 : `dynamic_initializer_for_'SHOOTERGAME_GetPlayerSpawnLocation''
  0x140080010 : `dynamic_initializer_for_'SHOOTERGAME_IsRainingAtLocation''
  0x140080BE0 : `dynamic_initializer_for_'SHOOTERGAME_NetSetLocation''
  0x140080E80 : `dynamic_initializer_for_'SHOOTERGAME_NetUpdateLocation''
  0x140082800 : `dynamic_initializer_for_'SHOOTERGAME_OverrideFinalWanderLocation''
  0x140082830 : `dynamic_initializer_for_'SHOOTERGAME_OverrideRandomWanderLocation''
  0x140083F70 : `dynamic_initializer_for_'SHOOTERGAME_ServerGetAllPlayerNamesAndLocations''
  0x1400846C0 : `dynamic_initializer_for_'SHOOTERGAME_ServerRecieveSpectatorLocationAndRotation''
  0x140085830 : `dynamic_initializer_for_'SHOOTERGAME_ServerSetItemBalloonLocation''
  0x140095AC0 : SameLocation''
  0x1400AAFA0 : `dynamic_initializer_for_'AllocationList''
  0x1400AAFB0 : `dynamic_initializer_for_'AllocationMap''
  0x1400B1630 : `dynamic_initializer_for_'AIMODULE_ProvideLocationsSet''
  0x1400B16B0 : `dynamic_initializer_for_'AIMODULE_ProvideSingleLocation''
  0x1400B74C0 : SlaveLocations''
  0x1400CBAF0 : `dynamic_initializer_for_'CVarMaxParticleTilePreAllocation''
  0x1400D19C0 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FWeightmapLayerAllocationInfo''
  ...
  FOUND=40

KEYWORD = Transform
  0x1400658A0 : `dynamic_initializer_for_'GScreenProjectionGlobalTransform''
  0x140069CB0 : `dynamic_initializer_for_'AutoInitializeUAnimInstance_DinoRootTransform''
  0x1400743A0 : `dynamic_initializer_for_'SHOOTERGAME_BP_OverrideCarriedCharacterTransform''
  0x140079B60 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideSnappedFromTransform''
  0x140079B90 : `dynamic_initializer_for_'SHOOTERGAME_BPOverrideSnappedToTransform''
  0x140080AC0 : `dynamic_initializer_for_'SHOOTERGAME_NetResetTransformAndVelocity''
  0x140087000 : `dynamic_initializer_for_'SHOOTERGAME_Tick_UpdateCompanionTransform''
  0x1400876F0 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UAnimInstance_DinoRootTransform''
  0x140095910 : Animation_TransformError''
  0x140098CD0 : `dynamic_initializer_for_'Transform_Ops''
  0x14009C920 : `dynamic_initializer_for_'UObjectexecTransformConstRegistar''
  0x14009C9A0 : `dynamic_initializer_for_'UObjectexecTransformConstBytecodeTemp''
  0x1400A2BE0 : `dynamic_initializer_for_'bTestTransformCalculus''
  0x1400B29B0 : `dynamic_initializer_for_'AutoInitializeUMovieScene3DTransformSection''
  0x1400B29D0 : `dynamic_initializer_for_'AutoInitializeUMovieScene3DTransformTrack''
  0x1400B2C30 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMovieScene3DTransformSection''
  0x1400B2C40 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMovieScene3DTransformTrack''
  0x1400B3020 : `dynamic_initializer_for_'AutoInitializeUMovieScene2DTransformSection''
  0x1400B3040 : `dynamic_initializer_for_'AutoInitializeUMovieScene2DTransformTrack''
  0x1400B3180 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FWidgetTransform''
  0x1400B3190 : `dynamic_initializer_for_'ScriptStruct_UMG_StaticRegisterNativesFWidgetTransform''
  0x1400B41B0 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMovieScene2DTransformSection''
  0x1400B41C0 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMovieScene2DTransformTrack''
  0x1400D2270 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FBoneTransform''
  0x1400D5610 : `dynamic_initializer_for_'AutoInitializeUMaterialExpressionTransform''
  0x1400D5630 : `dynamic_initializer_for_'AutoInitializeUMaterialExpressionTransformPosition''
  0x1400D6F00 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FRigTransformConstraint''
  0x1400D6F10 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FTransformBaseConstraint''
  0x1400D6F20 : `dynamic_initializer_for_'Z_CompiledInDeferStruct_UScriptStruct_FTransformBase''
  0x1400DE050 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMaterialExpressionTransform''
  0x1400DE060 : `dynamic_initializer_for_'Z_CompiledInDefer_UClass_UMaterialExpressionTransformPosition''
  0x140156F20 : UAnimInstance_DinoRootTransform
  0x1401943E0 : TAttribute<TOptional<FTransform2D>_>
  0x1401945C0 : ~TAttribute<TOptional<FTransform2D>_>
  0x14019A770 : FTransform2D
  0x14019A820 : GetAccumulatedRenderTransform
  0x1401B7390 : FSlateLayoutTransform
  0x140229BE0 : SetAvoidanceAreaTransform
  0x140229C40 : SetAvoidanceAreaArrayTransform
  0x140249D10 : HibernateShouldSerializeTransform
  ...
  FOUND=40

KEYWORD = SetRelativeLocation
  0x142B0D0C0 : SetRelativeLocationAndRotation
  0x14301FC80 : Z_Construct_UFunction_USceneComponent_SetRelativeLocation
  0x143020260 : Z_Construct_UFunction_USceneComponent_SetRelativeLocationAndRotation
  0x14334BFE0 : execSetRelativeLocationAndRotation
  0x14334C160 : execSetRelativeLocation
  FOUND=5

KEYWORD = GetRelativeLocation
  FOUND=0

============================================================
CONCLUSION V18
============================================================
CONFIRMED
HIGH_CONFIDENCE
POSSIBLE
NOT_PROVEN
