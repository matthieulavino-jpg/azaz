# azazSHOOTERGAME STATIC ANALYSIS V4
Ghidra 12.1.3
Program: ShooterGame.exe
Time: 58969 ms

#1 SCORE=3538 REFS=299 CALLS=1652 FIELDS=32
NAME: Z_Construct_UClass_AActor
ADDR: 1430700e0
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalStructureTurret
  - CALLS:Z_Construct_UFunction_AActor_GetTargetingLocation
  - CALLS:Z_Construct_UFunction_AActor_GetLifeSpan
  - CALLS:Z_Construct_UFunction_AActor_SetActorEnableCollision
  - CALLS:Z_Construct_UFunction_AActor_BPForceAllowsInventoryUse
  - CALLS:Z_Construct_UFunction_AActor_IsDead
  - CALLS:Z_Construct_UFunction_AActor_AddActorWorldTransform
  - CALLS:FDetermineBitMask_AActor_bPreventNPCSpawnFloor
  - CALLS:Z_Construct_UFunction_AActor_AddActorLocalOffset
  - CALLS:Z_Construct_UFunction_AActor_ServerSendExecCommandToPlayer
  - CALLS:Z_Construct_UFunction_AActor_K2_GetActorLocation
  - CALLS:FDetermineBitMask_AActor_bPreventCharacterBasing
  - CALLS:Z_Construct_UFunction_AActor_ServerSendExecCommandToEveryone
  - CALLS:Z_Construct_UFunction_AActor_AddTickPrerequisiteComponent
  - CALLS:Z_Construct_UFunction_AActor_GetInterpolatedLocation
  - CALLS:Z_Construct_UFunction_AActor_ServerSendSimpleExecCommandToEveryone
  - FIELD@14307246b:LEA RCX,[RBP + -0x80]
  - CALLS:Z_Construct_UFunction_AActor_MakeNoise
  - CALLS:Z_Construct_UFunction_AActor_GetHorizontalDistanceTo
  - CALLS:Z_Construct_UFunction_AActor_OnRep_ReplicatedMovement
  - CALLS:Z_Construct_UFunction_AActor_IsCorruptDino
  - CALLS:Z_Construct_UFunction_AActor_SetActorRelativeRotation
  - CALLS:Z_Construct_UFunction_AActor_TryMultiUse
  - CALLS:Z_Construct_UFunction_AActor_ActorPlaySound
  - CALLS:Z_Construct_UFunction_AActor_DrawInEditorViewport
  - CALLS:Z_Construct_UFunction_AActor_NetAttachRootComponentTo
  - CALLS:Z_Construct_UFunction_AActor_IsLocallyControlledByPlayer
  - CALLS:Z_Construct_UFunction_AActor_MulticastPropertyToPlayer
  - CALLS:FDetermineBitMask_AActor_bUseBPGetHUDDrawLocationOffset
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugCoordinateSystem
  - CALLS:Z_Construct_UFunction_AActor_GetHorizontalDotProductTo
  - CALLS:Z_Construct_UFunction_AActor_AddActorWorldRotation
  - CALLS:Z_Construct_UFunction_AActor_ReceiveEndPlay
  - FIELD@143071e97:LEA RCX,[RBP + -0x28]
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorBeginOverlap
  - FIELD@14307196c:LEA RCX,[RBP + -0x58]
  - CALLS:Z_Construct_UFunction_AActor_SetTickFunctionEnabled
  - CALLS:Z_Construct_UFunction_AActor_BPGetBonesToHideOnAllocation
  - CALLS:Z_Construct_UFunction_AActor_BPGetMultiUseCenterText
  - CALLS:Z_Construct_UFunction_AActor_BPInventoryItemUsed
  - CALLS:Z_Construct_UScriptStruct_AActor_FMultiUseEntry
  - CALLS:Z_Construct_UFunction_AActor_ReceiveInput
  - CALLS:Z_Construct_UFunction_AActor_ReceivePointDamage
  - CALLS:Z_Construct_UEnum_AActor_EBPMapCheckSeverity
  - CALLS:Z_Construct_UFunction_AActor_AllowGrappling
  - CALLS:Z_Construct_UFunction_AActor_CalculateComponentsBoundingBoxInLocalSpace
  - CALLS:Z_Construct_UFunction_AActor_ActorSemaphoreTaken__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_GetComponentByCustomTag
  - CALLS:Z_Construct_UFunction_AActor_BPGetShowDebugAnimationComponents
  - CALLS:Z_Construct_UFunction_AActor_GetDotProductTo
  - CALLS:Z_Construct_UFunction_AActor_ActorHitSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_GetActorClass
  - FIELD@143072631:LEA RCX,[RBP + -0x60]
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugCapsuleWithExtents
  - CALLS:Z_Construct_UFunction_AActor_AddActorWorldOffset
  - CALLS:Z_Construct_UFunction_AActor_SetTickableWhenPaused
  - FIELD@14307254c:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UFunction_AActor_GetComponentsByCustomTag
  - CALLS:Z_Construct_UFunction_AActor_PlaySoundAtLocation
  - CALLS:Z_Construct_UFunction_AActor_K2_SetActorLocation
  - FIELD@143071db5:LEA RCX,[RBP + -0x78]
  - FIELD@143072093:MOV R8,qword ptr [RBP + -0x38]
  - CALLS:Z_Construct_UFunction_AActor_BPGetActorEyesViewPoint
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalCharacterOrStructure
  - CALLS:Z_Construct_UFunction_AActor_GetInputAxisKeyValue
  - CALLS:Z_Construct_UFunction_AActor_IsTargetable
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugLineTraceHitResult
  - CALLS:Z_Construct_UFunction_AActor_ActorHasTag
  - FIELD@143071eb6:MOV R8,qword ptr [RBP + -0x28]
  - CALLS:Z_Construct_UFunction_AActor_GetComponentByClass
  - CALLS:Z_Construct_UFunction_AActor_SetReplicates
  - CALLS:Z_Construct_UFunction_AActor_GetInstigatorController
  - CALLS:Z_Construct_UFunction_AActor_GetOverlappingActors
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorOnInputTouchEnter
  - CALLS:Z_Construct_UFunction_AActor_MulticastProperty
  - CALLS:Z_Construct_UFunction_AActor_ActorEndPlaySignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_ModifyHudMultiUseLoc
  - CALLS:Z_Construct_UFunction_AActor_GetInstigator
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugArrow
  - AACTOR
  - CALLS:FDetermineBitMask_AActor_bPreventCharacterBasingAllowSteppingUp
  - CALLS:Z_Construct_UFunction_AActor_GetOwner
  - CALLS:Z_Construct_UScriptStruct_AActor_FNetExecParams
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugLine
  - CALLS:Z_Construct_UFunction_AActor_SetActorRotation
  - CALLS:Z_Construct_UFunction_AActor_BPPreventAttachments
  - CALLS:Z_Construct_UScriptStruct_UEngineTypes_FRepMovement
  - CALLS:Z_Construct_UFunction_AActor_BPCheckForErrors
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalDino
  - FIELD@1430700f8:LEA RBP,[RSP + -0xe410]
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugString
  - CALLS:Z_Construct_UFunction_AActor_DisableInput
  - CALLS:Z_Construct_UFunction_AActor_GetInputAxisValue
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugCylinder
  - CALLS:Z_Construct_UFunction_AActor_GetOwnerController
  - CALLS:Z_Construct_UFunction_AActor_BPConsumeUsePinCode
  - CALLS:Z_Construct_UFunction_AActor_BP_OverrideTargetingLocation
  - CALLS:Z_Construct_UFunction_AActor_K2_DestroyComponent
  - CALLS:Z_Construct_UFunction_AActor_K2_GetWorld
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorOnInputTouchEnd
  - CALLS:Z_Construct_UFunction_AActor_SetNetworkSpatializationParent
  - CALLS:Z_Construct_UFunction_AActor_GetUsablePriority
  - FIELD@14307256b:MOV R8,qword ptr [RBP + -0x70]
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugPoint
  - CALLS:Z_Construct_UFunction_AActor_ReceiveAnyDamage
  - CALLS:Z_Construct_UScriptStruct_UEngineBaseTypes_FActorTickFunction
  - CALLS:Z_Construct_UFunction_AActor_BPIsA
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorOnInputTouchLeave
  - CALLS:Z_Construct_UScriptStruct_AActor_FBPNetExecParams
  - CALLS:Z_Construct_UFunction_AActor_BP_GetHUDWorldDrawLocation
  - CALLS:Z_Construct_UFunction_AActor_BPClientHandleNetExecCommand
  - CALLS:Z_Construct_UFunction_AActor_BPOverrideUILocation
  - CALLS:Z_Construct_UFunction_AActor_IsOwnedOrControlledBy
  - CALLS:Z_Construct_UFunction_AActor_GetOverlappingComponents
  - CALLS:Z_Construct_UFunction_AActor_GetInputVectorAxisValue
  - CALLS:Z_Construct_UFunction_AActor_SetLifeSpan
  - CALLS:Z_Construct_UFunction_AActor_GetAttachedActors
  - CALLS:Z_Construct_UFunction_AActor_GetAttachedSoundVolumeMultiplier
  - FIELD@14307248a:MOV R8,qword ptr [RBP + -0x80]
  - CALLS:FDetermineBitMask_AActor_bIgnoredByCharacterEncroachment
  - CALLS:Z_Construct_UFunction_AActor_GetActorRelativeScale3D
  - CALLS:Z_Construct_UFunction_AActor_TakeAnyDamageSignature__DelegateSignature
  - FIELD@14307228e:MOV R8,qword ptr [RBP + -0x18]
  - CALLS:Z_Construct_UFunction_AActor_ReceiveRadialDamage
  - CALLS:Z_Construct_UFunction_AActor_GetActorBounds
  - FIELD@14307198b:MOV R8,qword ptr [RBP + -0x58]
  - CALLS:Z_Construct_UFunction_AActor_GetVisibleComponentByClass
  - NAME:ACTOR
  - FIELD@143071bdc:LEA RCX,[RBP + -0x10]
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorEndOverlap
  - CALLS:Z_Construct_UFunction_AActor_AllowIgnoreCharacterEncroachment
  - CALLS:Z_Construct_UFunction_AActor_BPInventoryItemDropped
  - CALLS:Z_Construct_UFunction_AActor_K2_GetRootComponent
  - CALLS:FDetermineBitMask_AActor_bReplicateVelocityHighQuality
  - CALLS:FDetermineBitMask_AActor_bReplicateRotationHighQuality
  - CALLS:Z_Construct_UFunction_AActor_BPCustomIsRelevantForClient
  - CALLS:Z_Construct_UFunction_AActor_GetActorRightVector
  - CALLS:Z_Construct_UFunction_AActor_AddComponent
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugPlane
  - CALLS:Z_Construct_UFunction_AActor_SnapRootComponentTo
  - CALLS:Z_Construct_UFunction_AActor_DrawBasicFloatingHUD
  - CALLS:Z_Construct_UFunction_AActor_GetActorUpVector
  - CALLS:Z_Construct_UFunction_AActor_TakePointDamageSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_K2_OnBecomeViewTarget
  - CALLS:Z_Construct_UFunction_AActor_ReceiveHit
  - CALLS:Z_Construct_UFunction_AActor_DetachRootComponentFromParent
  - CALLS:Z_Construct_UFunction_AActor_GetActorEnableCollision
  - CALLS:Z_Construct_UFunction_AActor_ForceNetUpdate
  - CALLS:Z_Construct_UFunction_AActor_ActorPlaySoundUnreliable
  - CALLS:Z_Construct_UFunction_AActor_GetDistanceTo
  - CALLS:Z_Construct_UFunction_AActor_SetActorScale3D
  - CALLS:Z_Construct_UFunction_AActor_K2_AttachRootComponentTo
  - CALLS:Z_Construct_UFunction_AActor_ForceReplicateNow
  - CALLS:FDetermineBitMask_AActor_bUseBPOverrideUILocation
  - CALLS:Z_Construct_UFunction_AActor_GetCharacterController
  - CALLS:GetPrivateStaticClassBody<AActor>
  - FIELD@143071bfb:MOV R8,qword ptr [RBP + -0x10]
  - FIELD@143071b15:MOV R8,qword ptr [RBP + -0x20]
  - CALLS:Z_Construct_UFunction_AActor_ActorOnInputTouchEndSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_AddActorLocalRotation
  - CALLS:Z_Construct_UFunction_AActor_AddTickPrerequisiteActor
  - CALLS:FDetermineBitMask_AActor_bUseBPGetBonesToHideOnAllocation
  - FIELD@143071f98:MOV R8,qword ptr [RBP + -0x68]
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugCamera
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugCapsule
  - FIELD@143072650:MOV R8,qword ptr [RBP + -0x60]
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalStructureItemContainer
  - CALLS:Z_Construct_UFunction_AActor_GetVerticalDistanceTo
  - CALLS:Z_Construct_UFunction_AActor_SetActorHiddenInGame
  - CALLS:Z_Construct_UFunction_AActor_SetActorRelativeTransform
  - CALLS:Z_Construct_UFunction_AActor_IsShooterCharacter
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugBox
  - CALLS:Z_Construct_UFunction_AActor_SetOwner
  - CALLS:Z_Construct_UFunction_AActor_GetAttachedSoundPitchMultiplier
  - FIELD@143071f79:LEA RCX,[RBP + -0x68]
  - CALLS:Z_Construct_UFunction_AActor_K2_GetActorRotation
  - CALLS:Z_Construct_UFunction_AActor_SetActorRelativeLocation
  - CALLS:Z_Construct_UScriptStruct_AActor_FBPMapCheckEntry
  - CALLS:Z_Construct_UFunction_AActor_ActorCustomEventSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_BPTryMultiUse
  - CALLS:Z_Construct_UFunction_AActor_ActorEndOverlapSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalStructure
  - CALLS:Z_Construct_UFunction_AActor_ReceiveActorOnInputTouchBegin
  - CALLS:Z_Construct_UFunction_AActor_GetTransform
  - CALLS:Z_Construct_UFunction_AActor_K2_OnEndViewTarget
  - CALLS:Z_Construct_UFunction_AActor_StopActorSound
  - CALLS:Z_Construct_UFunction_AActor_PlaySoundOnActor
  - CALLS:Z_Construct_UFunction_AActor_BPConsumeSetPinCode
  - CALLS:Z_Construct_UFunction_AActor_GetVelocity
  - CALLS:FDetermineBitMask_AActor_bReplicateMovement
  - CALLS:Z_Construct_UFunction_AActor_SetActorTransform
  - CALLS:FDetermineBitMask_AActor_bUseBPOverrideTargetingLocation
  - FIELD@14307226f:LEA RCX,[RBP + -0x18]
  - CALLS:Z_Construct_UFunction_AActor_BPGetMultiUseEntries
  - CALLS:Z_Construct_UFunction_AActor_IsFirstPersonMeshVisible
  - CALLS:Z_Construct_UFunction_AActor_GetSecondaryMountedActor
  - CALLS:Z_Construct_UFunction_AActor_NetDetachRootComponentFromAny
  - CALLS:Z_Construct_UFunction_AActor_GetInterpolatedRotation
  - CALLS:Z_Construct_UFunction_AActor_MulticastDrawDebugSphere
  - CALLS:Z_Construct_UFunction_AActor_GetActorViewDirection
  - CALLS:Z_Construct_UFunction_AActor_ActorEndTouchOverSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_GetAllSceneComponents
  - CALLS:Z_Construct_UFunction_AActor_MakeMIDForMaterial
  - CALLS:Z_Construct_UFunction_AActor_SetActorRelativeScale3D
  - CALLS:Z_Construct_UFunction_AActor_ClientMultiUse
  - CALLS:Z_Construct_UFunction_AActor_AddActorLocalTransform
  - CALLS:Z_Construct_UFunction_AActor_RemoveTickPrerequisiteActor
  - FIELD@143072074:LEA RCX,[RBP + -0x38]
  - CALLS:Z_Construct_UFunction_AActor_BPClientDoMultiUse
  - CALLS:Z_Construct_UFunction_AActor_BPAttachedRootComponent
  - CALLS:Z_Construct_UFunction_AActor_GetActorForwardVector
  - CALLS:Z_Construct_UFunction_AActor_K2_TeleportTo
  - CALLS:Z_Construct_UFunction_AActor_BPServerHandleNetExecCommand
  - FIELD@143071ccc:LEA RCX,[RBP + -0x48]
  - CALLS:Z_Construct_UFunction_AActor_ActorOnInputTouchBeginSignature__DelegateSignature
  - FIELD@143071afc:LEA RCX,[RBP + -0x20]
  - CALLS:Z_Construct_UFunction_AActor_GetInterpolatedTransform
  - FIELD@143071dd4:MOV R8,qword ptr [RBP + -0x78]
  - CALLS:Z_Construct_UFunction_AActor_GetComponentsByClass
  - CALLS:Z_Construct_UFunction_AActor_ReceiveTick
  - CALLS:Z_Construct_UFunction_AActor_GetActorTimeDilation
  - CALLS:Z_Construct_UFunction_AActor_IsPrimalCharacter
  - CALLS:Z_Construct_UFunction_AActor_AllowManualMultiUseActivation
  - CALLS:Z_Construct_UFunction_AActor_EnableInput
  - CALLS:Z_Construct_UFunction_AActor_GetActorScale3D
  - FIELD@143071ceb:MOV R8,qword ptr [RBP + -0x48]
  - CALLS:Z_Construct_UFunction_AActor_ActorBeginOverlapSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_ActorBeginTouchOverSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_AActor_HasAuthority
  - CALLS:Z_Construct_UFunction_AActor_K2_AttachRootComponentToActor
  - CALLS:Z_Construct_UFunction_AActor_PropertyServerToClients
  - CALLS:Z_Construct_UFunction_AActor_RemoveTickPrerequisiteComponent
  - CALLS:Z_Construct_UFunction_AActor_SetActorLocationAndRotation
  - CALLS:Z_Construct_UFunction_AActor_BPGetExtraSpecialBlueprintInt

#2 SCORE=3284 REFS=4 CALLS=496 FIELDS=2
NAME: GetPlacingGroundLocation
ADDR: 140a2bc40
  - FIELD@140a33274:MOV qword ptr [RSP + 0x5f8],-0x1
  - CALLS:Rotation
  - NAME:LOCATION
  - FIELD@140a2ff34:CMP EAX,-0x1
  - CALLS:GetSnapToLocation
  - CALLS:FRotationMatrix
  - CALLS:GetAttachedToStaticMeshTransform

#3 SCORE=2445 REFS=5 CALLS=56 FIELDS=113
NAME: GetParticleTransform
ADDR: 142e9fe10
  - FIELD@142e9fec0:MOVAPS xmmword ptr [RAX + -0x78],XMM9
  - FIELD@142ea02a1:MOV dword ptr [RBP + -0x18],0x0
  - FIELD@142ea004f:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@142e9feaa:MOV qword ptr [RAX + -0x30],R14
  - FIELD@142ea0188:MOVSS dword ptr [RBP + -0x10],XMM2
  - FIELD@142e9fe43:MOV qword ptr [RBP + -0xc],0x0
  - FIELD@142ea0116:MOV qword ptr [RBP + -0x80],0x0
  - FIELD@142e9fe88:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - FIELD@142e9fe90:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@142ea0299:MOV qword ptr [RBP + -0x20],0x0
  - FIELD@142e9ff01:MOVAPS xmmword ptr [RAX + -0xa8],XMM12
  - FIELD@142e9feae:MOV qword ptr [RAX + -0x38],R15
  - FIELD@142e9ff21:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@142e9fef9:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@142e9fe5d:MOVAPS xmmword ptr [RAX + -0x58],XMM7
  - FIELD@142e9fe78:MOVAPS xmmword ptr [RAX + -0x68],XMM8
  - FIELD@142e9fe4b:MOV qword ptr [RBP + -0x4],0x0
  - FIELD@142e9fe35:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@142e9fe19:LEA RBP,[RAX + -0x1d8]
  - FIELD@142e9fea6:MOV qword ptr [RAX + -0x20],RDI
  - FIELD@142e9fe9c:MOV qword ptr [RAX + -0x18],RBX
  - FIELD@142ea0054:MOVSS XMM0,dword ptr [RBP + -0x70]
  - NAME:TRANSFORM
  - FIELD@142e9fec5:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@142ea0152:MOVAPS xmmword ptr [RBP + -0x20],XMM5
  - FIELD@142ea011e:MOV dword ptr [RBP + -0x78],0x0

#4 SCORE=2351 REFS=2 CALLS=97 FIELDS=0
NAME: CalculateBonePositions
ADDR: 1409be260
  - CALLS:GetBoneLocation
  - CALLS:Rotation
  - NAME:BONE
  - NAME:POSITION
  - CALLS:FRotationMatrix

#5 SCORE=2021 REFS=138 CALLS=679 FIELDS=29
NAME: Z_Construct_UClass_APlayerController
ADDR: 1430e5f30
  - CALLS:Z_Construct_UFunction_APlayerController_ServerUpdateLevelVisibility
  - FIELD@1430e7c2f:MOV EAX,dword ptr [RBP + -0x44]
  - CALLS:Z_Construct_UFunction_APlayerController_GetViewportSize
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPrestreamTextures
  - FIELD@1430e8391:MOV R9D,dword ptr [RBP + -0x78]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientGotoState
  - CALLS:Z_Construct_UFunction_APlayerController_ClientEnableNetworkVoice
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPlayCameraShake
  - CALLS:GetPrivateStaticClassBody<APlayerController>
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSendNetExecCommandToServer
  - CALLS:Z_Construct_UFunction_APlayerController_ClientStopForceFeedback
  - CALLS:Z_Construct_UFunction_APlayerController_ServerAcknowledgePossession
  - CALLS:Z_Construct_UFunction_APlayerController_SetViewTargetWithBlend
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetViewTarget
  - CALLS:Z_Construct_UFunction_APlayerController_IsLookInputIgnored
  - CALLS:Z_Construct_UFunction_APlayerController_ServerMutePlayer
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetCinematicMode
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderFingerForObjects
  - CALLS:Z_Construct_UFunction_APlayerController_GetMousePosition
  - CALLS:Z_Construct_UFunction_APlayerController_SetIgnoreMoveInput
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPrepareMapChange
  - CALLS:Z_Construct_UFunction_APlayerController_Camera
  - CALLS:Z_Construct_UFunction_APlayerController_IsInputKeyDown
  - CALLS:Z_Construct_UFunction_APlayerController_ClientMessage
  - CALLS:Z_Construct_UFunction_APlayerController_ClientIgnoreMoveInput
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessNetExecCommand
  - FIELD@1430e894a:MOV R9D,dword ptr [RBP + -0x38]
  - NAME:PLAYER
  - FIELD@1430e7d41:MOV EAX,dword ptr [RBP + -0x64]
  - FIELD@1430e7ceb:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UFunction_APlayerController_ProjectWorldLocationToScreen
  - CALLS:Z_Construct_UFunction_APlayerController_AddPitchInput
  - CALLS:Z_Construct_UFunction_APlayerController_ClientStopCameraShake
  - CALLS:Z_Construct_UFunction_APlayerController_SendToConsole
  - FIELD@1430e7cb8:MOV EAX,dword ptr [RBP + -0x24]
  - CALLS:Z_Construct_UFunction_APlayerController_ServerChangeName
  - CALLS:Z_Construct_UFunction_APlayerController_ClientMutePlayer
  - CALLS:Z_Construct_UFunction_APlayerController_SwitchLevel
  - CALLS:Z_Construct_UFunction_APlayerController_ClientTeleportSucceeded
  - CALLS:Z_Construct_UFunction_APlayerController_ClientTravelInternal
  - CALLS:Z_Construct_UFunction_APlayerController_ClientTravel
  - CALLS:Z_Construct_UFunction_APlayerController_ServerNotifyLoadedWorld
  - CALLS:Z_Construct_UFunction_APlayerController_WasInputKeyJustReleased
  - CALLS:Z_Construct_UFunction_APlayerController_ServerUnmutePlayer
  - CALLS:Z_Construct_UFunction_APlayerController_ClientWasKicked
  - CALLS:Z_Construct_UFunction_APlayerController_PlayDynamicForceFeedback
  - CALLS:Z_Construct_UFunction_APlayerController_ClientReturnToMainMenu
  - CALLS:Z_Construct_UFunction_APlayerController_SetName
  - CALLS:Z_Construct_UFunction_APlayerController_ClientRetryClientRestart
  - CALLS:Z_Construct_UFunction_APlayerController_ServerProcessNetExecCommandUnreliable
  - FIELD@1430e5f86:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1430e5f8e:MOV qword ptr [R11 + -0x20],R14
  - CALLS:Z_Construct_UFunction_APlayerController_IsMoveInputIgnored
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessSimpleNetExecCommandUnreliableBP
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderCursor
  - CALLS:Z_Construct_UFunction_APlayerController_ClientStopCameraAnim
  - CALLS:Z_Construct_UClass_AController
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPlayForceFeedback
  - CALLS:Z_Construct_UFunction_APlayerController_ClientUnmutePlayer
  - CALLS:Z_Construct_UFunction_APlayerController_StartFire
  - CALLS:Z_Construct_UFunction_APlayerController_ClientNetGUIDActorDeletion
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderCursorByChannel
  - CALLS:Z_Construct_UFunction_APlayerController_ClientAddTextureStreamingLoc
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputVectorKeyState
  - FIELD@1430e7ed3:MOV R9D,dword ptr [RBP + -0x8]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessNetExecCommandUnreliable
  - CALLS:Z_Construct_UFunction_APlayerController_ServerProcessNetExecCommand
  - CALLS:Z_Construct_UEnum_APlayerController_EDynamicForceFeedbackAction
  - CALLS:GetPrivateStaticClassBody<ASpectatorPawn>
  - FIELD@1430e7edf:MOV EAX,dword ptr [RBP + -0x4]
  - FIELD@1430e83d0:LEA RCX,[RBP + -0x60]
  - CALLS:Z_Construct_UFunction_APlayerController_AddRollInput
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessSimpleNetExecCommandBP
  - FIELD@1430e8426:MOV EAX,dword ptr [RBP + -0x54]
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderCursorForObjects
  - CALLS:Z_Construct_UFunction_APlayerController_BPGetAimedUseActor
  - CALLS:Z_Construct_UFunction_APlayerController_GetHUD
  - CALLS:Z_Construct_UFunction_APlayerController_ServerViewSelf
  - CALLS:Z_Construct_UFunction_APlayerController_ConsoleKey
  - CALLS:Z_Construct_UFunction_APlayerController_ClientGameEnded
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputMouseDelta
  - FIELD@1430e839d:MOV EAX,dword ptr [RBP + -0x74]
  - FIELD@1430e7e89:LEA RCX,[RBP + -0x10]
  - CALLS:Z_Construct_UFunction_APlayerController_EnableCheats
  - CALLS:Z_Construct_UFunction_APlayerController_SetAudioListenerOverride
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputTouchState
  - FIELD@1430e7c23:MOV R9D,dword ptr [RBP + -0x48]
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputAnalogKeyState
  - CALLS:Z_Construct_UFunction_APlayerController_ClientRestart
  - CALLS:Z_Construct_UFunction_APlayerController_ClientRepObjRef
  - CALLS:Z_Construct_UFunction_APlayerController_NetSpawnActorAtLocation
  - CALLS:Z_Construct_UFunction_APlayerController_FOV
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPlaySound
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetCameraMode
  - FIELD@1430e5f8a:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_APlayerController_ClientTeamMessage
  - CALLS:Z_Construct_UFunction_APlayerController_LocalTravel
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessNetExecCommandBP
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPlayCameraAnim
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderFingerByChannel
  - CALLS:Z_Construct_UFunction_APlayerController_ActivateTouchInterface
  - CALLS:Z_Construct_UFunction_APlayerController_WasInputKeyJustPressed
  - CALLS:Z_Construct_UFunction_APlayerController_ClientReceiveLocalizedMessage
  - FIELD@1430e7cac:MOV R9D,dword ptr [RBP + -0x28]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientNotifyRespawned
  - CALLS:Z_Construct_UFunction_APlayerController_GetHitResultUnderFinger
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputAnalogStickState
  - CALLS:Z_Construct_UFunction_APlayerController_ServerCamera
  - FIELD@1430e8347:LEA RCX,[RBP + -0x80]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientUpdateLevelStreamingStatus
  - FIELD@1430e7c62:LEA RCX,[RBP + -0x30]
  - CALLS:Z_Construct_UFunction_APlayerController_ServerSetSpectatorLocation
  - CALLS:Z_Construct_UFunction_APlayerController_ClientProcessNetExecCommandUnreliableBP
  - CALLS:Z_Construct_UFunction_APlayerController_ServerUpdateCamera
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetCameraFade
  - CALLS:Z_Construct_UFunction_APlayerController_ClientPlaySoundAtLocation
  - FIELD@1430e7d35:MOV R9D,dword ptr [RBP + -0x68]
  - FIELD@1430e7bd9:LEA RCX,[RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSpawnCameraLensEffect
  - CALLS:Z_Construct_UFunction_APlayerController_NetConnectionHasActiveActor
  - CALLS:Z_Construct_UFunction_APlayerController_DeprojectMousePositionToWorld
  - CALLS:Z_Construct_UFunction_APlayerController_DeprojectScreenPositionToWorld
  - FIELD@1430e5f5b:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1430e5f34:LEA RBP,[R11 + -0x2d8]
  - CALLS:Z_Construct_UFunction_APlayerController_ClientCapBandwidth
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputMotionState
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetHUD
  - CALLS:Z_Construct_UFunction_APlayerController_SetVirtualJoystickVisibility
  - CALLS:Z_Construct_UFunction_APlayerController_ClientNotifyReconnected
  - CALLS:Z_Construct_UFunction_APlayerController_ClientIgnoreLookInput
  - FIELD@1430e841a:MOV R9D,dword ptr [RBP + -0x58]
  - CALLS:Z_Construct_UFunction_APlayerController_HandleRespawned
  - CALLS:Z_Construct_UFunction_APlayerController_AddYawInput
  - FIELD@1430e88fd:LEA RCX,[RBP + -0x40]
  - CALLS:Z_Construct_UFunction_APlayerController_CopyStringToClipboard
  - CALLS:Z_Construct_UFunction_APlayerController_GetInputKeyTimeDown
  - CALLS:Z_Construct_UFunction_APlayerController_ClientSetForceMipLevelsToBeResident
  - CALLS:Z_Construct_UFunction_APlayerController_SetIgnoreLookInput
  - CALLS:Z_Construct_UFunction_APlayerController_ToggleSpeaking

#6 SCORE=1902 REFS=2 CALLS=674 FIELDS=0
NAME: GetSnapToLocation
ADDR: 140a0cf20
  - CALLS:GetSnapPointLocation
  - NAME:LOCATION
  - CALLS:operator!=<AActor,APawn,FWeakObjectPtr,FIndexToObject>
  - CALLS:AllowSnapRotationForStructure
  - CALLS:BPOverrideSnappedFromTransform
  - CALLS:operator!=<AActor,AShooterCharacter,FWeakObjectPtr,FIndexToObject>
  - CALLS:BPOverrideSnappedToTransform

#7 SCORE=1747 REFS=55 CALLS=1097 FIELDS=29
NAME: Z_Construct_UClass_UCharacterMovementComponent
ADDR: 1431e7950
  - FIELD@1431e9477:MOV R9D,dword ptr [RBP + -0x48]
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_CalcVelocity
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveOldWithRotation
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetGroupsToAvoid
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bHasRequestedVelocity
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClientAckGoodMove
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_IsOnWalkableFloor
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bDisableSimulatedMovement
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bOnlyForwardsInputAccelerationWalking
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bWantsToProne
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseRotationAcceleration
  - FIELD@1431e942a:LEA RCX,[RBP + -0x50]
  - FIELD@1431e79a8:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetMovementBase
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bWantsToCrouch
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAllowImpactDeflection
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAccelerationFollowsRotation
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClientAdjustPosition
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetMaxJumpHeight
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerJumpOutOfWater
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetBase
  - FIELD@1431eb883:MOV EAX,dword ptr [RBP + -0x54]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bOnlyForwardsInputAcceleration
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCrouchMaintainsBaseLocation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bTouchForceScaledToMass
  - NAME:MOVEMENT
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bScalePushForceToVelocity
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetCharacterOwner
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bSlipOffLedges
  - FIELD@1431e9674:LEA RCX,[RBP + -0x10]
  - NAME:CHARACTER
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventAddingImpulse
  - FIELD@1431e7954:LEA RBP,[R11 + -0x6b8]
  - FIELD@1431eb909:MOV R9D,dword ptr [RBP + -0x38]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bIgnoreRotationAccelerationWhenSwimming
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bEnableScopedMovementUpdates
  - FIELD@1431e7999:MOV qword ptr [R11 + -0x20],R14
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAlwaysCheckFloor
  - CALLS:Z_Construct_UScriptStruct_UCharacterMovementComponent_FFindFloorResult
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bWasAvoidanceUpdated
  - FIELD@1431eb7f1:MOV EAX,dword ptr [RBP + -0x74]
  - CALLS:Z_Construct_UClass_UPawnMovementComponent
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventSlidingWhileFalling
  - FIELD@1431e7981:MOV qword ptr [R11 + -0x10],R12
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseCharacterInterpolationAndStops
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bRequireAccelerationForUseControllerDesiredRotation
  - FIELD@1431eb829:LEA RCX,[RBP + -0x60]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPushForceScaledToMass
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_IsWalkable
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveWithRotation
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_K2_GetWalkableFloorZ
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bEnablePhysicsInteraction
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseControllerDesiredRotation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bNotifyApex
  - FIELD@1431e935d:MOV EAX,dword ptr [RBP + -0x64]
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_K2_GetModifiedMaxAcceleration
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetAvoidanceGroup
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveDualWithRotation
  - FIELD@1431e79c2:MOV qword ptr [R11 + -0x18],R13
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAssumeSymmetricalRotation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCanWalkOffLedgesWhenCrouching
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventExitingWater
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCheatFlying
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetPerchRadiusThreshold
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMove
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bFastAttachedMove
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCanWalkOffLedges
  - FIELD@1431eb8bb:LEA RCX,[RBP + -0x40]
  - CALLS:Z_Construct_UScriptStruct_UCharacterMovementComponent_FStoredMoveData
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCanSlide
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_CapsuleTouched
  - FIELD@1431e959c:MOV R9D,dword ptr [RBP + -0x28]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceNextTickUpdate
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClearBase
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetAvoidanceEnabled
  - FIELD@1431e9482:MOV EAX,dword ptr [RBP + -0x44]
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ContextMoveReset
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveOld
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bRunPhysicsWithNoController
  - FIELD@1431eb877:MOV R9D,dword ptr [RBP + -0x58]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseBPAcknowledgeServerCorrection
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_RequestDirectMove
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetMovementMode
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventExitingWaterForceExtraOverlap
  - FIELD@1431e96cc:MOV EAX,dword ptr [RBP + -0x4]
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_DisableMovement
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseRootMotionForLocomotion
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bDeferUpdateMoveComponent
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_IsWalking
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetWalkableFloorAngle
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventEnteringWater
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bRequestedMoveUseAcceleration
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveOnlyRotation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceMaxAccel
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bReduceBackwardsMovement
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClientDrawDebugSphere
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseFlatBaseForFloorChecks
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bShrinkProxyCapsule
  - FIELD@1431e96c1:MOV R9D,dword ptr [RBP + -0x8]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bNetworkUpdateReceived
  - FIELD@1431eb7e5:MOV R9D,dword ptr [RBP + -0x78]
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveDualOnlyRotation
  - CALLS:Z_Construct_UScriptStruct_UAnimationAsset_FRootMotionMovementParams
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClientAdjustRootMotionPosition
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ServerMoveDual
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_AddImpulse
  - CALLS:Z_Construct_UScriptStruct_UCharacterMovementComponent_FCharacterMovementComponentPreClothTickFunction
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceDontAllowDesiredRotationWhenFalling
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_K2_GetWalkableFloorAngle
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetMaxAcceleration
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_AddForce
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bOrientRotationToMovement
  - FIELD@1431e95a7:MOV EAX,dword ptr [RBP + -0x24]
  - CALLS:GetPrivateStaticClassBody<UCharacterMovementComponent>
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bImpartBaseVelocityY
  - FIELD@1431e9305:LEA RCX,[RBP + -0x70]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bImpartBaseVelocityX
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAlwaysCheckForInvallidFloor
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetCurrentAcceleration
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_NewFallVelocity
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPerformingJumpOff
  - CALLS:Z_Construct_UEnum_UEngineTypes_EMovementMode
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bRequestedMoveWithMaxSpeed
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bZeroPitchWhenNoAcceleration
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetGroupsToIgnore
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bLastHasRequestedVelocity
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetImpartedMovementBaseVelocity
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_ClientVeryShortAdjustPosition
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bAllowSimulatedTickDistanceSkip
  - FIELD@1431e9352:MOV R9D,dword ptr [RBP + -0x68]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bCheckFallingAITempIgnoreDinoRiderMesh
  - FIELD@1431e954f:LEA RCX,[RBP + -0x30]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bUseAsyncWalking
  - FIELD@1431eb797:LEA RCX,[RBP + -0x80]
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bImpartBaseVelocityZ
  - CALLS:Z_Construct_UEnum_UCharacterMovementComponent_ENetMoveType
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceNextFloorCheck
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bEnableSwimmingOutsideOfWater
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventZeroPitchAndRollWhileFalling
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetValidPerchRadius
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_SetWalkableFloorZ
  - CALLS:Z_Construct_UFunction_UCharacterMovementComponent_GetAnalogInputModifier
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceBraking_DEPRECATED
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bMovementInProgress
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForceModifyDesiredRotation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bJustTeleported
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPreventWaterSurfaceHopping
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bPendingLaunchNoLowerVelocity
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bMaintainHorizontalGroundVelocity
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bIgnoreBaseRotation
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bImpartBaseAngularVelocity
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bNetworkMovementModeChanged
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bServerCorrectForMovementModeChanges
  - CALLS:FDetermineBitMask_UCharacterMovementComponent_bForcePreventExitingWater

#8 SCORE=1457 REFS=4 CALLS=75 FIELDS=158
NAME: EvaluateBoneTransforms
ADDR: 142d27620
  - FIELD@142d2769f:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@142d2764f:MOV qword ptr [RAX + -0x28],R13
  - FIELD@142d27717:LEA RCX,[RBP + -0x20]
  - NAME:BONE
  - FIELD@142d276b2:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@142d277e8:MOV qword ptr [RBP + -0x68],RDI
  - FIELD@142d2764b:MOV qword ptr [RAX + -0x20],R12
  - CALLS:GetLocalSpaceTransform
  - FIELD@142d2766e:MOVAPS xmmword ptr [RAX + -0x78],XMM9
  - FIELD@142d277e1:MOV R8D,dword ptr [RBP + -0x18]
  - FIELD@142d2766a:MOV qword ptr [RAX + -0x38],R15
  - FIELD@142d2779b:MOV R8D,dword ptr [RBP + -0x18]
  - FIELD@142d27693:LEA R8,[RBP + -0x10]
  - FIELD@142d27647:MOV qword ptr [RAX + -0x18],RDI
  - FIELD@142d27788:LEA RCX,[RBP + -0x20]
  - FIELD@142d2767b:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@142d2762d:LEA RBP,[RAX + -0x128]
  - FIELD@142d276f5:MOVSS dword ptr [RBP + -0x78],XMM12
  - FIELD@142d27673:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@142d276df:MOVSS dword ptr [RBP + -0x80],XMM10
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d2781a:MOV R8D,dword ptr [RBP + -0x18]
  - FIELD@142d27653:MOVAPS xmmword ptr [RBP + -0x10],XMM0
  - FIELD@142d27697:MOVAPS xmmword ptr [RAX + -0xa8],XMM12
  - FIELD@142d276ce:LEA RCX,[RBP + -0x20]
  - NAME:TRANSFORM
  - FIELD@142d2765f:MOV qword ptr [RAX + -0x30],R14
  - FIELD@142d276a7:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - CALLS:ConvertBoneSpaceTransformToCS
  - FIELD@142d276ef:MOVSS dword ptr [RBP + -0x7c],XMM11

#9 SCORE=1333 REFS=82 CALLS=390 FIELDS=29
NAME: Z_Construct_UClass_USceneComponent
ADDR: 143024930
  - FIELD@143026b0b:MOV R9D,dword ptr [RBP + -0x58]
  - FIELD@143026bbc:MOV R9D,dword ptr [RBP + -0x38]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetWorldTransform
  - FIELD@143024957:MOV qword ptr [R11 + -0x28],R15
  - FIELD@143024986:MOV qword ptr [R11 + -0x20],R14
  - FIELD@143026abe:LEA RCX,[RBP + -0x60]
  - FIELD@143026a03:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetWorldRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_GetChildComponent
  - CALLS:Z_Construct_UFunction_USceneComponent_AddWorldOffset
  - CALLS:Z_Construct_UFunction_USceneComponent_AddLocalTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_GetAllSocketNames
  - CALLS:Z_Construct_UFunction_USceneComponent_SetWorldLocationAndRotation
  - CALLS:FDetermineBitMask_USceneComponent_bAbsoluteLocation
  - FIELD@143026877:MOV R9D,dword ptr [RBP + -0x78]
  - CALLS:Z_Construct_UClass_UActorComponent
  - CALLS:Z_Construct_UFunction_USceneComponent_ResetRelativeTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_SetWorldScale3D
  - CALLS:Z_Construct_UFunction_USceneComponent_GetRightVector
  - STRING_REF:ComponentToWorld
  - CALLS:Z_Construct_UFunction_USceneComponent_ToggleVisibility
  - FIELD@143026a66:MOV EAX,dword ptr [RBP + -0x64]
  - FIELD@143026b17:MOV EAX,dword ptr [RBP + -0x54]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetAbsolute
  - FIELD@143026759:MOV R9D,dword ptr [RBP + -0x48]
  - CALLS:Z_Construct_UFunction_USceneComponent_AddWorldRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_AddLocalOffset
  - CALLS:Z_Construct_UFunction_USceneComponent_GetParentComponents
  - CALLS:Z_Construct_UFunction_USceneComponent_BP_GetCollisionEnabled
  - CALLS:Z_Construct_UFunction_USceneComponent_PhysicsVolumeChanged__DelegateSignature
  - FIELD@143026948:LEA RCX,[RBP + -0x10]
  - CALLS:Z_Construct_UFunction_USceneComponent_AddRelativeLocation
  - CALLS:Z_Construct_UFunction_USceneComponent_GetWorldLocation
  - FIELD@14302670c:LEA RCX,[RBP + -0x50]
  - FIELD@1430265ec:LEA RCX,[RBP + -0x30]
  - FIELD@143024934:LEA RBP,[R11 + -0x318]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetRelativeTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_OnRep_Transform
  - FIELD@143026995:MOV R9D,dword ptr [RBP + -0x8]
  - CALLS:Z_Construct_UFunction_USceneComponent_GetAttachParent
  - STRING_REF:RelativeLocation
  - CALLS:Z_Construct_UFunction_USceneComponent_AddWorldTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_GetSocketQuaternion
  - CALLS:Z_Construct_UScriptStruct_UObject_FTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_GetNumChildrenComponents
  - CALLS:Z_Construct_UFunction_USceneComponent_AddRelativeRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_GetRelativeTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_GetComponentVelocity
  - CALLS:Z_Construct_UFunction_USceneComponent_GetSocketTransform
  - CALLS:Z_Construct_UFunction_USceneComponent_SetRelativeScale3D
  - CALLS:GetPrivateStaticClassBody<USceneComponent>
  - CALLS:Z_Construct_UFunction_USceneComponent_K2_GetComponentScale
  - FIELD@143026765:MOV EAX,dword ptr [RBP + -0x44]
  - CALLS:Z_Construct_UFunction_USceneComponent_GetSocketLocation
  - FIELD@14302497e:MOV qword ptr [R11 + -0x10],R12
  - FIELD@143026b6f:LEA RCX,[RBP + -0x40]
  - FIELD@143026643:MOV R9D,dword ptr [RBP + -0x28]
  - CALLS:Z_Construct_UFunction_USceneComponent_GetChildrenComponents
  - CALLS:Z_Construct_UFunction_USceneComponent_K2_AttachTo
  - CALLS:Z_Construct_UFunction_USceneComponent_OnRep_Visibility
  - FIELD@14302664f:MOV EAX,dword ptr [RBP + -0x24]
  - CALLS:Z_Construct_UFunction_USceneComponent_IsSimulatingPhysics
  - CALLS:Z_Construct_UFunction_USceneComponent_K2_GetComponentToWorld
  - CALLS:Z_Construct_UFunction_USceneComponent_SetRelativeLocation
  - CALLS:Z_Construct_UFunction_USceneComponent_SetRelativeRotation
  - FIELD@143024982:MOV qword ptr [R11 + -0x18],R13
  - FIELD@143026a5a:MOV R9D,dword ptr [RBP + -0x68]
  - FIELD@1430269a1:MOV EAX,dword ptr [RBP + -0x4]
  - CALLS:FDetermineBitMask_USceneComponent_bRequiresCustomLocation
  - CALLS:Z_Construct_UFunction_USceneComponent_GetPhysicsVolume
  - CALLS:Z_Construct_UFunction_USceneComponent_GetSocketRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_GetForwardVector
  - CALLS:Z_Construct_UFunction_USceneComponent_K2_GetComponentLocation
  - CALLS:Z_Construct_UEnum_USceneComponent_ERelativeTransformSpace
  - CALLS:Z_Construct_UFunction_USceneComponent_SnapTo
  - SCENE_COMPONENT
  - FIELD@143026883:MOV EAX,dword ptr [RBP + -0x74]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetHiddenInGame
  - CALLS:Z_Construct_UFunction_USceneComponent_IsVisible
  - CALLS:Z_Construct_UFunction_USceneComponent_SetRelativeLocationAndRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_DetachFromParent
  - CALLS:Z_Construct_UFunction_USceneComponent_SetVisibility
  - CALLS:Z_Construct_UFunction_USceneComponent_GetUpVector
  - CALLS:Z_Construct_UFunction_USceneComponent_IsAnySimulatingPhysics
  - CALLS:Z_Construct_UFunction_USceneComponent_K2_GetComponentRotation
  - CALLS:Z_Construct_UFunction_USceneComponent_DoesSocketExist
  - CALLS:Z_Construct_UFunction_USceneComponent_SetMobility
  - CALLS:Z_Construct_UFunction_USceneComponent_StopSound
  - CALLS:Z_Construct_UEnum_USceneComponent_EDetailMode
  - CALLS:Z_Construct_UFunction_USceneComponent_AddLocalRotation
  - FIELD@14302682a:LEA RCX,[RBP + -0x80]
  - CALLS:Z_Construct_UFunction_USceneComponent_SetWorldLocation
  - CALLS:FDetermineBitMask_USceneComponent_bAbsoluteRotation

#10 SCORE=1302 REFS=9 CALLS=380 FIELDS=189
NAME: ServerReplicateActors
ADDR: 142a87890
  - FIELD@142a88130:MOVSS XMM1,dword ptr [RBP + -0x64]
  - FIELD@142a87fb7:MOV RDI,qword ptr [RBP + -0x78]
  - FIELD@142a88124:XOR ECX,dword ptr [RBP + -0x64]
  - FIELD@142a87894:LEA RBP,[RSP + -0x728]
  - FIELD@142a880cd:MOV RSI,qword ptr [RBP + -0x30]
  - FIELD@142a87f5c:MOV RDI,qword ptr [RBP + -0x78]
  - FIELD@142a8812d:XOR dword ptr [RBP + -0x64],ECX
  - FIELD@142a88172:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142a88111:MOV dword ptr [RBP + -0x64],0x3f800000
  - CALLS:GetPrivateStaticClassBody<APlayerController>
  - NAME:ACTOR
  - FIELD@142a87af9:MOV RCX,qword ptr [RSI + RAX*0x1 + -0x8]
  - FIELD@142a87e77:MOV RCX,qword ptr [RBP + -0x78]
  - FIELD@142a87b37:MOV EAX,dword ptr [RBP + -0x10]
  - CALLS:ActorChannelsFindRef
  - FIELD@142a881d1:LEA RAX,[RBP + -0x78]
  - FIELD@142a881e3:LEA RAX,[RBP + -0x78]
  - CALLS:SetChannelActor
  - FIELD@142a880b7:MOV RDI,qword ptr [RBP + -0x78]
  - FIELD@142a878f4:MOV dword ptr [RBP + -0x10],R13D
  - FIELD@142a87f2a:MOV RCX,qword ptr [RBP + -0x78]
  - FIELD@142a880d6:MOV R14,qword ptr [RBP + -0x18]
  - FIELD@142a87b27:MOV dword ptr [RBP + -0x10],R13D
  - CALLS:ReplicateActor
  - FIELD@142a87bbb:MOV qword ptr [RBP + -0x18],RAX
  - CALLS:Emplace<AActor_*___ptr64_const_&___ptr64>
  - CALLS:FActorPriority
  - CALLS:SortInternal<FActorPriority_*___ptr64,TDereferenceWrapper<FActorPriority_*___ptr64,`UNetDriver::ServerReplicateActors'::__l389::FCompareFActorPriority>_>
  - FIELD@142a87e29:MOV qword ptr [RBP + -0x78],RCX
  - FIELD@142a88184:MOV RDI,qword ptr [RBP + -0x78]
  - FIELD@142a881c1:LEA RAX,[RBP + -0x78]
  - FIELD@142a88007:MOV RDI,qword ptr [RBP + -0x78]
  - FIELD@142a87dd8:MOV qword ptr [RBP + -0x30],RSI

#11 SCORE=1211 REFS=5 CALLS=56 FIELDS=75
NAME: UpdateBasedMovement
ADDR: 1428c0130
  - FIELD@1428c03f1:MOVAPS XMM2,xmmword ptr [RBP + -0x60]
  - FIELD@1428c05e3:MOVSS dword ptr [RBP + -0x50],XMM0
  - FIELD@1428c0633:MOVSS dword ptr [RBP + -0x4c],XMM6
  - FIELD@1428c0681:MOVSS dword ptr [RBP + -0x28],XMM0
  - FIELD@1428c03df:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@1428c0617:MOVSS dword ptr [RBP + -0x20],XMM0
  - CALLS:SetWorldLocationAndRotation
  - FIELD@1428c0549:MOV dword ptr [RBP + -0x34],R14D
  - FIELD@1428c0545:MOV dword ptr [RBP + -0x44],R14D
  - FIELD@1428c0559:MOV dword ptr [RBP + -0x14],0x3f800000
  - FIELD@1428c03c7:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@1428c0657:MOVSS dword ptr [RBP + -0x1c],XMM0
  - FIELD@1428c0257:MOVAPS xmmword ptr [RBP + -0x60],XMM0
  - FIELD@1428c0646:MOVSS dword ptr [RBP + -0x3c],XMM0
  - FIELD@1428c054d:MOV dword ptr [RBP + -0x24],R14D
  - FIELD@1428c0498:MOVAPS XMM13,xmmword ptr [RBP + -0x60]
  - FIELD@1428c0638:MOVSS dword ptr [RBP + -0x2c],XMM1
  - CALLS:SetActorLocation
  - FIELD@1428c03da:MOVSS dword ptr [RBP + -0x5c],XMM1
  - NAME:MOVEMENT
  - FIELD@1428c0605:MOVSS dword ptr [RBP + -0x30],XMM0
  - FIELD@1428c0460:MOVAPS xmmword ptr [RBP + -0x60],XMM13
  - FIELD@1428c0133:LEA RBP,[RSP + -0x1b8]
  - FIELD@1428c0661:MOVSS dword ptr [RBP + -0x48],XMM7
  - CALLS:ApplyDeltaToAllPhysicsTransforms
  - FIELD@1428c068e:MOVSS dword ptr [RBP + -0x18],XMM0
  - FIELD@1428c05fd:MOVSS dword ptr [RBP + -0x40],XMM1
  - FIELD@1428c03ec:MOVSS dword ptr [RBP + -0x54],XMM0
  - CALLS:GetMovementBaseTransform
  - FIELD@1428c0676:MOVSS dword ptr [RBP + -0x38],XMM11

#12 SCORE=1201 REFS=46 CALLS=257 FIELDS=120
NAME: Z_Construct_UClass_APawn
ADDR: 14314ac30
  - CALLS:Z_Construct_UFunction_APawn_GetMovementBaseActor
  - FIELD@14314ac86:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_APawn_MovementTetherEvent__DelegateSignature
  - CALLS:Z_Construct_UFunction_APawn_AddMovementInput
  - FIELD@14314ac34:LEA RBP,[R11 + -0x128]
  - FIELD@14314ac82:MOV qword ptr [R11 + -0x18],R13
  - FIELD@14314b2b8:MOV word ptr [RBP + -0x40],0x100
  - FIELD@14314b2c2:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - FIELD@14314b416:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - CALLS:FDetermineBitMask_APawn_bPreventMovementStoppingOnPossess
  - CALLS:Z_Construct_UFunction_APawn_PawnMakeNoise
  - CALLS:Z_Construct_UFunction_APawn_GetController
  - CALLS:Z_Construct_UFunction_APawn_ReceivePossessed
  - FIELD@14314b2ce:MOV qword ptr [RBP + -0x38],R14
  - CALLS:Z_Construct_UFunction_APawn_IsMovementTethered
  - FIELD@14314b1d3:MOV byte ptr [RBP + -0x3e],DIL
  - FIELD@14314b20b:LEA RCX,[RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APawn_K2_GetMovementInputVector
  - CALLS:Z_Construct_UFunction_APawn_SetCanAffectNavigationGeneration
  - FIELD@14314ac7e:MOV qword ptr [R11 + -0x10],R12
  - FIELD@14314b1be:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - CALLS:Z_Construct_UFunction_APawn_GetTetherObject
  - CALLS:GetPrivateStaticClassBody<APawn>
  - FIELD@14314b2f7:MOV RCX,qword ptr [RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APawn_GetNavAgentLocation
  - CALLS:Z_Construct_UFunction_APawn_SetMovementTether
  - FIELD@14314b2be:MOV byte ptr [RBP + -0x3e],0x1
  - CALLS:Z_Construct_UFunction_APawn_IsMoveInputIgnored
  - CALLS:Z_Construct_UFunction_APawn_InterceptInputEvent
  - FIELD@14314b47c:MOV qword ptr [RBP + -0x50],RBX
  - CALLS:FDetermineBitMask_APawn_bUseControllerRotationPitch
  - CALLS:Z_Construct_UFunction_APawn_GetLastMovementInputVector
  - FIELD@14314b412:MOV byte ptr [RBP + -0x3e],0x1
  - CALLS:Z_Construct_UFunction_APawn_AddControllerRollInput
  - CALLS:Z_Construct_UFunction_APawn_GetControlRotation
  - CALLS:Z_Construct_UFunction_APawn_IsLocallyControlled
  - CALLS:FDetermineBitMask_APawn_bUseControllerRotationYaw
  - CALLS:Z_Construct_UFunction_APawn_IsFalling
  - CALLS:Z_Construct_UFunction_APawn_ConsumeMovementInputVector
  - FIELD@14314b32c:MOV byte ptr [RBP + -0x3e],R14B
  - CALLS:Z_Construct_UFunction_APawn_IsWithinTether
  - CALLS:Z_Construct_UFunction_APawn_IsControlled
  - FIELD@14314b1d7:MOV qword ptr [RBP + -0x38],R14
  - NAME:PAWN
  - FIELD@14314b40c:MOV word ptr [RBP + -0x40],0x100
  - FIELD@14314b377:LEA RCX,[RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APawn_GetTetheredVelocity
  - FIELD@14314b422:MOV qword ptr [RBP + -0x38],R14
  - CALLS:Z_Construct_UFunction_APawn_ClearMovementTether
  - CALLS:Z_Construct_UFunction_APawn_IsTargetWithinTether
  - FIELD@14314b1cd:MOV word ptr [RBP + -0x40],0x100
  - CALLS:Z_Construct_UFunction_APawn_IsCrouched
  - CALLS:Z_Construct_UFunction_APawn_GetBaseAimRotation
  - CALLS:Z_Construct_UFunction_APawn_GetPendingMovementInputVector
  - CALLS:Z_Construct_UFunction_APawn_LaunchPawn
  - CALLS:Z_Construct_UFunction_APawn_AddControllerYawInput
  - CALLS:Z_Construct_UFunction_APawn_GetMovementComponent
  - CALLS:FDetermineBitMask_APawn_bUseControllerRotationRoll
  - CALLS:Z_Construct_UFunction_APawn_AddControllerPitchInput
  - CALLS:Z_Construct_UFunction_APawn_GetTetheredDestination
  - FIELD@14314ac57:MOV qword ptr [R11 + -0x20],R14
  - FIELD@14314b44b:MOV RCX,qword ptr [RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APawn_IsWalking
  - CALLS:Z_Construct_UFunction_APawn_ReceiveUnpossessed
  - FIELD@14314b1b1:LEA RDX,[RBP + -0x50]
  - FIELD@14314b328:MOV qword ptr [RBP + -0x50],RBX
  - CALLS:GetPrivateStaticClassBody<APlayerState>

#13 SCORE=1201 REFS=4 CALLS=51 FIELDS=69
NAME: EvaluateBoneTransforms
ADDR: 142d48fd0
  - FIELD@142d491c2:LEA RDX,[RBP + -0x20]
  - FIELD@142d496cf:SUBSS XMM3,dword ptr [RBP + -0x60]
  - FIELD@142d4971c:MOVSS dword ptr [RBP + -0x78],XMM4
  - NAME:BONE
  - FIELD@142d496e8:SUBSS XMM4,dword ptr [RBP + -0x50]
  - FIELD@142d49227:MOVAPS xmmword ptr [RBP + -0x40],XMM0
  - CALLS:GetLocalSpaceTransform
  - FIELD@142d491be:MOV R8D,dword ptr [RBP + -0x68]
  - FIELD@142d4909e:CMP ECX,-0x1
  - FIELD@142d49218:MOV RBX,qword ptr [RBP + -0x70]
  - FIELD@142d49420:MOVSS XMM11,dword ptr [RBP + -0x80]
  - FIELD@142d496c1:MOVSS XMM5,dword ptr [RBP + -0x40]
  - FIELD@142d496df:SUBSS XMM5,dword ptr [RBP + -0x10]
  - FIELD@142d496f2:MOVSS dword ptr [RBP + -0x28],XMM1
  - FIELD@142d4957c:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@142d4900e:MOV qword ptr [RBP + -0x70],RDX
  - FIELD@142d492b8:MOVAPS xmmword ptr [RBP + -0x60],XMM10
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d48fdd:LEA RBP,[RSP + -0x1e8]
  - FIELD@142d49709:MOVSS dword ptr [RBP + -0x70],XMM6
  - FIELD@142d496b7:MOVSS XMM3,dword ptr [RBP + -0x3c]
  - FIELD@142d490fd:CMP EAX,-0x1
  - FIELD@142d49275:MOVAPS XMM8,xmmword ptr [RBP + -0x10]
  - FIELD@142d496ed:MOVSS dword ptr [RBP + -0x2c],XMM0
  - FIELD@142d492bd:MOVAPS xmmword ptr [RBP + -0x50],XMM11
  - NAME:TRANSFORM
  - FIELD@142d4934e:MOV dword ptr [RBP + -0x80],EAX
  - CALLS:FindBoneIndex
  - FIELD@142d496a9:MOVSS XMM4,dword ptr [RBP + -0x38]
  - FIELD@142d49100:MOV dword ptr [RBP + -0x68],EAX
  - CALLS:ConvertBoneSpaceTransformToCS

#14 SCORE=1134 REFS=4 CALLS=65 FIELDS=82
NAME: EvaluateBoneTransforms
ADDR: 142d47180
  - FIELD@142d472ce:MOV EDX,dword ptr [RBP + -0x78]
  - FIELD@142d47806:LEA RCX,[RBP + -0x60]
  - FIELD@142d4780a:MOVAPS xmmword ptr [RBP + -0x60],XMM0
  - FIELD@142d47195:LEA RBP,[RSP + -0x1e8]
  - NAME:BONE
  - FIELD@142d47260:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142d479db:MOVSS dword ptr [RBP + -0x1c],XMM8
  - FIELD@142d479e1:MOVSS dword ptr [RBP + -0x18],XMM9
  - FIELD@142d47213:LEA RCX,[RBP + -0x80]
  - FIELD@142d47b19:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142d479d3:MOV dword ptr [RBP + -0x14],EDI
  - FIELD@142d47327:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142d47bef:MOV ECX,dword ptr [RBP + -0x78]
  - FIELD@142d4783a:MOV dword ptr [RBP + -0x58],EDI
  - FIELD@142d479d6:MOVSS dword ptr [RBP + -0x20],XMM7
  - FIELD@142d479e7:MOVAPS XMM2,xmmword ptr [RBP + -0x20]
  - FIELD@142d47529:MOVSD qword ptr [RCX + R15*0x1 + -0xc],XMM0
  - FIELD@142d47530:MOV dword ptr [RCX + R15*0x1 + -0x4],EAX
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d47446:MOV ECX,dword ptr [RBP + -0x78]
  - FIELD@142d47c38:MOV qword ptr [RBP + -0x50],RDI
  - FIELD@142d474a1:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142d47535:MOV ECX,dword ptr [RBP + -0x78]
  - FIELD@142d47836:MOV qword ptr [RBP + -0x60],RDI
  - FIELD@142d4721f:MOV EDX,dword ptr [RBP + -0x78]
  - CALLS:GetTransformMatrix
  - NAME:TRANSFORM
  - FIELD@142d471f3:LEA RCX,[RBP + -0x80]
  - FIELD@142d47ae5:MOV ECX,dword ptr [RBP + -0x78]

#15 SCORE=1113 REFS=3 CALLS=142 FIELDS=5
NAME: SpawnMissionWithCallback
ADDR: 140319ef0
  - FIELD@140319f81:MOV qword ptr [RSP + 0xd0],-0x1
  - FIELD@14031a26d:MOV qword ptr [RSP + 0xc8],-0x1
  - CALLS:SpawnActorDeferred<AMissionType>
  - STRING_REF:Pawn
  - CALLS:CanStartMission
  - CALLS:IsPlayerEligibleForMission
  - NAME:PAWN
  - FIELD@14031a72c:MOV qword ptr [RSP + 0xd8],-0x1
  - STRING_REF:Character
  - FIELD@14031a0f5:MOV qword ptr [RSP + 0xc0],-0x1
  - FIELD@14031b346:MOV qword ptr [RSP + 0xb8],-0x1
  - CALLS:AddPlayerToMission

#16 SCORE=1088 REFS=10 CALLS=38 FIELDS=160
NAME: BPValidateStoredClientRotationInput_Implementation
ADDR: 1428b94a0
  - FIELD@1428b95f0:LEA RCX,[RBP + -0x59]
  - FIELD@1428b960f:MOV dword ptr [RBP + -0x51],EAX
  - FIELD@1428b95f4:MOVAPS xmmword ptr [RBP + -0x59],XMM0
  - FIELD@1428b95ec:LEA RDX,[RBP + -0x69]
  - NAME:ROTATION
  - FIELD@1428b964e:LEA RDX,[RBP + -0x59]
  - FIELD@1428b95fd:MOV EAX,dword ptr [RBP + -0x61]
  - FIELD@1428b965f:MOV EAX,dword ptr [RBP + -0x51]
  - FIELD@1428b9600:MOVSD XMM0,qword ptr [RBP + -0x69]
  - FIELD@1428b94c0:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@1428b9656:MOVAPS xmmword ptr [RBP + -0x69],XMM0
  - FIELD@1428b94c4:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@1428b94cd:MOVAPS xmmword ptr [RAX + -0x48],XMM9
  - FIELD@1428b966c:MOVSS XMM8,dword ptr [RBP + -0x65]
  - FIELD@1428b94d2:MOVAPS xmmword ptr [RAX + -0x58],XMM10
  - FIELD@1428b9667:MOVSD qword ptr [RBP + -0x69],XMM0
  - FIELD@1428b9662:MOVSD XMM0,qword ptr [RBP + -0x59]
  - FIELD@1428b94c8:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@1428b960a:MOVSS XMM6,dword ptr [RBP + -0x55]
  - FIELD@1428b9672:MOV dword ptr [RBP + -0x61],EAX
  - FIELD@1428b94b5:LEA RBP,[RAX + -0x5f]
  - FIELD@1428b9652:LEA RCX,[RBP + -0x69]
  - FIELD@1428b9605:MOVSD qword ptr [RBP + -0x59],XMM0
  - FIELD@1428b969a:LEA RDX,[RBP + -0x59]
  - FIELD@1428b94dc:MOVAPS xmmword ptr [RAX + -0x78],XMM12
  - FIELD@1428b94d7:MOVAPS xmmword ptr [RAX + -0x68],XMM11

#17 SCORE=1068 REFS=2 CALLS=26 FIELDS=181
NAME: FUN_143c1ffc0
ADDR: 143c1ffc0
  - FIELD@143c20041:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c2008d:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c2000a:MOV qword ptr [RBP + -0x10],0x4
  - STRING_REF:Transform
  - FIELD@143c2009f:MOV dword ptr [RBP + -0x20],0x50
  - FIELD@143c20029:MOV qword ptr [RBP + -0x30],RDI
  - STRING_REF:Velocity
  - FIELD@143c2009b:MOV qword ptr [RBP + -0x30],RSI
  - FIELD@143c2005d:LEA RDX,[RBP + -0x30]
  - FIELD@143c20094:LEA RDX,[RBP + -0x30]
  - FIELD@143c2002d:MOV qword ptr [RBP + -0x28],R15
  - FIELD@143c2003d:MOV dword ptr [RBP + -0x14],R15D
  - FIELD@143c20022:LEA RDX,[RBP + -0x30]
  - FIELD@143c20064:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1fffa:MOV qword ptr [RBP + -0x30],RSI
  - FIELD@143c20078:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c1ffef:LEA RDX,[RBP + -0x30]
  - FIELD@143c20002:MOV qword ptr [RBP + -0x28],R14
  - FIELD@143c20006:MOV qword ptr [RBP + -0x18],R15
  - FIELD@143c20074:MOV dword ptr [RBP + -0x14],R15D
  - FIELD@143c2006c:MOV qword ptr [RBP + -0x1c],0x190
  - STRING_REF:Position
  - FIELD@143c20068:MOV dword ptr [RBP + -0x20],R15D
  - FIELD@143c1fffe:MOV qword ptr [RBP + -0x20],R15
  - FIELD@143c200a6:MOV dword ptr [RBP + -0x1c],0x18
  - FIELD@143c20031:MOV dword ptr [RBP + -0x20],R15D
  - FIELD@143c20035:MOV qword ptr [RBP + -0x1c],0x190
  - FIELD@143c20056:MOV qword ptr [RBP + -0x28],RAX

#18 SCORE=1010 REFS=201 CALLS=175 FIELDS=196
NAME: DisplayDebug
ADDR: 142866a90
  - FIELD@142866c10:MOV dword ptr [RBP + -0x24],0x3ef5c28f
  - FIELD@142866ab7:MOV qword ptr [RAX + -0x20],RDI
  - FIELD@142866c17:MOV RAX,qword ptr [RBP + -0x28]
  - FIELD@142866c1b:MOV dword ptr [RBP + -0x50],0x3ef5c28f
  - FIELD@142866aa5:LEA RBP,[RAX + -0xc8]
  - FIELD@142866b31:LEA RCX,[RBP + -0x48]
  - FIELD@142866bf7:OR dword ptr [RBP + -0x54],0x1
  - FIELD@142866abf:MOV qword ptr [RAX + -0x30],R13
  - FIELD@142866acb:MOVAPS xmmword ptr [RAX + -0x78],XMM8
  - FIELD@142866bf3:OR dword ptr [RBP + -0x7c],0x1
  - CALLS:GetOverlappingActors
  - FIELD@142866c22:MOV qword ptr [RBP + -0x68],RAX
  - FIELD@142866abb:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142866b65:CMP dword ptr [RBP + -0x40],ESI
  - FIELD@142866c06:MOVUPS xmmword ptr [RBP + -0x78],XMM0
  - FIELD@142866b1d:CMOVNZ R8,qword ptr [RBP + -0x48]
  - FIELD@142866ac3:MOV qword ptr [RAX + -0x38],R14
  - FIELD@142866ac7:MOV qword ptr [RAX + -0x40],R15
  - FIELD@142866c26:MOV dword ptr [RBP + -0x4c],0x3f0a3d71
  - FIELD@142866ab3:MOV qword ptr [RAX + -0x18],RSI
  - FIELD@142866b10:CMP dword ptr [RBP + -0x40],ESI
  - FIELD@142866bef:AND dword ptr [RBP + -0x80],0xfffffffc
  - FIELD@142866aee:LEA RDX,[RBP + -0x48]
  - FIELD@142866bfb:MOV dword ptr [RBP + -0x28],0x3ed70a3d
  - CALLS:operator_enum_EMovementMode
  - FIELD@142866ad0:MOVAPS xmmword ptr [RAX + -0x88],XMM9
  - FIELD@142866b76:CMOVNZ RDI,qword ptr [RBP + -0x48]
  - STRING_REF:RootComponent

#19 SCORE=995 REFS=2 CALLS=218 FIELDS=0
NAME: UpdateRotation
ADDR: 1410a05e0
  - NAME:ROTATION
  - CALLS:GetLadderClimbRotation
  - CALLS:Rotation
  - CALLS:EnableTurnToFaceRotation
  - CALLS:Cast<UShooterCharacterMovement>
  - CALLS:SetActorRotation
  - CALLS:GetPassengerAttachedRotation
  - CALLS:BPLimitPlayerRotation

#20 SCORE=993 REFS=2 CALLS=48 FIELDS=4
NAME: GetFlowVectorAtLocation
ADDR: 141674ff0
  - FIELD@141675723:CMP dword ptr [RSP + 0x118],-0x1
  - FIELD@1416750e8:CMP dword ptr [RSP + 0x150],-0x1
  - NAME:LOCATION
  - FIELD@141676329:CMP dword ptr [RSP + 0x114],-0x1
  - FIELD@141675d26:CMP dword ptr [RSP + 0x104],-0x1
  - CALLS:GetGridIndexForLocation
  - CALLS:GetLocationForGridIndex

#21 SCORE=977 REFS=7 CALLS=36 FIELDS=79
NAME: GetAvoidanceVelocity_Internal
ADDR: 142c7e520
  - FIELD@142c7e7ba:MOVUPS XMM1,xmmword ptr [RBP + -0x38]
  - FIELD@142c7e729:MOV R10,qword ptr [RBP + -0x40]
  - FIELD@142c7e6ff:MOV qword ptr [RBP + -0x40],R10
  - FIELD@142c7e797:MOV dword ptr [RBP + -0x44],EAX
  - FIELD@142c7e77b:MOV dword ptr [RBP + -0x30],ESI
  - FIELD@142c7e6f1:MOV qword ptr [RBP + -0x34],R12
  - FIELD@142c7e778:MOV dword ptr [RBP + -0x48],EBX
  - FIELD@142c7e6f9:MOV dword ptr [RBP + -0x48],EBX
  - NAME:VELOCITY
  - FIELD@142c7e76c:MOV dword ptr [RBP + -0x38],0xffffffff
  - FIELD@142c7e600:MOVSS dword ptr [RBP + -0x50],XMM13
  - FIELD@142c7e7a3:MOV dword ptr [RBP + -0x34],R9D
  - FIELD@142c7e5f3:MOVSS dword ptr [RBP + -0x70],XMM15
  - FIELD@142c7e56e:MOV qword ptr [RBP + -0x18],RCX
  - FIELD@142c7e63f:MOVSS dword ptr [RBP + -0x20],XMM0
  - FIELD@142c7e72d:MOV R11,qword ptr [RBP + -0x28]
  - FIELD@142c7e527:LEA RBP,[RSP + -0x1b8]
  - FIELD@142c7e78d:LEA EAX,[RCX + -0x1]
  - FIELD@142c7e7be:MOVUPS XMM0,xmmword ptr [RBP + -0x48]
  - FIELD@142c7e5d8:MOVSS dword ptr [RBP + -0x6c],XMM11
  - FIELD@142c7e6f5:MOV qword ptr [RBP + -0x28],R11
  - FIELD@142c7e6df:MOV dword ptr [RBP + -0x44],0x1
  - FIELD@142c7e752:LEA EAX,[R9 + -0x1]
  - FIELD@142c7e7b3:MOV dword ptr [RBP + -0x34],ESI
  - FIELD@142c7e6ea:MOV dword ptr [RBP + -0x38],0xffffffff
  - FIELD@142c7e613:MOVSS dword ptr [RBP + -0x10],XMM6

#22 SCORE=967 REFS=4 CALLS=83 FIELDS=77
NAME: Spawn_Source
ADDR: 142ebb9a0
  - FIELD@142ebc2c7:MOV RAX,qword ptr [RBP + -0x68]
  - FIELD@142ebc330:MOV qword ptr [RBP + -0x80],R15
  - FIELD@142ebbbf8:MOV qword ptr [RBP + -0x68],R13
  - FIELD@142ebc38c:MOV qword ptr [RBP + -0x80],RCX
  - FIELD@142ebc368:CMP EAX,-0x1
  - FIELD@142ebc24c:MOVSS dword ptr [RBP + -0x24],XMM0
  - FIELD@142ebc251:MOVSS dword ptr [RBP + -0x1c],XMM2
  - NAME:PAWN
  - FIELD@142ebba75:MOV dword ptr [RBP + -0x58],EDI
  - FIELD@142ebbc69:MOV R13,qword ptr [RBP + -0x68]
  - FIELD@142ebc256:MOVSS dword ptr [RBP + -0x20],XMM1
  - FIELD@142ebc093:MOV qword ptr [RBP + -0x68],RCX
  - FIELD@142ebc334:MOV qword ptr [RBP + -0x60],R15
  - FIELD@142ebbd22:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142ebc3d9:MOV R8,qword ptr [RBP + -0x80]
  - FIELD@142ebbab3:MOV qword ptr [RBP + -0x50],R13
  - FIELD@142ebc09c:MOV qword ptr [RBP + -0x78],RDX
  - FIELD@142ebc294:MOV EAX,dword ptr [RBP + -0x1c]
  - FIELD@142ebc2da:MOV R8,qword ptr [RBP + -0x78]
  - FIELD@142ebb9b0:LEA RBP,[RSP + -0x150]
  - FIELD@142ebc2d1:MOV qword ptr [RBP + -0x70],RDX
  - FIELD@142ebc304:CMP EAX,-0x1
  - FIELD@142ebc28f:MOVSD XMM0,qword ptr [RBP + -0x24]
  - FIELD@142ebbc04:MOV qword ptr [RBP + -0x78],RDX
  - FIELD@142ebc326:MOV qword ptr [RBP + -0x70],RCX
  - FIELD@142ebc390:MOV qword ptr [RBP + -0x60],RAX

#23 SCORE=956 REFS=4 CALLS=165 FIELDS=0
NAME: ClimbingPositionTrace
ADDR: 141212800
  - NAME:POSITION

#24 SCORE=951 REFS=6 CALLS=38 FIELDS=2
NAME: GetInitGrappleAnchorRelativeOffset
ADDR: 140482e40
  - CALLS:GetBoneLocation
  - FIELD@14048321f:CMP EAX,-0x1
  - CALLS:GetTransform
  - CALLS:GetBoneTransform
  - CALLS:GetBoneIndex
  - NAME:RELATIVE
  - FIELD@140482ef1:MOV qword ptr [RSP + 0xa8],-0x1

#25 SCORE=939 REFS=3 CALLS=83 FIELDS=88
NAME: AddShapesToRigidActor
ADDR: 142ed9a00
  - FIELD@142ed9cde:MOVSS XMM1,dword ptr [RBP + -0x58]
  - FIELD@142ed9e6f:MOV qword ptr [RBP + -0x58],0x0
  - FIELD@142ed9ad9:MOV EAX,dword ptr [RBP + -0x58]
  - FIELD@142ed9a52:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - FIELD@142ed9ad2:MOV dword ptr [RBP + -0x58],0x3dcccccd
  - NAME:ACTOR
  - FIELD@142ed9ba0:MOVSS dword ptr [RBP + -0x78],XMM11
  - FIELD@142ed9a24:MOVAPS xmmword ptr [RAX + -0x58],XMM7
  - FIELD@142ed9a5a:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@142ed9a28:MOVAPS xmmword ptr [RAX + -0x68],XMM8
  - FIELD@142ed9ccf:MOVSS XMM2,dword ptr [RBP + -0x60]
  - FIELD@142ed9a12:LEA RBP,[RAX + -0xe8]
  - FIELD@142ed9a42:MOVAPS xmmword ptr [RAX + -0xa8],XMM12
  - FIELD@142ed9cd4:MOV dword ptr [RBP + -0x58],EAX
  - FIELD@142ed9a20:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@142ed9e8f:MOVSS dword ptr [RBP + -0x5c],XMM3
  - FIELD@142ed9bf3:MOV qword ptr [RBP + -0x70],RAX
  - FIELD@142ed9a4a:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@142ed9a2d:MOVAPS xmmword ptr [RAX + -0x78],XMM9
  - FIELD@142ed9d8f:LEA R8,[RBP + -0x70]
  - FIELD@142ed9e77:MOV qword ptr [RBP + -0x60],0x3
  - FIELD@142ed9ea4:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@142ed9a32:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@142ed9a3a:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@142ed9cca:MOVSD qword ptr [RBP + -0x60],XMM0
  - FIELD@142ed9ce8:MOVSS XMM0,dword ptr [RBP + -0x5c]

#26 SCORE=928 REFS=4 CALLS=22 FIELDS=97
NAME: Spawn
ADDR: 142e2e8d0
  - FIELD@142e2ef35:LEA RCX,[RBP + -0x80]
  - FIELD@142e2ee16:MOVSS dword ptr [RBP + -0x68],XMM6
  - FIELD@142e2edec:MOV EAX,dword ptr [RBP + -0x68]
  - FIELD@142e2ef41:MOV dword ptr [RBP + -0x68],EBX
  - FIELD@142e2ef49:MOVSS XMM0,dword ptr [RBP + -0x80]
  - FIELD@142e2ef4e:MOVSS XMM2,dword ptr [RBP + -0x7c]
  - FIELD@142e2ef63:MOV dword ptr [RBP + -0x44],EBX
  - NAME:PAWN
  - FIELD@142e2ea0b:MOV qword ptr [RBP + -0x10],RBX
  - FIELD@142e2e8da:LEA RBP,[RSP + -0xb8]
  - FIELD@142e2ef31:LEA RDX,[RBP + -0x70]
  - FIELD@142e2ee1b:MOV EAX,dword ptr [RBP + -0x68]
  - FIELD@142e2ea95:MOV dword ptr [RBP + -0x78],EBX
  - FIELD@142e2e99e:LEA RCX,[RBP + -0x10]
  - FIELD@142e2ebf1:MOV qword ptr [RBP + -0x80],RBX
  - FIELD@142e2eb94:MOVSS dword ptr [RBP + -0x68],XMM0
  - FIELD@142e2ef53:MOVSS XMM1,dword ptr [RBP + -0x78]
  - FIELD@142e2ea1a:MOV qword ptr [RBP + -0x60],RBX
  - FIELD@142e2e9c6:LEA RCX,[RBP + -0x8]
  - FIELD@142e2e9f7:MOV qword ptr [RBP + -0x8],RBX
  - FIELD@142e2eb99:MOV EAX,dword ptr [RBP + -0x68]
  - FIELD@142e2ede3:MOVSS dword ptr [RBP + -0x68],XMM0
  - FIELD@142e2ef39:MOV qword ptr [RBP + -0x70],0x3f800000
  - FIELD@142e2e95a:LEA RCX,[RBP + -0x60]
  - FIELD@142e2ea91:MOV qword ptr [RBP + -0x80],RBX
  - FIELD@142e2ebf5:MOV dword ptr [RBP + -0x78],EBX

#27 SCORE=927 REFS=6 CALLS=145 FIELDS=0
NAME: GetAimOffsetsTransform
ADDR: 1406a4be0
  - CALLS:Rotation
  - NAME:TRANSFORM
  - CALLS:GetClientRotationInterpSpeed
  - CALLS:BPModifyAimOffsetTargetLocation
  - CALLS:FRotationMatrix

#28 SCORE=917 REFS=52 CALLS=508 FIELDS=29
NAME: Z_Construct_UClass_ACharacter
ADDR: 14316be80
  - CALLS:Z_Construct_UFunction_ACharacter_CanJumpInternal
  - CALLS:Z_Construct_UFunction_ACharacter_ReplicateMovementToSimulatedClients
  - CALLS:Z_Construct_UFunction_ACharacter_IsJumpProvidingForce
  - FIELD@14316dd5e:LEA RCX,[RBP + -0x38]
  - FIELD@14316dc90:MOV EAX,dword ptr [RBP + -0x4c]
  - CALLS:GetPrivateStaticClassBody<ACharacter>
  - FIELD@14316bebc:MOV qword ptr [R11 + -0x20],R14
  - FIELD@14316e4c9:LEA RCX,[RBP + -0x48]
  - CALLS:Z_Construct_UScriptStruct_ACharacter_FBasedMovementInfo
  - FIELD@14316e408:MOV EAX,dword ptr [RBP + -0x7c]
  - CALLS:Z_Construct_UClass_APawn
  - CALLS:Z_Construct_UFunction_ACharacter_Crouch
  - CALLS:FDetermineBitMask_ACharacter_bOverrideFlyingVelocity
  - CALLS:Z_Construct_UFunction_ACharacter_GetCurrentMontage
  - CALLS:Z_Construct_UScriptStruct_UAnimationAsset_FRootMotionMovementParams
  - FIELD@14316bed6:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_ACharacter_PlayAnimMontage
  - CALLS:Z_Construct_UFunction_ACharacter_IsPlayingRootMotion
  - CALLS:FDetermineBitMask_ACharacter_bOverrideWalkingVelocity
  - FIELD@14316beda:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_ACharacter_LaunchCharacter
  - CALLS:Z_Construct_UFunction_ACharacter_K2_OnMovementModeChanged
  - CALLS:FDetermineBitMask_ACharacter_bOverrideNewFallVelocity
  - FIELD@14316bed2:MOV qword ptr [R11 + -0x10],R12
  - FIELD@14316dede:MOV EAX,dword ptr [RBP + -0xc]
  - CALLS:Z_Construct_UFunction_ACharacter_StopAnimMontage
  - NAME:CHARACTER
  - FIELD@14316db69:MOV EAX,dword ptr [RBP + -0x6c]
  - CALLS:Z_Construct_UFunction_ACharacter_K2_OnStartCrouch
  - CALLS:Z_Construct_UFunction_ACharacter_MovementModeChangedSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_ACharacter_Prone
  - FIELD@14316db5d:MOV R9D,dword ptr [RBP + -0x70]
  - FIELD@14316ded2:MOV R9D,dword ptr [RBP + -0x10]
  - CALLS:FDetermineBitMask_ACharacter_bReplicateDesiredRotation
  - CALLS:Z_Construct_UScriptStruct_ACharacter_FSimulatedRootMotionReplicatedMove
  - CALLS:Z_Construct_UFunction_ACharacter_K2_OnEndCrouch
  - CALLS:Z_Construct_UFunction_ACharacter_UnCrouch
  - FIELD@14316db10:LEA RCX,[RBP + -0x78]
  - CALLS:Z_Construct_UFunction_ACharacter_BPOverrideCharacterParticle
  - FIELD@14316dc37:LEA RCX,[RBP + -0x58]
  - CALLS:Z_Construct_UFunction_ACharacter_OnRep_ReplicatedBasedMovement
  - FIELD@14316be84:LEA RBP,[R11 + -0x408]
  - FIELD@14316e43e:LEA RCX,[RBP + -0x68]
  - FIELD@14316e3fc:MOV R9D,dword ptr [RBP + -0x80]
  - CALLS:Z_Construct_UFunction_ACharacter_OnLaunched
  - CALLS:Z_Construct_UFunction_ACharacter_BPValidateStoredClientRotationInput
  - CALLS:Z_Construct_UFunction_ACharacter_GetLastMovementDesiredRotation
  - CALLS:Z_Construct_UFunction_ACharacter_OverrideTerminalVelocity
  - CALLS:Z_Construct_UFunction_ACharacter_CharacterMovementUpdatedSignature__DelegateSignature
  - CALLS:Z_Construct_UFunction_ACharacter_CanJump
  - CALLS:Z_Construct_UFunction_ACharacter_NetTeleportSucceeded
  - FIELD@14316ddb7:MOV EAX,dword ptr [RBP + -0x2c]
  - CALLS:Z_Construct_UFunction_ACharacter_UnProne
  - FIELD@14316ddab:MOV R9D,dword ptr [RBP + -0x30]
  - CALLS:Z_Construct_UFunction_ACharacter_BP_PreventMovementMode
  - CALLS:Z_Construct_UFunction_ACharacter_ShouldForceDedicatedMovementTickEveryFrame
  - FIELD@14316dc84:MOV R9D,dword ptr [RBP + -0x50]
  - CALLS:Z_Construct_UFunction_ACharacter_IsRagdolled
  - CALLS:Z_Construct_UFunction_ACharacter_BPOverrideCharacterSound
  - CALLS:Z_Construct_UFunction_ACharacter_BPAcknowledgeServerCorrection
  - CALLS:FDetermineBitMask_ACharacter_bUseBPValidateStoredClientMovementInputs
  - CALLS:Z_Construct_UFunction_ACharacter_BPModifyRootMotionDeltaRotation
  - FIELD@14316e48b:MOV R9D,dword ptr [RBP + -0x60]
  - FIELD@14316e517:MOV R9D,dword ptr [RBP + -0x40]
  - CALLS:Z_Construct_UFunction_ACharacter_K2_UpdateCustomMovement
  - CALLS:Z_Construct_UFunction_ACharacter_OnLanded
  - FIELD@14316de85:LEA RCX,[RBP + -0x18]
  - FIELD@14316e497:MOV EAX,dword ptr [RBP + -0x5c]
  - CALLS:FDetermineBitMask_ACharacter_bOverrideSwimmingVelocity
  - FIELD@14316e523:MOV EAX,dword ptr [RBP + -0x3c]
  - CALLS:Z_Construct_UScriptStruct_ACharacter_FRepRootMotionMontage

#29 SCORE=911 REFS=5 CALLS=40 FIELDS=79
NAME: FUN_143be18c0
ADDR: 143be18c0
  - FIELD@143be1b9e:MOVSS XMM0,dword ptr [RBP + -0x14]
  - FIELD@143be1c7b:MOVSS XMM5,dword ptr [RBP + -0x1c]
  - FIELD@143be190c:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@143be1c5a:MOVSS XMM1,dword ptr [RBP + -0x24]
  - FIELD@143be1ac9:MOVSS dword ptr [RBP + -0x80],XMM1
  - FIELD@143be1c14:LEA RDX,[RBP + -0x50]
  - FIELD@143be1c2c:MOV qword ptr [RBP + -0x20],0x0
  - FIELD@143be18dc:MOV qword ptr [RAX + -0x20],R12
  - CALLS:transform
  - FIELD@143be1ab7:MOVSS dword ptr [RBP + -0x5c],XMM8
  - FIELD@143be1c6c:MOVSS XMM6,dword ptr [RBP + -0x20]
  - FIELD@143be18ca:LEA RBP,[RAX + -0x1f8]
  - FIELD@143be1c24:MOV qword ptr [RBP + -0x28],0x3
  - FIELD@143be1904:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@143be1ac3:MOVSS dword ptr [RBP + -0x54],XMM9
  - FIELD@143be1c49:LEA RDX,[RBP + -0x50]
  - FIELD@143be1c38:LEA RDX,[RBP + -0x28]
  - STRING_REF:Actor
  - FIELD@143be1ceb:MOV qword ptr [RBP + -0x10],0x2
  - FIELD@143be1b71:MOV qword ptr [RBP + -0x18],RAX
  - FIELD@143be1a95:MOVSS dword ptr [RBP + -0x60],XMM6
  - FIELD@143be18ee:MOV qword ptr [RAX + -0x38],R15
  - FIELD@143be1b6d:LEA RDX,[RBP + -0x18]
  - FIELD@143be18ea:MOV qword ptr [RAX + -0x30],R14
  - FIELD@143be1aa6:MOVSS dword ptr [RBP + -0x58],XMM7
  - FIELD@143be1b8d:LEA RDX,[RBP + -0x50]
  - FIELD@143be18e0:MOV qword ptr [RAX + -0x28],R13

#30 SCORE=876 REFS=2 CALLS=54 FIELDS=104
NAME: TestTransformCalculus
ADDR: 142407e50
  - FIELD@142407f85:LEA RCX,[RBP + -0x60]
  - CALLS:Concatenate<FShear2D,FSlateLayoutTransform>
  - CALLS:Concatenate<FMatrix2x2,FSlateLayoutTransform>
  - FIELD@142407e9b:MOV dword ptr [RBP + -0x20],0x40b9999a
  - FIELD@142407ea2:MOV dword ptr [RBP + -0x10],0x40e00000
  - CALLS:Concatenate<FSlateLayoutTransform,FMatrix2x2>
  - FIELD@142408188:MOV qword ptr [RBP + -0x80],0x0
  - FIELD@1424081a0:MOVAPS xmmword ptr [RBP + -0x30],XMM2
  - FIELD@1424080f5:LEA RCX,[RBP + -0x60]
  - FIELD@14240811f:MOVAPS xmmword ptr [RBP + -0x80],XMM2
  - CALLS:Concatenate<FSlateLayoutTransform,FShear2D>
  - FIELD@142407e54:LEA RBP,[RAX + -0xf8]
  - FIELD@142407e66:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@142407eb6:MOVSS dword ptr [RBP + -0x14],XMM0
  - FIELD@142407fd7:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@142407fdb:MOVAPS xmmword ptr [RBP + -0x70],XMM1
  - CALLS:Concatenate<FScale2D,FSlateLayoutTransform>
  - FIELD@142407e62:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@142407e6a:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@142408190:MOV dword ptr [RBP + -0x74],0x0
  - CALLS:Concatenate<FSlateLayoutTransform,FScale2D>
  - FIELD@142408197:MOVAPS xmmword ptr [RBP + -0x60],XMM0
  - CALLS:Concatenate<FQuat2D,FSlateLayoutTransform>
  - FIELD@14240819b:MOVSS dword ptr [RBP + -0x78],XMM6
  - FIELD@142407eb1:MOVSS dword ptr [RBP + -0x18],XMM1
  - FIELD@1424080e5:MOVAPS xmmword ptr [RBP + -0x70],XMM3
  - FIELD@1424080e1:MOVAPS xmmword ptr [RBP + -0x80],XMM2
  - FIELD@1424080ae:LEA R8,[RBP + -0x60]
  - FIELD@142408131:LEA RDX,[RBP + -0x60]
  - NAME:TRANSFORM
  - FIELD@1424080a5:LEA RCX,[RBP + -0x60]
  - FIELD@142408123:MOVAPS xmmword ptr [RBP + -0x70],XMM3
  - CALLS:Concatenate<FSlateLayoutTransform,FQuat2D>
  - CALLS:FRotationMatrix
  - FIELD@142407e6f:MOVAPS xmmword ptr [RAX + -0x48],XMM9

#31 SCORE=863 REFS=7 CALLS=56 FIELDS=23
NAME: GetSkinnedVertexPosition
ADDR: 142b73130
  - FIELD@142b73580:MOVZX ESI,byte ptr [R12 + -0x8]
  - FIELD@142b737d7:MOV RAX,qword ptr [RBP + -0x70]
  - FIELD@142b737d3:MOV RDX,qword ptr [RBP + -0x78]
  - FIELD@142b73fb0:MOVZX ESI,byte ptr [R12 + -0x4]
  - FIELD@142b74156:MOV qword ptr [RBP + -0x78],RAX
  - FIELD@142b7313c:LEA RBP,[RAX + -0x78]
  - FIELD@142b74203:MOV RDX,qword ptr [RBP + -0x70]
  - FIELD@142b7421a:MOV dword ptr [RBP + -0x68],EBX
  - NAME:POSITION
  - FIELD@142b7318e:MOV qword ptr [RAX + -0x30],R14
  - FIELD@142b7371b:MOV qword ptr [RBP + -0x70],RAX
  - FIELD@142b73942:MOV qword ptr [RBP + -0x80],R12
  - FIELD@142b73149:MOVAPS xmmword ptr [RAX + -0x58],XMM7
  - FIELD@142b7420f:MOV qword ptr [RBP + -0x70],RBX
  - FIELD@142b7318a:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142b74350:MOV R12,qword ptr [RBP + -0x80]
  - FIELD@142b73922:MOV R12,qword ptr [RBP + -0x80]
  - FIELD@142b73198:MOV qword ptr [RAX + -0x38],R15
  - FIELD@142b736c8:MOV qword ptr [RBP + -0x78],RDX
  - FIELD@142b73fa5:MOV qword ptr [RBP + -0x80],R12
  - FIELD@142b740f8:MOV qword ptr [RBP + -0x70],RDX
  - FIELD@142b7356d:MOV qword ptr [RBP + -0x80],R12
  - FIELD@142b74370:MOV qword ptr [RBP + -0x80],R12
  - FIELD@142b74207:MOV RAX,qword ptr [RBP + -0x78]

#32 SCORE=842 REFS=26 CALLS=139 FIELDS=93
NAME: Z_Construct_UClass_UMovementComponent
ADDR: 1431c3d90
  - CALLS:Z_Construct_UFunction_UMovementComponent_GetPlaneConstraintOrigin
  - FIELD@1431c40f1:MOVDQU xmmword ptr [RBP + -0x60],XMM0
  - FIELD@1431c42e0:MOV byte ptr [RBP + -0x4e],R15B
  - CALLS:Z_Construct_UFunction_UMovementComponent_SetPlaneConstraintNormal
  - FIELD@1431c3dd9:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1431c4111:MOV qword ptr [RBP + -0x48],R15
  - FIELD@1431c4264:MOV R14D,dword ptr [RBP + -0x68]
  - FIELD@1431c4283:MOV byte ptr [RBP + -0x4e],0x1
  - FIELD@1431c4108:MOV word ptr [RBP + -0x50],0x100
  - CALLS:Z_Construct_UFunction_UMovementComponent_GetPhysicsVolume
  - CALLS:Z_Construct_UFunction_UMovementComponent_IsExceedingMaxSpeed
  - FIELD@1431c3ddd:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_UMovementComponent_SetUpdatedComponent
  - FIELD@1431c427d:MOV word ptr [RBP + -0x50],0x100
  - FIELD@1431c412e:MOV RAX,qword ptr [RBP + -0x60]
  - CALLS:Z_Construct_UClass_UActorComponent
  - CALLS:Z_Construct_UFunction_UMovementComponent_K2_GetModifiedMaxSpeed
  - FIELD@1431c4287:MOV qword ptr [RBP + -0x48],R15
  - CALLS:Z_Construct_UFunction_UMovementComponent_K2_MoveUpdatedComponent
  - FIELD@1431c41ce:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UFunction_UMovementComponent_PhysicsVolumeChanged
  - CALLS:Z_Construct_UFunction_UMovementComponent_SnapUpdatedComponentToPlane
  - FIELD@1431c41d7:MOV qword ptr [RBP + -0x70],RAX
  - CALLS:Z_Construct_UFunction_UMovementComponent_SetPlaneConstraintOrigin
  - FIELD@1431c3d94:LEA RBP,[R11 + -0x118]
  - CALLS:Z_Construct_UFunction_UMovementComponent_SetPlaneConstraintFromVectors
  - FIELD@1431c41bb:LEA RCX,[RBP + -0x60]
  - CALLS:Z_Construct_UFunction_UMovementComponent_ConstrainLocationToPlane
  - NAME:MOVEMENT
  - CALLS:Z_Construct_UFunction_UMovementComponent_ConstrainDirectionToPlane
  - FIELD@1431c410e:MOV byte ptr [RBP + -0x4e],BL
  - FIELD@1431c4163:MOV qword ptr [RBP + -0x60],RDI
  - FIELD@1431c426b:MOVDQU xmmword ptr [RBP + -0x60],XMM0
  - FIELD@1431c3de1:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1431c42dc:MOV qword ptr [RBP + -0x60],RDI
  - CALLS:Z_Construct_UFunction_UMovementComponent_ShouldForceDedicatedTickEveryFrame
  - CALLS:Z_Construct_UFunction_UMovementComponent_K2_GetMaxSpeedModifier
  - CALLS:GetPrivateStaticClassBody<UMovementComponent>
  - FIELD@1431c42a4:MOV RAX,qword ptr [RBP + -0x60]
  - CALLS:Z_Construct_UFunction_UMovementComponent_GetMaxSpeed
  - FIELD@1431c3db7:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1431c4261:MOV ESI,dword ptr [RBP + -0x64]
  - CALLS:Z_Construct_UFunction_UMovementComponent_GetGravityZ
  - CALLS:Z_Construct_UFunction_UMovementComponent_GetPlaneConstraintNormal
  - FIELD@1431c41db:MOV qword ptr [RBP + -0x68],R15
  - CALLS:Z_Construct_UFunction_UMovementComponent_StopMovementImmediately
  - FIELD@1431c4167:MOV byte ptr [RBP + -0x4e],R15B

#33 SCORE=840 REFS=2 CALLS=13 FIELDS=68
NAME: GetBestShadowTransform
ADDR: 1437c9900
  - FIELD@1437c9942:MOVAPS xmmword ptr [RAX + -0xa8],XMM12
  - FIELD@1437c9920:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@1437c9928:MOVAPS xmmword ptr [RAX + -0x68],XMM8
  - FIELD@1437c9a4c:MOVSS XMM12,dword ptr [RBP + -0x5c]
  - FIELD@1437c9a55:SUBSS XMM11,dword ptr [RBP + -0x50]
  - FIELD@1437c9a23:MOVSD qword ptr [RBP + -0x50],XMM0
  - FIELD@1437c9add:MOVSS dword ptr [RBP + -0x68],XMM10
  - FIELD@1437c9912:LEA RBP,[RAX + -0x138]
  - FIELD@1437c9a5b:SUBSS XMM12,dword ptr [RBP + -0x4c]
  - FIELD@1437c992d:MOVAPS xmmword ptr [RAX + -0x78],XMM9
  - FIELD@1437c9a52:MOV dword ptr [RBP + -0x58],EAX
  - FIELD@1437c9ad3:MOVSS dword ptr [RBP + -0x6c],XMM12
  - FIELD@1437c9952:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - FIELD@1437c9932:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@1437c993a:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@1437c9a46:MOVSS XMM11,dword ptr [RBP + -0x60]
  - FIELD@1437c9a77:SUBSS XMM10,dword ptr [RBP + -0x48]
  - FIELD@1437c9a28:MOV dword ptr [RBP + -0x48],EAX
  - FIELD@1437c9acd:MOVSS dword ptr [RBP + -0x70],XMM11
  - FIELD@1437c994a:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@1437c995a:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@1437c9a61:MOVSS XMM10,dword ptr [RBP + -0x58]
  - NAME:TRANSFORM
  - FIELD@1437c9a41:MOVSD qword ptr [RBP + -0x60],XMM0
  - FIELD@1437c9ae9:MOVSD XMM0,qword ptr [RBP + -0x70]
  - FIELD@1437c9924:MOVAPS xmmword ptr [RAX + -0x58],XMM7

#34 SCORE=839 REFS=28 CALLS=472 FIELDS=0
NAME: StaticRegisterNativesAActor
ADDR: 142f94930
  - CALLS:execAddActorLocalRotation
  - CALLS:execGetTransform
  - CALLS:execGetActorRelativeScale3D
  - CALLS:execSetActorRelativeTransform
  - CALLS:execPlaySoundAtLocation
  - CALLS:execK2_AttachRootComponentToActor
  - CALLS:execGetTargetingLocation
  - CALLS:execSetActorRelativeLocation
  - CALLS:execK2_GetRootComponent
  - CALLS:execK2_SetActorLocation
  - CALLS:execSnapRootComponentTo
  - NAME:ACTOR
  - CALLS:execSetActorRelativeScale3D
  - CALLS:execSetActorLocationAndRotation
  - CALLS:execOnRep_ReplicatedMovement
  - CALLS:execSetActorRelativeRotation
  - CALLS:execSetActorRotation
  - CALLS:execGetInterpolatedTransform
  - CALLS:execSetActorTransform
  - CALLS:execGetInterpolatedLocation
  - CALLS:execK2_GetActorRotation
  - CALLS:execGetInterpolatedRotation
  - STRING_REF:SceneComponent
  - AACTOR
  - CALLS:execNetAttachRootComponentTo
  - CALLS:execK2_AttachRootComponentTo
  - CALLS:execAddActorWorldRotation
  - CALLS:execAddActorWorldTransform
  - CALLS:execGetVelocity
  - CALLS:execAddActorLocalTransform
  - CALLS:execK2_GetActorLocation
  - STRING_REF:RelativeLocation
  - CALLS:execDetachRootComponentFromParent
  - STRING_REF:RootComponent

#35 SCORE=826 REFS=2 CALLS=220 FIELDS=1
NAME: ListenServerClampPlayerLocations
ADDR: 140f24770
  - CALLS:SetActorLocation
  - NAME:PLAYER
  - CALLS:ClearRidingDino
  - NAME:LOCATION
  - CALLS:~TSparseArray<TSetElement<AActor_*___ptr64>,TSparseArrayAllocator<FDefaultAllocator,FDefaultBitArrayAllocator>_>
  - FIELD@140f25d07:CMP dword ptr [RAX],-0x1

#36 SCORE=824 REFS=4 CALLS=729 FIELDS=4
NAME: DrawLocalPlayerHUD
ADDR: 140590280
  - FIELD@14059302c:MOV qword ptr [RSP + 0x7d0],-0x1
  - FIELD@14059645d:CMP dword ptr [RCX + RAX*0x1],-0x1
  - NAME:PLAYER
  - CALLS:operator==<AActor,AActor,FWeakObjectPtr,FIndexToObject>
  - FIELD@14059472e:MOV qword ptr [RSP + 0x7c8],-0x1
  - FIELD@140590e9d:MOV qword ptr [RSP + 0x7c0],-0x1

#37 SCORE=817 REFS=4 CALLS=54 FIELDS=51
NAME: FindSimplePathToActor
ADDR: 1426532a0
  - FIELD@1426539c4:MOVSS dword ptr [RBP + -0x7c],XMM2
  - FIELD@142653a27:MOVSS dword ptr [RBP + -0x5c],XMM1
  - FIELD@1426539d9:MOVSS dword ptr [RBP + -0x78],XMM1
  - FIELD@1426532d6:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@1426532db:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@1426532eb:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - NAME:ACTOR
  - FIELD@1426532b8:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142653a83:MULPS XMM0,xmmword ptr [RBP + -0x70]
  - FIELD@1426532bc:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@1426532fb:MOVAPS xmmword ptr [RAX + -0xc8],XMM15
  - FIELD@142653a02:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@1426532f3:MOVAPS xmmword ptr [RAX + -0xb8],XMM14
  - FIELD@1426532e3:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@142653a3e:MOVSS dword ptr [RBP + -0x68],XMM15
  - FIELD@142653a1c:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@142653a87:MULPS XMM1,xmmword ptr [RBP + -0x80]
  - FIELD@142653a12:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@1426532b4:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@1426532a9:LEA RBP,[RAX + -0x78]
  - FIELD@1426538c7:MOV dword ptr [RBP + -0x64],0x0
  - FIELD@1426538c0:MOV dword ptr [RBP + -0x74],0x0
  - FIELD@1426538ce:MOV dword ptr [RBP + -0x54],0x3f800000
  - FIELD@1426532d1:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - FIELD@1426539a7:MOVSS dword ptr [RBP + -0x80],XMM1
  - FIELD@142653a0c:MOVSS dword ptr [RBP + -0x6c],XMM14

#38 SCORE=812 REFS=4 CALLS=63 FIELDS=48
NAME: FindPathToActor
ADDR: 1426542a0
  - FIELD@1426542df:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@1426542f2:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@1426546fa:MOVSS dword ptr [RBP + -0x58],XMM8
  - FIELD@142654302:MOVAPS xmmword ptr [RAX + -0xb8],XMM14
  - FIELD@1426547b9:MOVSS dword ptr [RBP + -0x5c],XMM1
  - FIELD@142654851:MOVSS dword ptr [RBP + -0x3c],XMM14
  - FIELD@1426542da:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - NAME:ACTOR
  - FIELD@14265430a:MOVAPS xmmword ptr [RAX + -0xc8],XMM15
  - FIELD@1426542c8:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@1426542e4:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@142654847:MOVSS dword ptr [RBP + -0x30],XMM0
  - FIELD@1426542a6:LEA RBP,[RAX + -0x228]
  - FIELD@142654715:MOV dword ptr [RBP + -0x24],0x3f800000
  - FIELD@1426547ec:MOVSS dword ptr [RBP + -0x50],XMM1
  - FIELD@1426542fa:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - FIELD@14265481e:MOVSS dword ptr [RBP + -0x48],XMM1
  - FIELD@142654760:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@142654809:MOVSS dword ptr [RBP + -0x4c],XMM2
  - FIELD@1426542c4:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@1426542c0:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@14265470e:MOV dword ptr [RBP + -0x34],0x0
  - FIELD@142654700:MOV dword ptr [RBP + -0x54],0x0
  - FIELD@1426542b8:MOV qword ptr [RAX + -0x20],R14
  - FIELD@1426542bc:MOV qword ptr [RAX + -0x28],R15
  - FIELD@142654707:MOV dword ptr [RBP + -0x44],0x0

#39 SCORE=808 REFS=9 CALLS=155 FIELDS=125
NAME: Z_Construct_UClass_UProjectileMovementComponent
ADDR: 1431fbb70
  - FIELD@1431fbbc2:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1431fbfec:LEA RCX,[RBP + -0x58]
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bForceSubStepping
  - FIELD@1431fbbc6:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_UProjectileMovementComponent_StopSimulating
  - FIELD@1431fbb97:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1431fbe4a:MOV byte ptr [RBP + -0x46],0x1
  - FIELD@1431fbd50:MOV word ptr [RBP + -0x48],0x100
  - FIELD@1431fbf68:MOV RCX,qword ptr [RBP + -0x58]
  - FIELD@1431fbf3f:MOV qword ptr [RBP + -0x40],R14
  - FIELD@1431fbd56:MOV byte ptr [RBP + -0x46],DIL
  - FIELD@1431fbd90:LEA RCX,[RBP + -0x58]
  - FIELD@1431fbf29:MOV word ptr [RBP + -0x48],0x100
  - FIELD@1431fbe86:LEA RCX,[RBP + -0x58]
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bIsHomingProjectile
  - FIELD@1431fbe32:MOVDQU xmmword ptr [RBP + -0x58],XMM0
  - FIELD@1431fbf2f:MOV byte ptr [RBP + -0x46],0x1
  - CALLS:Z_Construct_UFunction_UProjectileMovementComponent_SetVelocityInLocalSpace
  - FIELD@1431fbe44:MOV word ptr [RBP + -0x48],0x100
  - CALLS:Z_Construct_UFunction_UProjectileMovementComponent_OnProjectileStopDelegate__DelegateSignature
  - CALLS:Z_Construct_UClass_UMovementComponent
  - CALLS:Z_Construct_UFunction_UProjectileMovementComponent_OnProjectileBounceDelegate__DelegateSignature
  - FIELD@1431fbe25:LEA RDX,[RBP + -0x58]
  - FIELD@1431fbb74:LEA RBP,[R11 + -0x128]
  - FIELD@1431fbf99:MOV qword ptr [RBP + -0x58],RBX
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bShouldBounce
  - NAME:MOVEMENT
  - FIELD@1431fbd31:LEA RDX,[RBP + -0x58]
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bRotationFollowsVelocity
  - CALLS:GetPrivateStaticClassBody<UProjectileMovementComponent>
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bTriggerBounceImpactNotification
  - FIELD@1431fbf33:MOVDQU xmmword ptr [RBP + -0x58],XMM0
  - FIELD@1431fbd35:MOVDQU xmmword ptr [RBP + -0x58],XMM0
  - FIELD@1431fbe4e:MOV qword ptr [RBP + -0x40],R14
  - CALLS:Z_Construct_UFunction_UProjectileMovementComponent_LimitVelocity
  - FIELD@1431fbd5a:MOV qword ptr [RBP + -0x40],R14
  - CALLS:FDetermineBitMask_UProjectileMovementComponent_bInitialVelocityInLocalSpace
  - FIELD@1431fbbbe:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1431fbf9d:MOV byte ptr [RBP + -0x46],R14B

#40 SCORE=786 REFS=6 CALLS=40 FIELDS=2
NAME: GetGrappleAnchorWorldLocation
ADDR: 140485300
  - FIELD@1404856e0:CMP EAX,-0x1
  - CALLS:GetBoneLocation
  - CALLS:GetTransform
  - NAME:LOCATION
  - CALLS:GetBoneTransform
  - CALLS:GetBoneIndex
  - FIELD@1404853a9:MOV qword ptr [RSP + 0xa0],-0x1

#41 SCORE=776 REFS=5 CALLS=41 FIELDS=79
NAME: ModifyBonesEvaluateBoneTransforms
ADDR: 142d30ba0
  - FIELD@142d30c79:MOV dword ptr [RBP + -0x40],R12D
  - FIELD@142d30ea8:CMP EAX,-0x1
  - FIELD@142d30c7d:MOV dword ptr [RBP + -0x3c],EBX
  - FIELD@142d30efb:MOV ECX,dword ptr [RBP + -0x28]
  - FIELD@142d30c44:MOV qword ptr [RBP + -0x68],RBX
  - NAME:BONE
  - FIELD@142d30bf3:MOV qword ptr [RBP + -0x78],R8
  - FIELD@142d30bdc:MOV qword ptr [R11 + -0x30],R14
  - FIELD@142d30ba5:LEA RBP,[R11 + -0x158]
  - FIELD@142d30f1a:LEA EAX,[RCX + -0x1]
  - FIELD@142d30be4:MOV qword ptr [RBP + -0x80],R9
  - FIELD@142d30c71:LEA RCX,[RBP + -0x38]
  - FIELD@142d30f13:LEA RAX,[RBP + -0x38]
  - FIELD@142d30bcc:MOV qword ptr [R11 + -0x18],RDI
  - FIELD@142d30c8e:MOV dword ptr [RBP + -0x28],EBX
  - FIELD@142d30c37:LEA RCX,[RBP + -0x60]
  - FIELD@142d30c40:MOV qword ptr [RBP + -0x70],RBX
  - FIELD@142d30f02:MOV R9,qword ptr [RBP + -0x30]
  - FIELD@142d30be0:MOV qword ptr [R11 + -0x38],R15
  - FIELD@142d30be8:MOVAPS xmmword ptr [R11 + -0xd8],XMM15
  - FIELD@142d30edc:CMP EAX,-0x1
  - FIELD@142d30f2c:CMP EAX,-0x1
  - CALLS:GetComponentSpaceTransform
  - CALLS:AccumulateToLocalSpaceBoneTransforms
  - FIELD@142d30bd8:MOV qword ptr [R11 + -0x28],R13
  - FIELD@142d30e84:CMP EAX,-0x1
  - NAME:TRANSFORM
  - FIELD@142d30e72:LEA EAX,[RCX + -0x1]
  - FIELD@142d30bd4:MOV qword ptr [R11 + -0x20],R12

#42 SCORE=770 REFS=4 CALLS=28 FIELDS=73
NAME: CalcSliceTransform
ADDR: 142b92690
  - FIELD@142b926f3:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@142b92703:MOVAPS xmmword ptr [RAX + -0xb8],XMM14
  - FIELD@142b926ce:MOV qword ptr [RBP + -0x50],0x0
  - FIELD@142b92771:LEA RSI,[RBP + -0x5c]
  - FIELD@142b926a9:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142b926eb:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@142b9272f:MOVUPS xmmword ptr [RBP + -0x60],XMM0
  - FIELD@142b926fb:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - FIELD@142b9270b:MOVAPS xmmword ptr [RAX + -0xc8],XMM15
  - FIELD@142b926dd:MOVUPS xmmword ptr [RBP + -0x60],XMM0
  - FIELD@142b927ba:LEA RAX,[RBP + -0x54]
  - FIELD@142b92777:LEA RSI,[RBP + -0x60]
  - FIELD@142b926e6:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142b92733:MOVSD qword ptr [RBP + -0x50],XMM1
  - FIELD@142b926ad:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@142b9276b:LEA RSI,[RBP + -0x58]
  - FIELD@142b9272c:MOV dword ptr [RBP + -0x48],EAX
  - FIELD@142b92697:LEA RBP,[RAX + -0xa8]
  - FIELD@142b926a5:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142b927b4:LEA RAX,[RBP + -0x50]
  - FIELD@142b926d6:MOV dword ptr [RBP + -0x48],0x0
  - FIELD@142b927ae:LEA RAX,[RBP + -0x4c]
  - FIELD@142b92803:LEA RAX,[RBP + -0x50]
  - FIELD@142b927fd:LEA RAX,[RBP + -0x4c]
  - NAME:TRANSFORM
  - FIELD@142b926e1:MOVAPS xmmword ptr [RAX + -0x68],XMM9

#43 SCORE=766 REFS=3 CALLS=34 FIELDS=0
NAME: UpdateOwnerSwingingVelocity
ADDR: 140469330
  - CALLS:GetTransform
  - NAME:VELOCITY
  - CALLS:CanManipulateOwnerVelocity
  - CALLS:GetControlRotation
  - CALLS:FRotationMatrix

#44 SCORE=757 REFS=427 CALLS=2076 FIELDS=0
NAME: Z_Construct_UClass_APrimalDinoCharacter
ADDR: 141d14860
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPCheckCanSpawnFromLocation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPDesiredRotationIsLocalSpace
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPOverrideFloatingHUDLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_OverrideRandomWanderLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetCurrentAimOffsetsRotation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBP_OverrideCarriedCharacterTransform
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPModifyControlRotation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_SetTurretModeMovementRestrictions
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bForceAllowBackwardsMovementWithNoRider
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bLocationBasedAttack
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_ApplyRidingAttackExtraVelocity
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPModifyControlRotation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bPreventRotationRateModifier
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bBPManagedFPVViewLocationNoRider
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetLandingLocation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bForceAllowBackwardsMovement
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bRiderMovementLocked
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPPreventSpawnForPlayer
  - NAME:CHARACTER
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetSocketLocationTemp
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPGetRiderUnboardLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPDesiredRotationIsLocalSpace
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bOverrideRotationOnCarriedCharacter
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseInteprolatedVelocity
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_ServerSetRiderMountedWeaponRotation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bRiderDontBeBlockedByPawnMesh
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BP_OverrideCarriedCharacterTransform
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPGetRiderUnboardLocation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseVelocityForRequestedMoveIfStuck
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_SetLastMovementDesiredRotation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_ShouldAttackOfPlayedAnimationStopMovement
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_SpawnedPlayerFor
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bBPModifyAimOffsetTargetLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_OverrideFinalWanderLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetPlayerSpawnLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetAimOffsetsTransform
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetDinoVelocity
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bPreventMovementModeChangeForDinoPassengers
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_ClearCharacterAIMovement
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bAttackStopsRotation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBP_CustomModifier_RotationRate
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_IsCurrentAttackStopsMovement
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPCheckCanSpawnFromLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetPlayerSpawnRotation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPModifyAimOffsetTargetLocation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bServerForceUpdateDinoGameplayMeshNearPlayer
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPGetCrosshairLocation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPOverrideFloatingHUDLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPModifyDesiredRotation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BP_GetCustomModifier_RotationRate
  - CALLS:Z_Construct_UScriptStruct_APrimalDinoCharacter_FPrimalSaddleStructure
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_SetMovementAccelerationVector
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseLocalSpaceDesiredRotationWithRider
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPGetCrosshairLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_GetActorCenterTraceLocation
  - CALLS:Z_Construct_UFunction_APrimalDinoCharacter_BPOverrideCameraViewTarget
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bUseBPModifyDesiredRotation
  - CALLS:FDetermineBitMask_APrimalDinoCharacter_bAttackStopsMovement

#45 SCORE=750 REFS=23 CALLS=260 FIELDS=60
NAME: Z_Construct_UClass_UWheeledVehicleMovementComponent
ADDR: 1431f53b0
  - FIELD@1431f5409:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1431f540d:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1431f5755:MOV byte ptr [RBP + -0x7e],SIL
  - FIELD@1431f5839:MOV word ptr [RBP + -0x80],0x100
  - FIELD@1431f56e5:MOV qword ptr [RBP + -0x78],R12
  - FIELD@1431f5a0f:MOV byte ptr [RBP + -0x7e],SIL
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetCurrentGear
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetEngineRotationSpeed
  - FIELD@1431f5c7d:MOV byte ptr [RBP + -0x7e],0x1
  - CALLS:Z_Construct_UScriptStruct_UWheeledVehicleMovementComponent_FVehicleInputRate
  - CALLS:Z_Construct_UClass_UPawnMovementComponent
  - FIELD@1431f53db:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1431f5afd:MOV byte ptr [RBP + -0x7e],0x1
  - FIELD@1431f56fe:MOV byte ptr [RBP + -0x7e],BL
  - CALLS:Z_Construct_UScriptStruct_UWheeledVehicleMovementComponent_FWheelSetup
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetThrottleInput
  - FIELD@1431f5b6e:MOV byte ptr [RBP + -0x7e],SIL
  - FIELD@1431f5d68:MOV word ptr [RBP + -0x80],0x100
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_ServerUpdateState
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetGearDown
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetHandbrakeInput
  - FIELD@1431f56df:MOV word ptr [RBP + -0x80],0x100
  - FIELD@1431f5998:MOV word ptr [RBP + -0x80],0x100
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetTargetGear
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetUseAutoGears
  - FIELD@1431f5c77:MOV word ptr [RBP + -0x80],0x100
  - FIELD@1431f5af7:MOV word ptr [RBP + -0x80],0x100
  - FIELD@1431f599e:MOV byte ptr [RBP + -0x7e],0x1
  - FIELD@1431f59af:MOV qword ptr [RBP + -0x78],R12
  - FIELD@1431f5850:MOV qword ptr [RBP + -0x78],R12
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetEngineMaxRotationSpeed
  - CALLS:Z_Construct_UScriptStruct_UWheeledVehicleMovementComponent_FReplicatedVehicleState
  - FIELD@1431f58b0:MOV byte ptr [RBP + -0x7e],SIL
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetForwardSpeed
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetUseAutoGears
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetGearUp
  - NAME:MOVEMENT
  - CALLS:GetPrivateStaticClassBody<UWheeledVehicleMovementComponent>
  - FIELD@1431f5405:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetSteeringInput
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_SetTargetGear
  - CALLS:Z_Construct_UFunction_UWheeledVehicleMovementComponent_GetThrottleInput
  - FIELD@1431f583f:MOV byte ptr [RBP + -0x7e],0x1
  - FIELD@1431f5b0e:MOV qword ptr [RBP + -0x78],R12
  - FIELD@1431f53b4:LEA RBP,[R11 + -0x238]
  - FIELD@1431f5c81:MOV qword ptr [RBP + -0x78],R12

#46 SCORE=748 REFS=4 CALLS=41 FIELDS=73
NAME: EvaluateBoneTransforms
ADDR: 142d31c00
  - FIELD@142d31cf3:MOV dword ptr [RBP + -0x40],R12D
  - FIELD@142d31fe8:MOV RAX,qword ptr [RBP + -0x70]
  - FIELD@142d31fbd:CMP EAX,-0x1
  - FIELD@142d31cb1:MOV qword ptr [RBP + -0x70],RBX
  - FIELD@142d31cf7:MOV dword ptr [RBP + -0x3c],EBX
  - NAME:BONE
  - FIELD@142d31ee2:LEA EAX,[RCX + -0x1]
  - FIELD@142d31f4c:CMP EAX,-0x1
  - FIELD@142d31c8f:LEA RCX,[RBP + -0x60]
  - FIELD@142d31d08:MOV dword ptr [RBP + -0x28],EBX
  - FIELD@142d31f6b:MOV ECX,dword ptr [RBP + -0x28]
  - FIELD@142d31ceb:LEA RCX,[RBP + -0x38]
  - FIELD@142d31f9c:CMP EAX,-0x1
  - FIELD@142d31c36:MOV qword ptr [RBP + -0x78],R8
  - FIELD@142d31fd1:LEA RCX,[RBP + -0x70]
  - FIELD@142d32061:MOV R13,qword ptr [RBP + -0x78]
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d31c07:LEA RBP,[RSP + -0x138]
  - CALLS:AccumulateToLocalSpaceBoneTransforms
  - FIELD@142d31f72:MOV R9,qword ptr [RBP + -0x30]
  - FIELD@142d31cd0:MOV qword ptr [RBP + -0x68],RBX
  - FIELD@142d31fa8:MOV RCX,qword ptr [RBP + -0x70]
  - FIELD@142d32069:MOV EAX,dword ptr [RBP + -0x68]
  - NAME:TRANSFORM
  - FIELD@142d31c2b:MOV qword ptr [RBP + -0x80],R9
  - FIELD@142d31f18:CMP EAX,-0x1
  - FIELD@142d31f83:LEA RAX,[RBP + -0x38]
  - FIELD@142d31f8a:LEA EAX,[RCX + -0x1]
  - FIELD@142d31ef4:CMP EAX,-0x1

#47 SCORE=741 REFS=9 CALLS=25 FIELDS=88
NAME: GetTetheredVelocity
ADDR: 142aacd20
  - FIELD@142aad035:MOVSS XMM7,dword ptr [RBP + -0x69]
  - FIELD@142aacfcb:MOV EAX,dword ptr [RBP + -0x61]
  - FIELD@142aacff5:MOVSS dword ptr [RBP + -0x65],XMM0
  - FIELD@142aacde4:LEA RDX,[RBP + -0x79]
  - FIELD@142aad030:MOVSD qword ptr [RBP + -0x69],XMM0
  - NAME:VELOCITY
  - FIELD@142aace0c:MOVSS dword ptr [RBP + -0x75],XMM0
  - FIELD@142aacdfa:MOVSS dword ptr [RBP + -0x79],XMM1
  - FIELD@142aacd45:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142aad044:SUBSS XMM6,dword ptr [RBP + -0x75]
  - FIELD@142aad03f:SUBSS XMM7,dword ptr [RBP + -0x79]
  - FIELD@142aacfff:MOV EAX,dword ptr [RBP + -0x61]
  - FIELD@142aad017:MOVSD qword ptr [RBP + -0x59],XMM0
  - FIELD@142aacd28:LEA RBP,[RAX + -0x5f]
  - FIELD@142aad03a:MOVSS XMM6,dword ptr [RBP + -0x65]
  - FIELD@142aacd40:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - FIELD@142aad049:MOVSS XMM8,dword ptr [RBP + -0x61]
  - FIELD@142aad014:MOV dword ptr [RBP + -0x51],EAX
  - FIELD@142aacfdf:MOVSS dword ptr [RBP + -0x69],XMM1
  - FIELD@142aacfc1:LEA RDX,[RBP + -0x69]
  - FIELD@142aace07:MOVSS dword ptr [RBP + -0x71],XMM1
  - FIELD@142aacfce:MOVSD XMM0,qword ptr [RBP + -0x69]
  - FIELD@142aacffa:MOVSD XMM0,qword ptr [RBP + -0x69]
  - FIELD@142aacff0:MOVSS dword ptr [RBP + -0x61],XMM1
  - FIELD@142aad02a:MOV dword ptr [RBP + -0x61],EAX
  - FIELD@142aad01c:LEA RAX,[RBP + -0x59]

#48 SCORE=740 REFS=3 CALLS=115 FIELDS=0
NAME: ClampBuildLocation
ADDR: 140a3a210
  - NAME:LOCATION
  - CALLS:GetPlacingGroundLocation
  - CALLS:GetPhysicsVolumeAtLocation

#49 SCORE=738 REFS=5 CALLS=94 FIELDS=35
NAME: PhysicsRotation
ADDR: 1428d6470
  - FIELD@1428d7008:MOVSS dword ptr [RBP + -0x68],XMM1
  - FIELD@1428d708a:MOVSD qword ptr [RBP + -0x80],XMM0
  - FIELD@1428d700d:MOVSS dword ptr [RBP + -0x6c],XMM0
  - FIELD@1428d6ffb:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@1428d6bbc:MOVSS XMM2,dword ptr [RBP + -0x5c]
  - FIELD@1428d70d9:MOV dword ptr [RBP + -0x78],EAX
  - NAME:ROTATION
  - FIELD@1428d6fe4:LEA RDX,[RBP + -0x70]
  - FIELD@1428d67b0:LEA RDX,[RBP + -0x80]
  - FIELD@1428d6478:LEA RBP,[RSP + -0x68]
  - FIELD@1428d652e:LEA RDX,[RBP + -0x60]
  - FIELD@1428d6ea6:MOVSS XMM2,dword ptr [RBP + -0x60]
  - FIELD@1428d708f:MOV dword ptr [RBP + -0x78],EAX
  - FIELD@1428d7092:LEA RAX,[RBP + -0x80]
  - FIELD@1428d6c23:MOVSS XMM2,dword ptr [RBP + -0x5c]
  - FIELD@1428d6514:LEA RCX,[RBP + -0x50]
  - FIELD@1428d651f:MOVAPS xmmword ptr [RBP + -0x50],XMM0
  - FIELD@1428d70c2:SUBSS XMM1,dword ptr [RBP + -0x6c]
  - FIELD@1428d6871:LEA RDX,[RBP + -0x80]
  - FIELD@1428d70bd:SUBSS XMM2,dword ptr [RBP + -0x70]
  - FIELD@1428d70c7:SUBSS XMM0,dword ptr [RBP + -0x68]
  - FIELD@1428d6575:LEA RDX,[RBP + -0x80]
  - FIELD@1428d6ee2:MOVSS XMM2,dword ptr [RBP + -0x58]
  - FIELD@1428d7096:LEA RDX,[RBP + -0x50]
  - FIELD@1428d6564:LEA RCX,[RBP + -0x60]
  - FIELD@1428d65d5:LEA RDX,[RBP + -0x80]

#50 SCORE=723 REFS=3 CALLS=117 FIELDS=99
NAME: SpawnEx
ADDR: 142e87db0
  - FIELD@142e8818d:MOVSD qword ptr [RBP + -0x79],XMM0
  - FIELD@142e87ddf:MOVAPS xmmword ptr [RAX + -0x68],XMM7
  - NAME:PAWN
  - FIELD@142e8815d:MOV dword ptr [RBP + -0x59],R12D
  - FIELD@142e88145:MOV R12D,dword ptr [RBP + -0x59]
  - FIELD@142e87fe9:LEA R12,[RBP + -0x41]
  - FIELD@142e87ed8:MOV dword ptr [RBP + -0x59],R15D
  - FIELD@142e87f13:LEA R8,[RBP + -0x49]
  - FIELD@142e87fcd:LEA R12,[RBP + -0x49]
  - FIELD@142e87f6d:LEA R12,[RBP + -0x41]
  - FIELD@142e8817e:MOV dword ptr [RBP + -0x71],EAX
  - FIELD@142e87dee:MOVAPS xmmword ptr [RAX + -0x88],XMM12
  - FIELD@142e87f51:LEA R12,[RBP + -0x49]
  - FIELD@142e87f62:LEA R12,[RBP + -0x45]
  - FIELD@142e87e5a:MOV dword ptr [RBP + -0x55],R15D
  - FIELD@142e87e42:MOV dword ptr [RBP + -0x55],ESI
  - FIELD@142e88219:MOVSS XMM0,dword ptr [RBP + -0x75]
  - FIELD@142e87ddb:MOVAPS xmmword ptr [RAX + -0x58],XMM6
  - FIELD@142e87de3:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142e8805a:LEA R12,[RBP + -0x45]
  - FIELD@142e88065:LEA R12,[RBP + -0x41]
  - FIELD@142e88049:LEA R12,[RBP + -0x49]
  - FIELD@142e87fde:LEA R12,[RBP + -0x45]
  - FIELD@142e87dd0:LEA RBP,[RAX + -0x4f]
  - FIELD@142e87e4f:MOV dword ptr [RBP + -0x55],EDX
  - FIELD@142e87e7c:LEA RDX,[RBP + -0x69]

#51 SCORE=721 REFS=7 CALLS=19 FIELDS=28
NAME: GetSocketTransform
ADDR: 142b709b0
  - FIELD@142b71052:MOVAPS xmmword ptr [RBP + -0x60],XMM3
  - FIELD@142b70b86:LEA RDX,[RBP + -0x50]
  - FIELD@142b709bc:LEA RBP,[RSP + -0x80]
  - FIELD@142b70f29:MULPS XMM2,xmmword ptr [RBP + -0x30]
  - FIELD@142b70db9:MULPS XMM9,xmmword ptr [RBP + -0x30]
  - FIELD@142b70b9f:MOVAPS XMM6,xmmword ptr [RBP + -0x30]
  - FIELD@142b70add:MOVAPS xmmword ptr [RBP + -0x80],XMM13
  - FIELD@142b70fc7:ADDPS XMM13,xmmword ptr [RBP + -0x40]
  - CALLS:GetBoneTransform
  - CALLS:GetBoneIndex
  - FIELD@142b711a2:MOVAPS xmmword ptr [RBP + -0x80],XMM13
  - FIELD@142b70b7d:CMP EAX,-0x1
  - FIELD@142b70e3f:MULPS XMM12,xmmword ptr [RBP + -0x30]
  - CALLS:FindSocket
  - NAME:SOCKET
  - FIELD@142b70e85:ADDPS XMM2,xmmword ptr [RBP + -0x40]
  - FIELD@142b70cf2:MOVAPS XMM6,xmmword ptr [RBP + -0x50]
  - FIELD@142b70ae2:MOVAPS xmmword ptr [RBP + -0x70],XMM12
  - FIELD@142b70a0f:MOVAPS xmmword ptr [RBP + -0x70],XMM12
  - CALLS:GetRelativeTransform
  - FIELD@142b7105b:CMP EAX,-0x1
  - FIELD@142b710d8:MULPS XMM12,xmmword ptr [RBP + -0x60]
  - FIELD@142b70a0a:MOVAPS xmmword ptr [RBP + -0x80],XMM13
  - FIELD@142b70e89:MOVAPS xmmword ptr [RBP + -0x60],XMM2
  - FIELD@142b70a8b:CMP EDX,-0x1
  - FIELD@142b711ad:MOVAPS xmmword ptr [RBP + -0x70],XMM12
  - FIELD@142b70ab4:CMP EBX,-0x1
  - FIELD@142b70e8d:MOVAPS xmmword ptr [RBP + -0x80],XMM2
  - FIELD@142b70fb2:MULPS XMM12,xmmword ptr [RBP + -0x30]
  - CALLS:GetSocketLocalTransform
  - NAME:TRANSFORM
  - FIELD@142b70e9a:MOVAPS XMM11,xmmword ptr [RBP + -0x50]

#52 SCORE=717 REFS=4 CALLS=51 FIELDS=62
NAME: SuggestProjectileVelocity
ADDR: 14298a010
  - FIELD@14298a01c:LEA RBP,[RAX + -0x1b8]
  - FIELD@14298a05f:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@14298a54a:LEA R9,[RBP + -0x70]
  - FIELD@14298a60c:MOVSS dword ptr [RBP + -0x7c],XMM2
  - NAME:VELOCITY
  - FIELD@14298a02e:MOVAPS xmmword ptr [RAX + -0x58],XMM7
  - FIELD@14298a02a:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@14298a59b:MOVSS dword ptr [RBP + -0x68],XMM0
  - FIELD@14298a5b2:MOVSS dword ptr [RBP + -0x64],XMM1
  - FIELD@14298a03f:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@14298a057:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - FIELD@14298a41e:MOVSS dword ptr [RBP + -0x58],XMM7
  - FIELD@14298a648:MOVSS dword ptr [RBP + -0x7c],XMM5
  - FIELD@14298a423:MOV EAX,dword ptr [RBP + -0x58]
  - FIELD@14298a589:MOVSS dword ptr [RBP + -0x6c],XMM0
  - FIELD@14298a209:MOVSS dword ptr [RBP + -0x78],XMM12
  - FIELD@14298a037:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@14298a093:MOV qword ptr [RBP + -0x20],R8
  - FIELD@14298a632:MOVSS dword ptr [RBP + -0x80],XMM5
  - FIELD@14298a047:MOVAPS xmmword ptr [RAX + -0xa8],XMM12
  - FIELD@14298a577:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@14298a04f:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@14298a602:MOVSS dword ptr [RBP + -0x80],XMM2
  - FIELD@14298a032:MOVAPS xmmword ptr [RAX + -0x78],XMM9
  - FIELD@14298a71b:MOV qword ptr [RBP + -0x48],RDX
  - FIELD@14298a717:MOV qword ptr [RBP + -0x50],RAX

#53 SCORE=713 REFS=2 CALLS=87 FIELDS=0
NAME: GetAttachedToStaticMeshTransform
ADDR: 140a6b350
  - NAME:MESH
  - CALLS:GetInstanceTransform
  - NAME:TRANSFORM

#54 SCORE=709 REFS=4 CALLS=110 FIELDS=154
NAME: InitializeDefaultPawnInputBindings
ADDR: 142930b40
  - FIELD@142930d42:MOV qword ptr [RBP + -0x28],RDI
  - FIELD@142930bb2:MOV qword ptr [RBP + -0x18],RBX
  - FIELD@142930c36:MOV qword ptr [RBP + -0x20],RSI
  - FIELD@142930d3e:MOV qword ptr [RBP + -0x30],RAX
  - NAME:PAWN
  - FIELD@142930bea:LEA RCX,[RBP + -0x30]
  - FIELD@142930ba6:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@142930cba:MOV qword ptr [RBP + -0x28],RDI
  - FIELD@142930d4a:MOV qword ptr [RBP + -0x18],RBX
  - FIELD@142930bae:MOV qword ptr [RBP + -0x20],RSI
  - FIELD@142930bbd:MOV dword ptr [RBP + -0x10],0x3f800000
  - FIELD@142930c3a:MOV qword ptr [RBP + -0x18],RBX
  - FIELD@142930baa:MOV qword ptr [RBP + -0x28],RDI
  - FIELD@142930cb6:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@142930be1:LEA RCX,[RBP + -0x30]
  - FIELD@142930c32:MOV qword ptr [RBP + -0x28],RDI
  - FIELD@142930c2e:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@142930cbe:MOV qword ptr [RBP + -0x20],RSI
  - FIELD@142930ccd:MOV dword ptr [RBP + -0x10],0x3f800000
  - FIELD@142930cfa:LEA RCX,[RBP + -0x30]
  - FIELD@142930cf1:LEA RCX,[RBP + -0x30]
  - FIELD@142930c45:MOV dword ptr [RBP + -0x10],0xbf800000
  - FIELD@142930c69:LEA RCX,[RBP + -0x30]
  - FIELD@142930c72:LEA RCX,[RBP + -0x30]
  - FIELD@142930d46:MOV qword ptr [RBP + -0x20],RSI
  - FIELD@142930cc2:MOV qword ptr [RBP + -0x18],RBX

#55 SCORE=706 REFS=6 CALLS=21 FIELDS=58
NAME: ApplyControlInputToVelocity
ADDR: 1429708c0
  - FIELD@1429709e2:MOVSS XMM8,dword ptr [RBP + -0x65]
  - FIELD@142970909:MOVAPS xmmword ptr [RAX + -0x68],XMM11
  - FIELD@142970904:MOVAPS xmmword ptr [RAX + -0x58],XMM10
  - FIELD@14297099f:MOV dword ptr [RBP + -0x51],EDX
  - FIELD@1429709dd:MOVSS XMM7,dword ptr [RBP + -0x69]
  - FIELD@1429709c2:MOV dword ptr [RBP + -0x61],EAX
  - FIELD@142970ab1:MOVSS XMM8,dword ptr [RBP + -0x65]
  - FIELD@14297099a:MOVSD qword ptr [RBP + -0x59],XMM1
  - FIELD@142970990:MOV dword ptr [RBP + -0x51],EAX
  - FIELD@142970aac:MOVSS XMM7,dword ptr [RBP + -0x69]
  - NAME:VELOCITY
  - FIELD@1429708e0:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@142970993:MOVSD qword ptr [RBP + -0x59],XMM0
  - FIELD@142970917:MOVAPS xmmword ptr [RAX + -0x78],XMM12
  - FIELD@142970aa7:MOVSD qword ptr [RBP + -0x69],XMM0
  - FIELD@1429709bb:LEA RCX,[RBP + -0x59]
  - FIELD@1429709d0:MOVSD qword ptr [RBP + -0x69],XMM1
  - FIELD@1429709c9:MOVSD qword ptr [RBP + -0x69],XMM0
  - FIELD@142970ab7:MOVSS XMM9,dword ptr [RBP + -0x61]
  - FIELD@1429708d8:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@1429709e8:MOVSS XMM9,dword ptr [RBP + -0x61]
  - FIELD@1429708cd:LEA RBP,[RAX + -0x5f]
  - FIELD@1429709d5:MOV dword ptr [RBP + -0x61],EDX
  - FIELD@1429708ff:MOVAPS xmmword ptr [RAX + -0x48],XMM9
  - FIELD@142970aa4:MOV dword ptr [RBP + -0x61],EAX
  - FIELD@1429708dc:MOVAPS xmmword ptr [RAX + -0x28],XMM7

#56 SCORE=702 REFS=4 CALLS=34 FIELDS=35
NAME: EvaluateBoneTransforms
ADDR: 142d43720
  - FIELD@142d43796:MOVAPS xmmword ptr [R11 + -0xa8],XMM12
  - NAME:BONE
  - FIELD@142d43acb:MOV dword ptr [RBP + -0x58],EAX
  - FIELD@142d43a7e:LEA RDX,[RBP + -0x3c]
  - FIELD@142d43772:MOVAPS xmmword ptr [R11 + -0x68],XMM8
  - FIELD@142d43768:MOVAPS xmmword ptr [R11 + -0x48],XMM6
  - FIELD@142d43781:MOVAPS xmmword ptr [R11 + -0x78],XMM9
  - FIELD@142d43757:MOV qword ptr [R11 + -0x30],R14
  - FIELD@142d437d4:LEA RDX,[RBP + -0x30]
  - FIELD@142d43a9f:MOVSS dword ptr [RBP + -0x78],XMM0
  - FIELD@142d437a6:MOVAPS xmmword ptr [R11 + -0xc8],XMM14
  - FIELD@142d43ab6:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@142d43761:MOV qword ptr [R11 + -0x38],R15
  - FIELD@142d4378e:MOVAPS xmmword ptr [R11 + -0x98],XMM11
  - FIELD@142d43748:MOV qword ptr [R11 + -0x20],R12
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d43753:MOV qword ptr [R11 + -0x28],R13
  - FIELD@142d4379e:MOVAPS xmmword ptr [R11 + -0xb8],XMM13
  - FIELD@142d4377d:MOV qword ptr [RBP + -0x68],R12
  - FIELD@142d43ace:LEA RAX,[RBP + -0x60]
  - FIELD@142d43724:LEA RBP,[R11 + -0x128]
  - FIELD@142d43744:MOV qword ptr [R11 + -0x18],RDI
  - FIELD@142d43aa8:MOVSS dword ptr [RBP + -0x74],XMM1
  - FIELD@142d43786:MOVAPS xmmword ptr [R11 + -0x88],XMM10
  - NAME:TRANSFORM
  - FIELD@142d43ab2:LEA RAX,[RBP + -0x78]
  - FIELD@142d437fa:MULPS XMM2,xmmword ptr [RBP + -0x20]
  - FIELD@142d4376d:MOVAPS xmmword ptr [R11 + -0x58],XMM7

#57 SCORE=669 REFS=7 CALLS=76 FIELDS=55
NAME: ComputeSkinnedPositions
ADDR: 142b748a0
  - FIELD@142b74e11:MOVAPS xmmword ptr [RSI + RCX*0x1 + -0x40],XMM9
  - FIELD@142b751fb:MOVAPS XMM2,xmmword ptr [RBP + -0x30]
  - FIELD@142b748a8:LEA RBP,[RSP + -0xf0]
  - FIELD@142b74e17:MOVAPS xmmword ptr [RSI + RCX*0x1 + -0x30],XMM10
  - FIELD@142b751f1:MOVSS XMM0,dword ptr [RBP + -0x54]
  - FIELD@142b751c9:MOV dword ptr [RBP + -0x24],0x3f800000
  - FIELD@142b751c0:MOVSS XMM1,dword ptr [RBP + -0x58]
  - FIELD@142b7552e:MOVSS dword ptr [RBP + -0x20],XMM0
  - FIELD@142b751bb:MOVSS XMM0,dword ptr [RBP + -0x5c]
  - FIELD@142b75500:MOVSD qword ptr [RBP + -0x74],XMM0
  - FIELD@142b75538:MOV dword ptr [RBP + -0x6c],EAX
  - FIELD@142b74e76:MOV qword ptr [RBP + -0x40],RBX
  - FIELD@142b751e9:MOVSS dword ptr [RBP + -0x2c],XMM1
  - FIELD@142b7550a:MOVSS XMM1,dword ptr [RBP + -0x70]
  - FIELD@142b75540:MOVSS dword ptr [RBP + -0x18],XMM0
  - FIELD@142b74e1d:MOVAPS xmmword ptr [RSI + RCX*0x1 + -0x20],XMM11
  - FIELD@142b75513:MOV dword ptr [RBP + -0x14],0x3f800000
  - FIELD@142b74e23:MOVAPS xmmword ptr [RSI + RCX*0x1 + -0x10],XMM12
  - FIELD@142b751e4:MOVSS dword ptr [RBP + -0x30],XMM0
  - FIELD@142b7553b:MOVSS XMM0,dword ptr [RBP + -0x6c]
  - FIELD@142b75505:MOVSS XMM0,dword ptr [RBP + -0x74]
  - FIELD@142b75533:MOVSS dword ptr [RBP + -0x1c],XMM1
  - FIELD@142b751f6:MOVSS dword ptr [RBP + -0x28],XMM0
  - NAME:POSITION
  - FIELD@142b751b6:MOVSD qword ptr [RBP + -0x5c],XMM0
  - FIELD@142b751ee:MOV dword ptr [RBP + -0x54],EAX

#58 SCORE=667 REFS=2 CALLS=267 FIELDS=0
NAME: UpdateLocation
ADDR: 140aa1e00
  - CALLS:SetActorLocation
  - NAME:LOCATION

#59 SCORE=661 REFS=382 CALLS=2025 FIELDS=0
NAME: Z_Construct_UClass_APrimalCharacter
ADDR: 141c9a410
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetInterpolatedRotation_NonFlattened
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBP_OverrideTerminalVelocity
  - CALLS:FDetermineBitMask_APrimalCharacter_bBPManagedFPVViewLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPNetAddCharacterMovementImpulse
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBPOverrideFlyingVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPGetFPVViewLocation
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBPAdjustCharacterMovementImpulse
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPGetAddForwardVelocityOnJump
  - CALLS:FDetermineBitMask_APrimalCharacter_bPreventMovement
  - CALLS:Z_Construct_UEnum_UEngineTypes_EMovementMode
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPOnMovementModeChangedNotify
  - CALLS:Z_Construct_UFunction_APrimalCharacter_EnableTurnToFaceRotation
  - CALLS:FDetermineBitMask_APrimalCharacter_bBPLimitPlayerRotation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetDefaultMovementSpeed
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBPOnMovementModeChangedNotify
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPAdjustCharacterMovementImpulse
  - CALLS:Z_Construct_UFunction_APrimalCharacter_NetSetMovementModeSimulatedInternal
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPLimitPlayerRotation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_NetSetCharacterMovementVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetCapsuleBottomLocation
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBPOverrideCharacterNewFallVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPOverrideCharacterNewFallVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_OverrideCameraTargetOriginLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetBasedMovementComponent
  - CALLS:FDetermineBitMask_APrimalCharacter_bPreventTargetingAndMovement
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPNetSetMovementMode
  - CALLS:Z_Construct_UFunction_APrimalCharacter_TickMovementComponent
  - CALLS:Z_Construct_UFunction_APrimalCharacter_OnRep_RagdollPositions
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPNetSetCharacterMovementVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetFloatingHUDLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetPrimalCharMovementMode
  - CALLS:FDetermineBitMask_APrimalCharacter_bBPCameraRotationFinal
  - CALLS:Z_Construct_UClass_ACharacter
  - CALLS:Z_Construct_UFunction_APrimalCharacter_NetAddCharacterMovementImpulse
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPOverrideFlyingVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetSocketLocation
  - CALLS:FDetermineBitMask_APrimalCharacter_bIgnoreCorpseDecompositionMultipliers
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BP_OverrideTerminalVelocity
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetCharacterViewLocationAndDirection
  - CALLS:FDetermineBitMask_APrimalCharacter_bUseBP_OverrideCameraTargetOriginLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_AttachedToOtherCharacterUpdateWorldLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPOverrideFPVViewLocation
  - NAME:CHARACTER
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BP_OverrideCameraTargetOriginLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_GetCapsuleTopLocation
  - CALLS:Z_Construct_UFunction_APrimalCharacter_BPCameraRotationFinal

#60 SCORE=656 REFS=2 CALLS=48 FIELDS=0
NAME: UpdateClimbingTargetLocation
ADDR: 140176a70
  - CALLS:GetActorForwardVector
  - NAME:LOCATION
  - CALLS:GetActorUpVector
  - CALLS:GetActorRightVector

#61 SCORE=649 REFS=4 CALLS=108 FIELDS=137
NAME: Z_Construct_UClass_UParticleModuleAttractorPoint
ADDR: 1435e31e0
  - FIELD@1435e3231:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1435e3207:MOV qword ptr [R11 + -0x28],R15
  - CALLS:GetPrivateStaticClassBody<UParticleModuleAttractorPoint>
  - FIELD@1435e3282:LEA RCX,[RBP + -0x78]
  - FIELD@1435e334b:MOV word ptr [RBP + -0x18],0x100
  - FIELD@1435e31e4:LEA RBP,[R11 + -0x158]
  - FIELD@1435e332a:MOV ESI,dword ptr [RBP + -0x6c]
  - FIELD@1435e3419:MOV qword ptr [RBP + -0x38],RAX
  - FIELD@1435e33ad:MOV byte ptr [RBP + -0x16],R15B
  - NAME:ACTOR
  - FIELD@1435e341d:MOV qword ptr [RBP + -0x30],R15
  - FIELD@1435e34a3:MOV ESI,dword ptr [RBP + -0x2c]
  - FIELD@1435e34a6:MOV R14D,dword ptr [RBP + -0x30]
  - FIELD@1435e3351:MOV byte ptr [RBP + -0x16],BL
  - FIELD@1435e3354:MOV qword ptr [RBP + -0x10],R15
  - FIELD@1435e33fd:LEA RCX,[RBP + -0x28]
  - FIELD@1435e332d:MOV R14D,dword ptr [RBP + -0x70]
  - FIELD@1435e3374:MOV RAX,qword ptr [RBP + -0x28]
  - FIELD@1435e34ad:MOVDQU xmmword ptr [RBP + -0x28],XMM0
  - FIELD@1435e328b:MOV qword ptr [RBP + -0x78],RAX
  - FIELD@1435e34bf:MOV word ptr [RBP + -0x18],0x100
  - FIELD@1435e3229:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1435e328f:MOV qword ptr [RBP + -0x70],R15
  - FIELD@1435e322d:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1435e33a9:MOV qword ptr [RBP + -0x28],RDI
  - FIELD@1435e3410:LEA RCX,[RBP + -0x38]
  - FIELD@1435e3334:MOVDQU xmmword ptr [RBP + -0x28],XMM0

#62 SCORE=648 REFS=4 CALLS=14 FIELDS=20
NAME: SpawnEx
ADDR: 142e96030
  - FIELD@142e962b0:MULPS XMM1,xmmword ptr [RBP + -0x70]
  - FIELD@142e96b9a:MOVAPS XMM10,xmmword ptr [R11 + -0x60]
  - FIELD@142e96065:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142e96b7c:MOVAPS XMM7,xmmword ptr [R11 + -0x30]
  - NAME:PAWN
  - FIELD@142e9603f:LEA RBP,[RAX + -0x48]
  - FIELD@142e96b77:MOVAPS XMM6,xmmword ptr [R11 + -0x20]
  - FIELD@142e96073:MOV qword ptr [RAX + -0x20],RSI
  - FIELD@142e9686d:MOVSS dword ptr [RBP + -0x78],XMM8
  - FIELD@142e96604:MOV dword ptr [RBP + -0x74],0x0
  - FIELD@142e9685c:MOVSS dword ptr [RBP + -0x7c],XMM6
  - FIELD@142e96060:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - FIELD@142e9687a:MULPS XMM0,xmmword ptr [RBP + -0x80]
  - FIELD@142e962ca:MULPS XMM2,xmmword ptr [RBP + -0x80]
  - FIELD@142e96b81:MOVAPS XMM8,xmmword ptr [R11 + -0x40]
  - FIELD@142e9604e:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142e96077:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - FIELD@142e96856:MOVSS dword ptr [RBP + -0x80],XMM10
  - FIELD@142e96b95:MOVAPS XMM9,xmmword ptr [R11 + -0x50]
  - FIELD@142e9604a:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142e96052:MOVAPS xmmword ptr [RAX + -0x58],XMM8

#63 SCORE=643 REFS=2 CALLS=58 FIELDS=0
NAME: TemplateAllowActorSpawn
ADDR: 1407c91d0
  - CALLS:SpawnEmitterAtLocation
  - CALLS:PlaySoundAtLocation
  - CALLS:SpawnDecalAttached
  - CALLS:SpawnEmitterAttached
  - NAME:ACTOR
  - CALLS:TemplateAllowActorSpawn
  - CALLS:Rotation
  - CALLS:SpawnDecalAtLocation
  - NAME:PAWN
  - CALLS:FRotationMatrix

#64 SCORE=629 REFS=2 CALLS=278 FIELDS=2
NAME: GetLandingLocation
ADDR: 1405fefa0
  - FIELD@140601a95:CMP EAX,-0x1
  - NAME:LOCATION
  - FIELD@140601b4e:CMP EAX,-0x1
  - CALLS:BPOverrideLandingLocation

#65 SCORE=627 REFS=8 CALLS=21 FIELDS=59
NAME: GetSphereMesh
ADDR: 142ae62d0
  - FIELD@142ae6473:MOV dword ptr [RBP + -0x68],0x0
  - FIELD@142ae6464:MOV dword ptr [RBP + -0x64],0x0
  - FIELD@142ae62fa:MOV qword ptr [RAX + -0x20],RDI
  - FIELD@142ae6452:MOVSS dword ptr [RBP + -0x5c],XMM7
  - FIELD@142ae62e4:LEA RBP,[RAX + -0x198]
  - FIELD@142ae646b:MOV qword ptr [RBP + -0x70],0x3f800000
  - FIELD@142ae631e:MOVAPS xmmword ptr [RAX + -0x78],XMM8
  - FIELD@142ae6316:MOVAPS xmmword ptr [RAX + -0x58],XMM6
  - FIELD@142ae62fe:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142ae645f:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@142ae644a:LEA RDX,[RBP + -0x70]
  - FIELD@142ae6306:MOV qword ptr [RAX + -0x38],R14
  - FIELD@142ae6302:MOV qword ptr [RAX + -0x30],R13
  - FIELD@142ae62f2:MOV qword ptr [RAX + -0x10],RBX
  - NAME:MESH
  - FIELD@142ae6446:LEA R8,[RBP + -0x64]
  - FIELD@142ae6415:MOV dword ptr [RDI + -0x8],EAX
  - FIELD@142ae62f6:MOV qword ptr [RAX + -0x18],RSI
  - FIELD@142ae644e:LEA RCX,[RDI + -0x8]
  - FIELD@142ae630a:MOV qword ptr [RAX + -0x40],R15
  - FIELD@142ae64c0:MOV dword ptr [RBP + -0x48],0x0
  - FIELD@142ae6326:MOVAPS xmmword ptr [RAX + -0x88],XMM9
  - FIELD@142ae631a:MOVAPS xmmword ptr [RAX + -0x68],XMM7
  - FIELD@142ae6438:MOVSS dword ptr [RDI + -0x4],XMM7
  - FIELD@142ae632e:MOVAPS xmmword ptr [RAX + -0xe8],XMM15
  - CALLS:GetMesh
  - FIELD@142ae6442:LEA R9,[RDI + -0x8]

#66 SCORE=624 REFS=3 CALLS=237 FIELDS=3
NAME: GetLandingLocation
ADDR: 1406ba860
  - NAME:LOCATION
  - FIELD@1406bd60b:CMP dword ptr [RSP + 0x90],-0x1
  - FIELD@1406be36a:CMP EAX,-0x1
  - FIELD@1406be2b1:CMP EAX,-0x1

#67 SCORE=620 REFS=4 CALLS=28 FIELDS=47
NAME: EvaluateBoneTransforms
ADDR: 142d26730
  - FIELD@142d268aa:MOVAPS XMM2,xmmword ptr [RBP + -0x60]
  - FIELD@142d269cf:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@142d26848:LEA RDX,[RBP + -0x60]
  - NAME:BONE
  - FIELD@142d26cb7:CMP EAX,-0x1
  - FIELD@142d26b38:LEA RAX,[RBP + -0x80]
  - FIELD@142d26991:MOVSS XMM1,dword ptr [RBP + -0x78]
  - FIELD@142d269c8:LEA RDX,[RBP + -0x60]
  - CALLS:GetLocalSpaceTransform
  - FIELD@142d26b9b:MOVSS XMM1,dword ptr [RBP + -0x78]
  - FIELD@142d26bb0:MOVSS XMM0,dword ptr [RBP + -0x80]
  - FIELD@142d26aa8:LEA RSI,[RBP + -0x70]
  - FIELD@142d26738:LEA RBP,[RSP + -0xa0]
  - FIELD@142d26751:MOV qword ptr [RBP + -0x20],RAX
  - FIELD@142d269fa:MOV dword ptr [RBP + -0x78],EAX
  - FIELD@142d26c9d:MOVAPS XMM15,xmmword ptr [RBP + -0x40]
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d26972:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@142d2696a:MOVAPS XMM0,xmmword ptr [RBP + -0x40]
  - FIELD@142d26c94:MOVAPS XMM6,xmmword ptr [RBP + -0x60]
  - FIELD@142d269ef:MOVSD qword ptr [RBP + -0x80],XMM0
  - FIELD@142d26c3d:MOVAPS XMM2,xmmword ptr [RBP + -0x60]
  - FIELD@142d26918:MOVAPS XMM2,xmmword ptr [RBP + -0x50]
  - FIELD@142d26b42:LEA RCX,[RBP + -0x78]
  - NAME:TRANSFORM
  - FIELD@142d2694c:MOVSS XMM2,dword ptr [RBP + -0x48]
  - FIELD@142d26b96:MOVSS XMM0,dword ptr [RBP + -0x7c]
  - FIELD@142d26c98:MOVAPS XMM14,xmmword ptr [RBP + -0x50]
  - FIELD@142d26b3e:LEA RAX,[RBP + -0x7c]

#68 SCORE=619 REFS=11 CALLS=97 FIELDS=113
NAME: RootDir
ADDR: 1420af3f0
  - FIELD@1420af52b:MOV qword ptr [RBP + -0x28],R14
  - FIELD@1420af55d:LEA RCX,[RBP + -0x28]
  - FIELD@1420af52f:MOV dword ptr [RBP + -0x1c],R14D
  - FIELD@1420af47c:MOV qword ptr [RBP + -0x30],R14
  - FIELD@1420af5b1:MOV word ptr [RBX + RDI*0x2 + -0x2],R14W
  - FIELD@1420af472:MOV qword ptr [RBP + -0x38],R14
  - FIELD@1420af5b7:LEA RDX,[RBP + -0x28]
  - FIELD@1420af56a:MOV dword ptr [RBP + -0x1c],EAX
  - FIELD@1420af4c6:MOV R13,qword ptr [RBP + -0x38]
  - FIELD@1420af510:CMP EAX,-0x1
  - FIELD@1420af4b1:LEA RCX,[RBP + -0x38]
  - CALLS:ResizeAllocation
  - FIELD@1420af54b:MOV dword ptr [RBP + -0x20],ECX
  - FIELD@1420af5c4:MOV RBX,qword ptr [RBP + -0x28]
  - FIELD@1420af4be:MOV dword ptr [RBP + -0x2c],EAX
  - FIELD@1420af5ee:LEA RDX,[RBP + -0x38]
  - FIELD@1420af520:LEA EBX,[RDI + -0x1]
  - FIELD@1420af5a4:LEA R8,[RDI + -0x1]
  - FIELD@1420af5f2:LEA RCX,[RBP + -0x28]
  - NAME:ROOT
  - CALLS:EngineDir
  - FIELD@1420af48a:OR RBX,-0x1
  - FIELD@1420af59d:MOV RBX,qword ptr [RBP + -0x28]
  - FIELD@1420af4ca:MOV EDI,dword ptr [RBP + -0x30]
  - CALLS:ConvertRelativePathToFull
  - FIELD@1420af572:CMP dword ptr [RBP + -0x20],R12D
  - FIELD@1420af49d:MOV dword ptr [RBP + -0x30],EBX
  - FIELD@1420af5bb:LEA RCX,[RBP + -0x38]
  - FIELD@1420af5fb:LEA RCX,[RBP + -0x38]

#69 SCORE=619 REFS=12 CALLS=49 FIELDS=38
NAME: OnRep_ReplicatedBasedMovement
ADDR: 1428b6df0
  - FIELD@1428b73a4:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@1428b75f1:MOVSS dword ptr [RBP + -0x4c],XMM7
  - FIELD@1428b750d:MOV dword ptr [RBP + -0x44],EDI
  - FIELD@1428b6fe5:MOV qword ptr [RBP + -0x70],R13
  - FIELD@1428b7536:MOV dword ptr [RBP + -0x24],EDI
  - FIELD@1428b73ae:MOVAPS XMM8,xmmword ptr [RBP + -0x60]
  - FIELD@1428b75c8:MOVSS dword ptr [RBP + -0x40],XMM1
  - FIELD@1428b73a9:MOVSS dword ptr [RBP + -0x5c],XMM1
  - CALLS:SetActorLocationAndRotation
  - FIELD@1428b75e7:MOVSS dword ptr [RBP + -0x20],XMM0
  - FIELD@1428b7377:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@1428b7539:MOV dword ptr [RBP + -0x14],0x3f800000
  - NAME:MOVEMENT
  - FIELD@1428b75b2:MOVSS dword ptr [RBP + -0x50],XMM0
  - FIELD@1428b72a9:LEA R9,[RBP + -0x80]
  - FIELD@1428b7100:MOV qword ptr [RBP + -0x70],R13
  - FIELD@1428b7041:MOVUPS XMM0,xmmword ptr [RBP + -0x70]
  - FIELD@1428b7104:MOV dword ptr [RBP + -0x68],EDI
  - FIELD@1428b7603:MOVSS dword ptr [RBP + -0x2c],XMM1
  - FIELD@1428b6fe9:MOV dword ptr [RBP + -0x68],EDI
  - CALLS:TBaseDynamicDelegate_FiveParams<void,AActor_*___ptr64,UPrimitiveComponent_*___ptr64,int,bool,FHitResult_const_&___ptr64,FWeakObjectPtr>
  - FIELD@1428b75d5:MOVSS dword ptr [RBP + -0x30],XMM0
  - FIELD@1428b7318:MOV dword ptr [RBP + -0x54],0x3f800000
  - CALLS:GetMovementBaseTransform
  - FIELD@1428b72ca:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@1428b7510:MOV dword ptr [RBP + -0x34],EDI
  - FIELD@1428b715c:MOVUPS XMM0,xmmword ptr [RBP + -0x70]
  - FIELD@1428b6df3:LEA RBP,[RSP + -0x1d8]
  - FIELD@1428b72f0:MOVAPS XMM0,xmmword ptr [RBP + -0x80]

#70 SCORE=613 REFS=11 CALLS=107 FIELDS=91
NAME: Z_Construct_UClass_UPawnSensingComponent
ADDR: 1426cc000
  - FIELD@1426cc04e:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1426cc44d:LEA RCX,[RBP + -0x80]
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_GetPeripheralVisionAngle
  - FIELD@1426cc202:MOVDQU xmmword ptr [RBP + -0x80],XMM0
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_SetSensingInterval
  - FIELD@1426cc312:MOV word ptr [RBP + -0x70],0x100
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_SetSensingUpdatesEnabled
  - FIELD@1426cc056:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1426cc21d:MOV word ptr [RBP + -0x70],0x100
  - FIELD@1426cc4de:MOV word ptr [RBP + -0x70],0x100
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_SeePawnDelegate__DelegateSignature
  - NAME:PAWN
  - FIELD@1426cc223:MOV byte ptr [RBP + -0x6e],DIL
  - FIELD@1426cc34b:LEA RCX,[RBP + -0x80]
  - CALLS:GetPrivateStaticClassBody<UPawnSensingComponent>
  - CALLS:Z_Construct_UClass_UActorComponent
  - FIELD@1426cc004:LEA RBP,[R11 + -0xf8]
  - FIELD@1426cc318:MOV byte ptr [RBP + -0x6e],0x1
  - FIELD@1426cc256:LEA RCX,[RBP + -0x80]
  - FIELD@1426cc4e4:MOV byte ptr [RBP + -0x6e],0x1
  - FIELD@1426cc2f5:LEA RDX,[RBP + -0x80]
  - FIELD@1426cc027:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1426cc3e3:MOV word ptr [RBP + -0x70],0x100
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_SetPeripheralVisionAngle
  - FIELD@1426cc1fe:LEA RDX,[RBP + -0x80]
  - FIELD@1426cc227:MOV qword ptr [RBP + -0x68],R15
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_HearNoiseDelegate__DelegateSignature
  - FIELD@1426cc3e9:MOV byte ptr [RBP + -0x6e],0x1
  - FIELD@1426cc31c:MOV qword ptr [RBP + -0x68],R15
  - FIELD@1426cc41f:LEA RDX,[RBP + -0x80]
  - FIELD@1426cc3ed:MOVDQU xmmword ptr [RBP + -0x80],XMM0
  - FIELD@1426cc052:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1426cc2f9:MOVDQU xmmword ptr [RBP + -0x80],XMM0
  - CALLS:Z_Construct_UFunction_UPawnSensingComponent_GetPeripheralVisionCosine
  - FIELD@1426cc3f9:MOV qword ptr [RBP + -0x68],R15

#71 SCORE=609 REFS=7 CALLS=31 FIELDS=0
NAME: GetProjectileSpawnTransform
ADDR: 141248eb0
  - CALLS:GetMuzzleLocation
  - CALLS:GetCameraDamageStartLocation
  - CALLS:Rotation
  - NAME:TRANSFORM
  - NAME:PAWN

#72 SCORE=605 REFS=4 CALLS=13 FIELDS=25
NAME: UpdateTransforms
ADDR: 142e4f380
  - FIELD@142e4f4a9:MOVAPS xmmword ptr [RBP + -0x80],XMM4
  - FIELD@142e4f4dd:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@142e4f3c4:MOVAPS xmmword ptr [RAX + -0x98],XMM14
  - FIELD@142e4f3ad:MOVAPS xmmword ptr [RAX + -0x58],XMM10
  - FIELD@142e4fad2:MOVAPS XMM7,xmmword ptr [R11 + -0x20]
  - FIELD@142e4f4e1:MOVAPS xmmword ptr [RBP + -0x70],XMM1
  - FIELD@142e4f4b1:MOVAPS xmmword ptr [RBP + -0x70],XMM6
  - FIELD@142e4faeb:MOVAPS XMM12,xmmword ptr [R11 + -0x70]
  - FIELD@142e4f39c:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@142e4facd:MOVAPS XMM6,xmmword ptr [R11 + -0x10]
  - FIELD@142e4fad7:MOVAPS XMM8,xmmword ptr [R11 + -0x30]
  - FIELD@142e4faf0:MOVAPS XMM13,xmmword ptr [R11 + -0x80]
  - FIELD@142e4f398:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@142e4faf5:MOVAPS XMM14,xmmword ptr [R11 + -0x90]
  - FIELD@142e4f3a3:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@142e4f388:LEA RBP,[RAX + -0x48]
  - FIELD@142e4f3a8:MOVAPS xmmword ptr [RAX + -0x48],XMM9
  - FIELD@142e4f3b2:MOVAPS xmmword ptr [RAX + -0x68],XMM11
  - FIELD@142e4f3b7:MOVAPS xmmword ptr [RAX + -0x78],XMM12
  - FIELD@142e4f3bc:MOVAPS xmmword ptr [RAX + -0x88],XMM13
  - FIELD@142e4fafd:MOVAPS XMM15,xmmword ptr [R11 + -0xa0]
  - FIELD@142e4f3cc:MOVAPS xmmword ptr [RAX + -0xa8],XMM15
  - FIELD@142e4fadc:MOVAPS XMM9,xmmword ptr [R11 + -0x40]
  - NAME:TRANSFORM
  - FIELD@142e4fae6:MOVAPS XMM11,xmmword ptr [R11 + -0x60]
  - FIELD@142e4fae1:MOVAPS XMM10,xmmword ptr [R11 + -0x50]

#73 SCORE=601 REFS=5 CALLS=48 FIELDS=119
NAME: PopulateTabSpawnerMenu
ADDR: 1423083c0
  - FIELD@14230846b:LEA RCX,[RBP + -0x19]
  - FIELD@14230852a:LEA EAX,[RCX + -0x1]
  - NAME:PAWN
  - FIELD@142308489:MOV dword ptr [RBP + -0x59],EBX
  - FIELD@142308578:MOVUPS xmmword ptr [RBP + -0x1],XMM0
  - CALLS:MakeSpawnerMenuEntry
  - FIELD@142308442:MOV qword ptr [RBP + -0x11],RAX
  - FIELD@142308501:MOV dword ptr [RBP + -0x49],0xffffffff
  - FIELD@142308550:MOV dword ptr [RBP + -0x45],EDI
  - FIELD@142308553:MOVUPS XMM5,xmmword ptr [RBP + -0x49]
  - FIELD@142308518:MOV dword ptr [RBP + -0x41],EDI
  - CALLS:PopulateTabSpawnerMenu_Helper
  - FIELD@142308580:MOVUPS XMM3,xmmword ptr [RBP + -0x9]
  - FIELD@142308494:MOV dword ptr [RBP + -0x49],0xffffffff
  - FIELD@14230849b:MOV qword ptr [RBP + -0x45],0x0
  - FIELD@142308534:MOV dword ptr [RBP + -0x55],EAX
  - FIELD@14230859b:MOVUPS xmmword ptr [RBP + -0x59],XMM3
  - FIELD@1423084e7:LEA EAX,[R9 + -0x1]
  - FIELD@14230848c:MOV dword ptr [RBP + -0x55],R12D
  - FIELD@14230855b:MOV qword ptr [RBP + -0x9],R15
  - FIELD@142308557:MOVUPS XMM0,xmmword ptr [RBP + -0x59]
  - FIELD@142308515:MOV dword ptr [RBP + -0x59],EBX
  - FIELD@1423083df:LEA RBP,[RSP + -0x27]
  - FIELD@142308490:MOV qword ptr [RBP + -0x51],R14
  - FIELD@142308542:MOV dword ptr [RBP + -0x45],R9D
  - FIELD@142308567:MOV word ptr [RBP + -0x21],0x0
  - FIELD@142308413:MOV qword ptr [RBP + -0x19],RBX
  - FIELD@142308563:MOV qword ptr [RBP + -0x29],R15

#74 SCORE=600 REFS=6 CALLS=85 FIELDS=103
NAME: Z_Construct_UClass_UParticleModuleLocationPrimitiveBase
ADDR: 1435f70f0
  - FIELD@1435f74ee:MOV ESI,dword ptr [RBP + -0x4c]
  - FIELD@1435f7399:MOV qword ptr [RBP + -0x30],R15
  - FIELD@1435f72a8:MOV byte ptr [RBP + -0x36],R15B
  - FIELD@1435f72ee:LEA RCX,[RBP + -0x48]
  - FIELD@1435f7235:MOV word ptr [RBP + -0x38],0x100
  - FIELD@1435f7389:MOV byte ptr [RBP + -0x36],0x1
  - CALLS:Z_Construct_UClass_UParticleModuleLocationBase
  - FIELD@1435f73c2:MOV RCX,qword ptr [RBP + -0x48]
  - CALLS:GetPrivateStaticClassBody<UParticleModuleLocationPrimitiveBase>
  - NAME:LOCATION
  - FIELD@1435f73f3:MOV qword ptr [RBP + -0x48],RDI
  - FIELD@1435f7117:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1435f7461:MOV qword ptr [RBP + -0x50],R15
  - FIELD@1435f738d:MOVDQU xmmword ptr [RBP + -0x48],XMM0
  - FIELD@1435f72a4:MOV qword ptr [RBP + -0x48],RDI
  - FIELD@1435f70f4:LEA RBP,[R11 + -0x138]
  - FIELD@1435f7141:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1435f723b:MOV qword ptr [RBP + -0x30],R15
  - FIELD@1435f73f7:MOV byte ptr [RBP + -0x36],R15B
  - FIELD@1435f723f:MOVDQU xmmword ptr [RBP + -0x48],XMM0
  - FIELD@1435f7273:MOV RCX,qword ptr [RBP + -0x48]
  - FIELD@1435f713d:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1435f7441:LEA RCX,[RBP + -0x48]
  - FIELD@1435f7253:MOV byte ptr [RBP + -0x36],BL
  - FIELD@1435f7383:MOV word ptr [RBP + -0x38],0x100
  - FIELD@1435f7454:LEA RCX,[RBP + -0x58]
  - FIELD@1435f745d:MOV qword ptr [RBP + -0x58],RAX
  - FIELD@1435f7139:MOV qword ptr [R11 + -0x10],R12

#75 SCORE=591 REFS=5 CALLS=172 FIELDS=0
NAME: StaticRegisterNativesUSceneComponent
ADDR: 142f936e0
  - CALLS:execAddLocalTransform
  - CALLS:execK2_GetComponentRotation
  - CALLS:execGetSocketLocation
  - CALLS:execAddWorldTransform
  - CALLS:execSetRelativeScale3D
  - CALLS:execGetSocketRotation
  - CALLS:execK2_GetComponentToWorld
  - CALLS:execGetSocketTransform
  - CALLS:execAddLocalRotation
  - CALLS:execSetWorldLocation
  - CALLS:execSetRelativeLocation
  - STRING_REF:ComponentToWorld
  - CALLS:execAddWorldRotation
  - CALLS:execResetRelativeTransform
  - CALLS:execSetRelativeLocationAndRotation
  - CALLS:execGetWorldLocation
  - CALLS:execSetWorldLocationAndRotation
  - CALLS:execAddRelativeLocation
  - CALLS:execOnRep_Transform
  - SCENE_COMPONENT
  - CALLS:execSetRelativeTransform
  - CALLS:execAddRelativeRotation
  - CALLS:execSetRelativeRotation
  - CALLS:execSetWorldTransform
  - STRING_REF:RelativeLocation
  - CALLS:execGetRelativeTransform
  - CALLS:execGetComponentVelocity
  - CALLS:execSetWorldRotation

#76 SCORE=589 REFS=4 CALLS=116 FIELDS=0
NAME: CanSpawnOverWater
ADDR: 1408cd660
  - CALLS:GetLocationPhysicsVolume
  - CALLS:Rotation
  - NAME:PAWN

#77 SCORE=585 REFS=7 CALLS=9 FIELDS=20
NAME: getRelativeLinearVelocity
ADDR: 143be9440
  - FIELD@143be9a63:MOVAPS XMM12,xmmword ptr [R11 + -0x78]
  - FIELD@143be9474:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@143be9a3f:MOVAPS XMM11,xmmword ptr [R11 + -0x68]
  - FIELD@143be9a49:MOVAPS XMM10,xmmword ptr [R11 + -0x58]
  - FIELD@143be9a2d:MOVAPS XMM8,xmmword ptr [R11 + -0x38]
  - FIELD@143be9452:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@143be9481:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@143be9489:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - NAME:RELATIVE
  - FIELD@143be9479:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@143be99a4:MOVAPS XMM13,xmmword ptr [R11 + -0x88]
  - FIELD@143be99ac:MOVAPS XMM14,xmmword ptr [R11 + -0x98]
  - FIELD@143be9491:MOVAPS xmmword ptr [RAX + -0xb8],XMM14
  - FIELD@143be9a58:MOVAPS XMM9,xmmword ptr [R11 + -0x48]
  - NAME:VELOCITY
  - FIELD@143be9a08:MOVAPS XMM7,xmmword ptr [R11 + -0x28]
  - FIELD@143be9499:MOVAPS xmmword ptr [RAX + -0xc8],XMM15
  - FIELD@143be99b4:MOVAPS XMM15,xmmword ptr [R11 + -0xa8]
  - FIELD@143be9a23:MOVAPS XMM6,xmmword ptr [R11 + -0x18]
  - FIELD@143be9456:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@143be944e:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@143be946f:MOVAPS xmmword ptr [RAX + -0x68],XMM9

#78 SCORE=582 REFS=5 CALLS=19 FIELDS=1
NAME: GetParticleLocation
ADDR: 142e8d470
  - NAME:LOCATION
  - FIELD@142e8d47b:LEA RBP,[RSP + -0x8]

#79 SCORE=579 REFS=2 CALLS=46 FIELDS=0
NAME: FindValidLocationNextToTarget
ADDR: 1415b9130
  - NAME:LOCATION

#80 SCORE=575 REFS=53 CALLS=225 FIELDS=44
NAME: Z_Construct_UClass_UActorComponent
ADDR: 143010a40
  - FIELD@143011478:MOV ESI,dword ptr [RBP + -0x64]
  - CALLS:Z_Construct_UScriptStruct_UEngineBaseTypes_FActorComponentTickFunction
  - FIELD@143011782:MOV ESI,dword ptr [RBP + -0x44]
  - FIELD@1430113ee:MOV qword ptr [RBP + -0x70],RAX
  - FIELD@1430116ef:LEA RCX,[RBP + -0x50]
  - FIELD@1430116f8:MOV qword ptr [RBP + -0x50],RAX
  - CALLS:Z_Construct_UFunction_UActorComponent_RemoveTickPrerequisiteActor
  - CALLS:Z_Construct_UFunction_UActorComponent_Activate
  - CALLS:Z_Construct_UFunction_UActorComponent_SetActive
  - CALLS:Z_Construct_UFunction_UActorComponent_SetComponentTickEnabled
  - FIELD@143010a8d:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_UActorComponent_AddTickPrerequisiteComponent
  - NAME:ACTOR
  - FIELD@143011577:MOV qword ptr [RBP + -0x8],R15
  - FIELD@143010a44:LEA RBP,[R11 + -0x2f8]
  - FIELD@143010a67:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_UActorComponent_IsActive
  - FIELD@143010d37:LEA RCX,[RBP + -0x30]
  - FIELD@143011600:MOV R14D,dword ptr [RBP + -0x8]
  - FIELD@143011d4e:LEA RCX,[RBP + -0x80]
  - CALLS:Z_Construct_UFunction_UActorComponent_ComponentHasTag
  - CALLS:Z_Construct_UFunction_UActorComponent_SetIsReplicated
  - FIELD@143011785:MOV R14D,dword ptr [RBP + -0x48]
  - FIELD@1430115fd:MOV ESI,dword ptr [RBP + -0x4]
  - CALLS:Z_Construct_UFunction_UActorComponent_GetOwner
  - FIELD@1430113e5:LEA RCX,[RBP + -0x70]
  - CALLS:GetPrivateStaticClassBody<UActorComponent>
  - FIELD@143010dea:MOV R14D,dword ptr [RBP + -0x28]
  - CALLS:Z_Construct_UFunction_UActorComponent_RemoveTickPrerequisiteComponent
  - CALLS:Z_Construct_UFunction_UActorComponent_BPOnComponentTick
  - FIELD@143010a89:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1430113f2:MOV qword ptr [RBP + -0x68],R15
  - CALLS:Z_Construct_UFunction_UActorComponent_BPTickComponent
  - CALLS:Z_Construct_UFunction_UActorComponent_GetWorld
  - FIELD@143010d40:MOV qword ptr [RBP + -0x28],R15
  - FIELD@14301147b:MOV R14D,dword ptr [RBP + -0x68]
  - CALLS:Z_Construct_UFunction_UActorComponent_AddTickPrerequisiteActor
  - CALLS:Z_Construct_UFunction_UActorComponent_K2_DestroyComponent
  - FIELD@143010d44:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@143011573:MOV qword ptr [RBP + -0x10],RAX
  - FIELD@1430116fc:MOV qword ptr [RBP + -0x48],R15
  - FIELD@143010de7:MOV ESI,dword ptr [RBP + -0x24]
  - FIELD@14301156a:LEA RCX,[RBP + -0x10]

#81 SCORE=573 REFS=5 CALLS=43 FIELDS=20
NAME: GetBoneAtomRotation
ADDR: 142cf8790
  - FIELD@142cf87be:MOV qword ptr [RAX + -0x20],RDI
  - FIELD@142cf88ce:LEA EBX,[R13 + -0x1]
  - FIELD@142cf87ac:CMP R8D,-0x1
  - FIELD@142cf87ef:MOVAPS xmmword ptr [RAX + -0xc8],XMM13
  - FIELD@142cf8a95:LEA EDI,[R8 + -0x1]
  - FIELD@142cf87b6:MOV qword ptr [RAX + -0x10],RBX
  - FIELD@142cf87ca:MOV qword ptr [RAX + -0x38],R14
  - NAME:BONE
  - FIELD@142cf87a1:LEA RBP,[RAX + -0x48]
  - FIELD@142cf87db:MOVAPS xmmword ptr [RAX + -0x58],XMM6
  - FIELD@142cf87c6:MOV qword ptr [RAX + -0x30],R13
  - NAME:ROTATION
  - FIELD@142cf8a25:LEA EDI,[R8 + -0x1]
  - FIELD@142cf87e7:MOVAPS xmmword ptr [RAX + -0xb8],XMM12
  - FIELD@142cf8984:LEA EAX,[RCX + -0x1]
  - FIELD@142cf87c2:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142cf87ce:MOV qword ptr [RAX + -0x40],R15
  - FIELD@142cf897a:LEA EDI,[R13 + -0x1]
  - FIELD@142cf89b5:LEA EDX,[RAX + -0x1]
  - FIELD@142cf8949:AND RSI,-0x4
  - FIELD@142cf87df:MOVAPS xmmword ptr [RAX + -0xa8],XMM11
  - FIELD@142cf87ba:MOV qword ptr [RAX + -0x18],RSI

#82 SCORE=570 REFS=9 CALLS=25 FIELDS=28
NAME: GetAudioListenerPosition
ADDR: 142ac1340
  - FIELD@142ac1baa:MOVAPS XMM7,xmmword ptr [R11 + -0x28]
  - FIELD@142ac1b48:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@142ac1b12:MOVSS dword ptr [RBP + -0x78],XMM1
  - FIELD@142ac19dd:MOV dword ptr [RBP + -0x74],0x0
  - FIELD@142ac1b63:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@142ac1b58:MOVSS dword ptr [RBP + -0x5c],XMM1
  - FIELD@142ac1bc4:MOVAPS XMM9,xmmword ptr [R11 + -0x48]
  - FIELD@142ac135c:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142ac1370:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@142ac19fb:MOV dword ptr [RBP + -0x54],0x3f800000
  - FIELD@142ac1375:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - FIELD@142ac139a:MOVAPS xmmword ptr [RAX + -0xa8],XMM14
  - FIELD@142ac1387:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@142ac1b0c:MOVSS dword ptr [RBP + -0x68],XMM11
  - FIELD@142ac1b32:MOVSS dword ptr [RBP + -0x60],XMM0
  - NAME:POSITION
  - FIELD@142ac1adb:MOVSS dword ptr [RBP + -0x80],XMM1
  - FIELD@142ac1b5d:MOVSS dword ptr [RBP + -0x6c],XMM10
  - FIELD@142ac137f:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@142ac1baf:MOVAPS XMM8,xmmword ptr [R11 + -0x38]
  - FIELD@142ac137a:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142ac1b07:MOVSS dword ptr [RBP + -0x7c],XMM2
  - FIELD@142ac134a:LEA RBP,[RAX + -0x58]
  - FIELD@142ac19e4:MOV dword ptr [RBP + -0x64],0x0
  - FIELD@142ac1ba5:MOVAPS XMM6,xmmword ptr [R11 + -0x18]
  - FIELD@142ac1360:MOVAPS xmmword ptr [RAX + -0x48],XMM7

#83 SCORE=567 REFS=21 CALLS=237 FIELDS=98
NAME: Z_Construct_UClass_UInstancedStaticMeshComponent
ADDR: 14323f8f0
  - CALLS:GetPrivateStaticClassBody<UInstancedStaticMeshComponent>
  - FIELD@14323fdde:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14323fe34:LEA RCX,[RBP + -0x70]
  - FIELD@14323fff4:LEA RDX,[RBP + -0x70]
  - FIELD@14323fd3b:LEA RCX,[RBP + -0x70]
  - FIELD@14323fcfd:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@143240059:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UFunction_UInstancedStaticMeshComponent_GetPositionOfInstance
  - FIELD@14323fdfd:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@14324001d:MOV qword ptr [RBP + -0x58],R12
  - FIELD@143240258:MOV qword ptr [RBP + -0x58],R12
  - FIELD@14323f949:MOV qword ptr [R11 + -0x10],R14
  - FIELD@14323fce5:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@143240019:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@14324024f:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14323fdf7:MOV word ptr [RBP + -0x60],0x100
  - CALLS:GetPrivateStaticClassBody<UActorComponent>
  - NAME:MESH
  - CALLS:Z_Construct_UClass_UStaticMeshComponent
  - CALLS:Z_Construct_UFunction_UInstancedStaticMeshComponent_UpdateInstanceTransform
  - FIELD@14323fd01:MOV qword ptr [RBP + -0x58],R12
  - FIELD@14323f8f4:LEA RBP,[R11 + -0x248]
  - FIELD@14323fcdb:LEA RDX,[RBP + -0x70]
  - FIELD@143240254:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@14323fdda:LEA RDX,[RBP + -0x70]
  - FIELD@14323fe01:MOV qword ptr [RBP + -0x58],R12
  - CALLS:Z_Construct_UFunction_UInstancedStaticMeshComponent_GetInstanceTransform
  - FIELD@143240001:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14323f921:MOV qword ptr [R11 + -0x18],R15
  - FIELD@143240249:MOV word ptr [RBP + -0x60],0x100
  - FIELD@14323fcf7:MOV word ptr [RBP + -0x60],0x100
  - FIELD@143240013:MOV word ptr [RBP + -0x60],0x100

#84 SCORE=563 REFS=4 CALLS=49 FIELDS=5
NAME: StartMission
ADDR: 1402f07c0
  - FIELD@1402f086f:MOV qword ptr [RSP + 0xc8],-0x1
  - STRING_REF:Pawn
  - FIELD@1402f0f18:MOV qword ptr [RSP + 0xb8],-0x1
  - STRING_REF:Character
  - FIELD@1402f0d9a:MOV qword ptr [RSP + 0xb0],-0x1
  - CALLS:SpawnMissionWithCallback
  - FIELD@1402f0b91:MOV qword ptr [RSP + 0xa8],-0x1
  - CALLS:BPGetMissionStartLocation
  - FIELD@1402f09c6:MOV qword ptr [RSP + 0xc0],-0x1

#85 SCORE=561 REFS=14 CALLS=157 FIELDS=109
NAME: Z_Construct_UClass_UStaticMeshComponent
ADDR: 143238190
  - FIELD@143238810:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - FIELD@14323862a:MOV byte ptr [RBP + -0x3e],R15B
  - FIELD@14323835c:MOV word ptr [RBP + -0x40],0x100
  - FIELD@1432385cc:MOV qword ptr [RBP + -0x38],R15
  - FIELD@14323837a:MOV byte ptr [RBP + -0x3e],BL
  - FIELD@143238806:MOV word ptr [RBP + -0x40],0x100
  - FIELD@1432383cb:MOV qword ptr [RBP + -0x50],RDI
  - FIELD@1432385c0:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - FIELD@1432385f5:MOV RCX,qword ptr [RBP + -0x50]
  - FIELD@143238671:LEA RCX,[RBP + -0x50]
  - FIELD@143238362:MOV qword ptr [RBP + -0x38],R15
  - FIELD@14323839a:MOV RCX,qword ptr [RBP + -0x50]
  - FIELD@143238626:MOV qword ptr [RBP + -0x50],RDI
  - FIELD@143238194:LEA RBP,[R11 + -0x278]
  - FIELD@14323881c:MOV qword ptr [RBP + -0x38],R15
  - FIELD@143238366:MOVDQU xmmword ptr [RBP + -0x50],XMM0
  - FIELD@14323880c:MOV byte ptr [RBP + -0x3e],0x1
  - NAME:MESH
  - FIELD@143238412:LEA RCX,[RBP + -0x50]
  - CALLS:GetPrivateStaticClassBody<UStaticMeshComponent>
  - FIELD@1432381dd:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1432381e5:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1432385bc:MOV byte ptr [RBP + -0x3e],0x1
  - FIELD@1432385b6:MOV word ptr [RBP + -0x40],0x100
  - FIELD@1432383cf:MOV byte ptr [RBP + -0x3e],R15B
  - FIELD@1432381b7:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UClass_UMeshComponent
  - FIELD@1432381e1:MOV qword ptr [R11 + -0x18],R13

#86 SCORE=557 REFS=5 CALLS=94 FIELDS=65
NAME: load
ADDR: 143c27a90
  - FIELD@143c27a96:LEA RBP,[RSP + -0x208]
  - FIELD@143c27be2:LEA RAX,[RBP + -0x20]
  - FIELD@143c27d8b:MOV RAX,-0x1
  - FIELD@143c2848b:LEA RAX,[RBP + -0x80]
  - FIELD@143c283cf:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@143c283f1:LEA RAX,[RBP + -0x80]
  - FIELD@143c27ae4:LEA RDX,[RBP + -0x30]
  - FIELD@143c2839f:LEA RAX,[RBP + -0x80]
  - FIELD@143c28276:LEA RDX,[RBP + -0x60]
  - STRING_REF:Location
  - FIELD@143c28393:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - CALLS:addNewClass
  - FIELD@143c27af3:MOV EAX,dword ptr [RBP + -0x30]
  - FIELD@143c28371:MOVSD qword ptr [RBP + -0x70],XMM1
  - FIELD@143c284b7:MOVSD qword ptr [RBP + -0x70],XMM1
  - FIELD@143c27e02:LEA ECX,[RSI + -0x1]
  - FIELD@143c2843e:LEA RAX,[RBP + -0x80]
  - FIELD@143c28421:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@143c284ad:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@143c2826a:MOV dword ptr [RBP + -0x60],R8D
  - FIELD@143c28460:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@143c2846a:MOVSD qword ptr [RBP + -0x70],XMM1
  - FIELD@143c27bcd:LEA RCX,[RBP + -0x20]
  - FIELD@143c283d3:MOVSD qword ptr [RBP + -0x70],XMM1
  - FIELD@143c28352:LEA RAX,[RBP + -0x80]
  - FIELD@143c28425:MOVSD qword ptr [RBP + -0x70],XMM1
  - FIELD@143c2826e:MOV dword ptr [RBP + -0x5c],R9D

#87 SCORE=556 REFS=2 CALLS=37 FIELDS=0
NAME: ApplyTetherMoveVelocity_Implementation
ADDR: 140466950
  - CALLS:AdjustMovementVectorIfAgainstSurface
  - CALLS:GetTetherWorldEndLocation
  - NAME:VELOCITY
  - CALLS:GetGrappleVelocityDampingRate
  - CALLS:CanManipulateOwnerVelocity

#88 SCORE=552 REFS=7 CALLS=102 FIELDS=28
NAME: PerformMovement
ADDR: 1428c1630
  - FIELD@1428c23ed:LEA R8,[RBP + -0x50]
  - FIELD@1428c22ca:LEA R8,[RBP + -0x50]
  - CALLS:~FScopedMovementUpdate
  - FIELD@1428c182f:MOVSD qword ptr [RBP + -0x70],XMM0
  - FIELD@1428c231e:MOVSS dword ptr [RBP + -0x7c],XMM0
  - FIELD@1428c22f6:LEA RDX,[RBP + -0x80]
  - FIELD@1428c1834:MOV dword ptr [RBP + -0x68],EAX
  - FIELD@1428c23e9:LEA R9,[RBP + -0x60]
  - FIELD@1428c1963:MOVSD qword ptr [RBP + -0x50],XMM0
  - CALLS:FScopedMovementUpdate
  - FIELD@1428c189e:LEA RCX,[RBP + -0x30]
  - FIELD@1428c230c:MOVSS dword ptr [RBP + -0x80],XMM1
  - FIELD@1428c1633:LEA RBP,[RSP + -0x2e8]
  - FIELD@1428c190d:MOV dword ptr [RBP + -0x58],EAX
  - FIELD@1428c2319:MOVSS dword ptr [RBP + -0x78],XMM1
  - FIELD@1428c186d:MOV EAX,dword ptr [RBP + -0x40]
  - CALLS:BPModifyRootMotionDeltaRotation
  - NAME:MOVEMENT
  - FIELD@1428c188f:MOVSS dword ptr [RBP + -0x3c],XMM0
  - FIELD@1428c235e:MOVSS XMM0,dword ptr [RBP + -0x7c]
  - FIELD@1428c2352:MOVSS XMM0,dword ptr [RBP + -0x80]
  - FIELD@1428c23ac:LEA RAX,[RBP + -0x40]
  - FIELD@1428c22c3:LEA R9,[RBP + -0x60]
  - FIELD@1428c236a:MOVSS XMM0,dword ptr [RBP + -0x78]
  - FIELD@1428c195a:MOV dword ptr [RBP + -0x48],EAX
  - FIELD@1428c23b0:LEA R9,[RBP + -0x70]
  - FIELD@1428c18a2:MOV dword ptr [RBP + -0x40],EAX
  - FIELD@1428c1908:MOVSD qword ptr [RBP + -0x60],XMM0
  - FIELD@1428c1894:MOVSS dword ptr [RBP + -0x38],XMM1

#89 SCORE=551 REFS=4 CALLS=135 FIELDS=0
NAME: TickStasisForCharacter
ADDR: 14106ed40
  - CALLS:operator==<AActor,APrimalDinoCharacter,FWeakObjectPtr,FIndexToObject>
  - NAME:CHARACTER

#90 SCORE=550 REFS=7 CALLS=7 FIELDS=33
NAME: GetTransformMatrix
ADDR: 142b4ded0
  - FIELD@142b4e2bc:MOV dword ptr [RBP + -0x44],0x0
  - FIELD@142b4e38a:MOVSS dword ptr [RBP + -0x78],XMM0
  - FIELD@142b4e3f5:MOVAPS XMM10,xmmword ptr [R11 + -0x50]
  - CALLS:GetBoneTransform
  - FIELD@142b4dee3:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@142b4dee7:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@142b4e29b:MOV qword ptr [RBP + -0x58],0x0
  - FIELD@142b4e24f:MOV qword ptr [RBP + -0x64],0x0
  - FIELD@142b4e32e:MOVSS dword ptr [RBP + -0x80],XMM0
  - FIELD@142b4e3c4:MOVSS dword ptr [RBP + -0x48],XMM0
  - FIELD@142b4df00:MOVAPS xmmword ptr [RAX + -0x58],XMM10
  - FIELD@142b4e379:MOVSS dword ptr [RBP + -0x7c],XMM0
  - FIELD@142b4e3fa:MOVAPS XMM11,xmmword ptr [R11 + -0x60]
  - FIELD@142b4e2a3:MOV qword ptr [RBP + -0x50],0x0
  - FIELD@142b4e3b1:MOVSS dword ptr [RBP + -0x5c],XMM0
  - FIELD@142b4e3db:MOVAPS XMM5,xmmword ptr [RBP + -0x80]
  - FIELD@142b4e3a7:MOVAPS XMM2,xmmword ptr [RBP + -0x70]
  - FIELD@142b4df0f:MOVAPS xmmword ptr [RAX + -0x88],XMM13
  - NAME:TRANSFORM
  - FIELD@142b4e39c:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@142b4defb:MOVAPS xmmword ptr [RAX + -0x48],XMM9
  - FIELD@142b4deeb:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@142b4ded8:LEA RBP,[RAX + -0x58]
  - FIELD@142b4e247:MOV qword ptr [RBP + -0x6c],0x0
  - FIELD@142b4df05:MOVAPS xmmword ptr [RAX + -0x68],XMM11
  - FIELD@142b4df0a:MOVAPS xmmword ptr [RAX + -0x78],XMM12
  - FIELD@142b4e294:MOV dword ptr [RBP + -0x74],0x3f800000

#91 SCORE=550 REFS=8 CALLS=37 FIELDS=4
NAME: CalcVelocity
ADDR: 1428c5a50
  - FIELD@1428c5a55:LEA RBP,[RSP + -0x20]
  - FIELD@1428c5e8c:LEA RCX,[RBP + -0x80]
  - CALLS:GetTetheredVelocity
  - NAME:VELOCITY
  - FIELD@1428c5ea9:MOVAPS xmmword ptr [RBP + -0x80],XMM0
  - FIELD@1428c5f41:LEA RDX,[RBP + -0x80]

#92 SCORE=545 REFS=5 CALLS=96 FIELDS=87
NAME: ReplicateClientActors
ADDR: 142a85710
  - FIELD@142a85991:LEA RAX,[RBP + -0x80]
  - FIELD@142a85739:MOV qword ptr [RAX + -0x40],R14
  - FIELD@142a857d7:MOV qword ptr [RBP + -0x78],R13
  - FIELD@142a85978:MOV qword ptr [RBP + -0x80],RCX
  - FIELD@142a858e6:MOVUPS XMM0,xmmword ptr [RBP + -0x48]
  - FIELD@142a85a0e:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142a85988:LEA RAX,[RBP + -0x80]
  - FIELD@142a859f1:MOV dword ptr [RBP + -0x6c],EAX
  - FIELD@142a859e4:LEA RCX,[RBP + -0x78]
  - FIELD@142a85793:CMP EAX,-0x1
  - NAME:ACTOR
  - FIELD@142a85974:LEA RAX,[RBP + -0x80]
  - FIELD@142a857bd:MOV qword ptr [RBP + -0x68],R10
  - FIELD@142a858f2:MOVUPS XMM1,xmmword ptr [RBP + -0x38]
  - FIELD@142a859f9:MOV R12D,dword ptr [RBP + -0x6c]
  - CALLS:SetChannelActor
  - FIELD@142a858e2:MOVUPS xmmword ptr [RBP + -0x40],XMM0
  - FIELD@142a8572d:LEA RBP,[RSP + -0x50]
  - FIELD@142a858ea:MOVUPS xmmword ptr [RBP + -0x30],XMM2
  - FIELD@142a8582d:MOV R10,qword ptr [RBP + -0x68]
  - FIELD@142a859fd:MOV R14D,dword ptr [RBP + -0x70]
  - FIELD@142a8589c:LEA EAX,[RCX + -0x1]
  - CALLS:ReplicateActor
  - FIELD@142a858d9:MOV qword ptr [RBP + -0x48],R11
  - FIELD@142a85854:LEA EAX,[R9 + -0x1]
  - FIELD@142a85743:MOVAPS xmmword ptr [RAX + -0xa8],XMM11
  - CALLS:FActorPriority
  - CALLS:SortInternal<FActorPriority_*___ptr64,TDereferenceWrapper<FActorPriority_*___ptr64,`UNetDriver::ServerReplicateActors'::__l389::FCompareFActorPriority>_>
  - FIELD@142a85a01:MOV R15,qword ptr [RBP + -0x78]
  - FIELD@142a859ca:MOV dword ptr [RBP + -0x70],R14D

#93 SCORE=540 REFS=4 CALLS=52 FIELDS=1
NAME: APrimalCharacter
ADDR: 1404b63a0
  - NAME:CHARACTER
  - FIELD@1404b80a6:MOV qword ptr [RSP + 0x40],-0x1
  - CALLS:SetDefaultSubobjectClass<UShooterCharacterMovement>
  - STRING_REF:Character

#94 SCORE=536 REFS=5 CALLS=10 FIELDS=60
NAME: SetTransform
ADDR: 142af8570
  - FIELD@142af86b3:MOV dword ptr [RBP + -0x41],EAX
  - FIELD@142af8632:MOVSD qword ptr [RBP + -0x29],XMM0
  - FIELD@142af85ae:MOV EAX,dword ptr [RBP + -0x21]
  - FIELD@142af8759:MOV EAX,dword ptr [RBP + -0x41]
  - FIELD@142af8595:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@142af8591:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@142af868f:MOV dword ptr [RBP + -0x41],EAX
  - FIELD@142af8692:MOVSD qword ptr [RBP + -0x49],XMM0
  - FIELD@142af86b6:MOVSD qword ptr [RBP + -0x49],XMM0
  - FIELD@142af8745:MOVSS dword ptr [RBP + -0x49],XMM4
  - FIELD@142af8610:MOV dword ptr [RBP + -0x21],EAX
  - FIELD@142af868a:MOVSD XMM0,qword ptr [RBP + -0x39]
  - FIELD@142af85a4:MOVSS dword ptr [RBP + -0x21],XMM0
  - FIELD@142af85c8:MOV qword ptr [RBP + -0x29],0x0
  - FIELD@142af8664:MOVSS dword ptr [RBP + -0x35],XMM5
  - FIELD@142af85b1:LEA RDX,[RBP + -0x19]
  - FIELD@142af874f:MOVSD XMM0,qword ptr [RBP + -0x49]
  - FIELD@142af8754:MOVSS dword ptr [RBP + -0x41],XMM6
  - FIELD@142af85d0:MOV dword ptr [RBP + -0x21],0x0
  - FIELD@142af8644:MOVSS dword ptr [RBP + -0x39],XMM4
  - FIELD@142af874a:MOVSS dword ptr [RBP + -0x45],XMM5
  - FIELD@142af8687:MOV EAX,dword ptr [RBP + -0x31]
  - NAME:TRANSFORM
  - FIELD@142af857c:LEA RBP,[RAX + -0x5f]
  - FIELD@142af859c:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@142af8669:MOVSS dword ptr [RBP + -0x31],XMM6

#95 SCORE=534 REFS=7 CALLS=6 FIELDS=20
NAME: getRelativeTransform
ADDR: 143c0e310
  - FIELD@143c0e35d:MOVAPS xmmword ptr [RAX + -0xa8],XMM14
  - FIELD@143c0e348:MOVAPS xmmword ptr [RAX + -0x78],XMM11
  - FIELD@143c0e7c3:MOVAPS XMM14,xmmword ptr [R11 + -0x90]
  - NAME:RELATIVE
  - FIELD@143c0e365:MOVAPS xmmword ptr [RAX + -0xb8],XMM15
  - FIELD@143c0e77e:MOVAPS XMM11,xmmword ptr [R11 + -0x60]
  - FIELD@143c0e7b4:MOVAPS XMM8,xmmword ptr [R11 + -0x30]
  - FIELD@143c0e355:MOVAPS xmmword ptr [RAX + -0x98],XMM13
  - FIELD@143c0e79f:MOVAPS XMM7,xmmword ptr [R11 + -0x20]
  - FIELD@143c0e7cb:MOVAPS XMM15,xmmword ptr [R11 + -0xa0]
  - FIELD@143c0e325:MOVAPS xmmword ptr [RAX + -0x48],XMM8
  - FIELD@143c0e321:MOVAPS xmmword ptr [RAX + -0x38],XMM7
  - FIELD@143c0e33e:MOVAPS xmmword ptr [RAX + -0x58],XMM9
  - FIELD@143c0e31d:MOVAPS xmmword ptr [RAX + -0x28],XMM6
  - FIELD@143c0e7be:MOVAPS XMM13,xmmword ptr [R11 + -0x80]
  - FIELD@143c0e774:MOVAPS XMM9,xmmword ptr [R11 + -0x40]
  - FIELD@143c0e34d:MOVAPS xmmword ptr [RAX + -0x88],XMM12
  - NAME:TRANSFORM
  - FIELD@143c0e7a9:MOVAPS XMM6,xmmword ptr [R11 + -0x10]
  - FIELD@143c0e779:MOVAPS XMM10,xmmword ptr [R11 + -0x50]
  - FIELD@143c0e343:MOVAPS xmmword ptr [RAX + -0x68],XMM10
  - FIELD@143c0e7b9:MOVAPS XMM12,xmmword ptr [R11 + -0x70]

#96 SCORE=531 REFS=4 CALLS=6 FIELDS=28
NAME: GetConnectionLocationAndRotation
ADDR: 142dad350
  - FIELD@142dad61e:MOVSD qword ptr [RBP + -0x49],XMM0
  - FIELD@142dad42c:LEA RDX,[RBP + -0x39]
  - FIELD@142dad558:LEA RCX,[RBP + -0x49]
  - FIELD@142dad623:MOVSS XMM2,dword ptr [RBP + -0x45]
  - FIELD@142dad486:MOVSS XMM0,dword ptr [RBP + -0x31]
  - FIELD@142dad435:MOVSS XMM14,dword ptr [RBP + -0x39]
  - FIELD@142dad3c1:MOVSD qword ptr [RBP + -0x49],XMM0
  - NAME:ROTATION
  - FIELD@142dad462:MOVSS XMM0,dword ptr [RBP + -0x41]
  - FIELD@142dad628:MOVSS XMM7,dword ptr [RBP + -0x49]
  - FIELD@142dad423:MOVSS XMM0,dword ptr [RBP + -0x31]
  - NAME:LOCATION
  - FIELD@142dad450:MOVSS XMM6,dword ptr [RBP + -0x49]
  - FIELD@142dad3f0:LEA RDX,[RBP + -0x39]
  - FIELD@142dad49b:MOVSS XMM2,dword ptr [RBP + -0x35]
  - FIELD@142dad5a6:MOV EAX,dword ptr [RBP + -0x41]
  - FIELD@142dad481:MOVSS XMM1,dword ptr [RBP + -0x2d]
  - FIELD@142dad430:MOVSS XMM2,dword ptr [RBP + -0x35]
  - FIELD@142dad5a1:MOVSS dword ptr [RBP + -0x41],XMM0
  - FIELD@142dad5f3:MOVAPS xmmword ptr [RBP + -0x49],XMM1
  - FIELD@142dad62d:MOV dword ptr [RBP + -0x41],EAX
  - FIELD@142dad41e:MOVSS XMM1,dword ptr [RBP + -0x2d]
  - FIELD@142dad554:LEA RDX,[RBP + -0x39]
  - FIELD@142dad471:MOVSS XMM2,dword ptr [RBP + -0x45]
  - FIELD@142dad3be:MOV dword ptr [RBP + -0x41],EAX
  - FIELD@142dad365:LEA RBP,[RSP + -0x57]
  - FIELD@142dad4a0:MOVSS XMM13,dword ptr [RBP + -0x39]

#97 SCORE=529 REFS=22 CALLS=154 FIELDS=29
NAME: Z_Construct_UClass_ATrueSkySequenceActor
ADDR: 1439f9a00
  - FIELD@1439fa343:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439fa155:MOV qword ptr [RBP + -0x10],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetSunRotation
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetKeyframeInt
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetSunColor
  - FIELD@1439fa64c:MOV qword ptr [RBP + -0x8],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_CloudLineTest
  - FIELD@1439fa159:MOV qword ptr [RBP + -0x8],R14
  - NAME:ACTOR
  - FIELD@1439fa061:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439fa347:MOV qword ptr [RBP + -0x8],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetNextModifiableSkyKeyframe
  - FIELD@1439f9a27:MOV qword ptr [R11 + -0x10],R14
  - FIELD@1439fa648:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439f9a4d:MOV qword ptr [R11 + -0x18],R15
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetPointLight
  - FIELD@1439fa767:MOV qword ptr [RBP + -0x10],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetInt
  - CALLS:GetPrivateStaticClassBody<ATrueSkySequenceActor>
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_CloudPointTest
  - FIELD@1439fa528:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439f9a04:LEA RBP,[R11 + -0x208]
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetTime
  - FIELD@1439f9d5a:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1439fa065:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1439fa433:MOV qword ptr [RBP + -0x10],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetKeyframeInt
  - FIELD@1439fa76b:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1439fa88d:MOV qword ptr [RBP + -0x10],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetPointLightSource
  - FIELD@1439fa257:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1439fa891:MOV qword ptr [RBP + -0x8],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetNextModifiableCloudKeyframe
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetFloat
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetInt
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_SetKeyframeFloat
  - FIELD@1439f9f6d:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439f9d52:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439fa253:MOV qword ptr [RBP + -0x10],R14
  - FIELD@1439fa52c:MOV qword ptr [RBP + -0x8],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetFloat
  - FIELD@1439fa437:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1439f9f71:MOV qword ptr [RBP + -0x8],R14
  - CALLS:Z_Construct_UFunction_ATrueSkySequenceActor_GetKeyframeFloat

#98 SCORE=525 REFS=6 CALLS=91 FIELDS=105
NAME: Z_Construct_UScriptStruct_UPlayerInput_FKeyBind
ADDR: 143565440
  - FIELD@1435657f9:LEA RCX,[RBP + -0x48]
  - FIELD@143565693:MOV qword ptr [RBP + -0x50],R12
  - FIELD@143565819:MOV qword ptr [RBP + -0x70],R12
  - FIELD@14356579f:MOV byte ptr [RBP + -0x36],R12B
  - FIELD@143565815:MOV qword ptr [RBP + -0x78],RAX
  - FIELD@143565686:LEA RCX,[RBP + -0x58]
  - FIELD@14356579b:MOV qword ptr [RBP + -0x48],RDI
  - FIELD@143565673:LEA RCX,[RBP + -0x48]
  - FIELD@14356580c:LEA RCX,[RBP + -0x78]
  - FIELD@143565566:MOV qword ptr [RBP + -0x30],R12
  - FIELD@143565720:MOV ESI,dword ptr [RBP + -0x4c]
  - FIELD@14356572a:MOVDQU xmmword ptr [RBP + -0x48],XMM0
  - NAME:PLAYER
  - FIELD@1435655e0:MOV byte ptr [RBP + -0x36],R12B
  - FIELD@14356557e:MOV byte ptr [RBP + -0x36],BL
  - FIELD@14356556a:MOVDQU xmmword ptr [RBP + -0x48],XMM0
  - FIELD@143565763:MOV RAX,qword ptr [RBP + -0x48]
  - FIELD@143565723:MOV R14D,dword ptr [RBP + -0x50]
  - FIELD@143565560:MOV word ptr [RBP + -0x38],0x100
  - FIELD@14356573c:MOV word ptr [RBP + -0x38],0x100
  - FIELD@1435655dc:MOV qword ptr [RBP + -0x48],RDI
  - FIELD@143565746:MOV qword ptr [RBP + -0x30],R12
  - FIELD@1435655ae:MOV RAX,qword ptr [RBP + -0x48]
  - FIELD@143565446:LEA RBP,[RSP + -0x118]
  - CALLS:Z_Construct_UClass_UPlayerInput
  - FIELD@143565742:MOV byte ptr [RBP + -0x36],0x1
  - FIELD@14356568f:MOV qword ptr [RBP + -0x58],RAX

#99 SCORE=525 REFS=2 CALLS=6 FIELDS=0
NAME: SimpleCurveInterpClampedTransform
ADDR: 1415bfb50
  - NAME:TRANSFORM

#100 SCORE=518 REFS=5 CALLS=106 FIELDS=76
NAME: Z_Construct_UClass_UParticleModuleLocationSkelVertSurface
ADDR: 1435f9e00
  - FIELD@1435f9f72:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - FIELD@1435f9e04:LEA RBP,[R11 + -0x248]
  - FIELD@1435fa0f8:MOV qword ptr [RBP + -0x60],R15
  - FIELD@1435fa0dc:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - FIELD@1435fa4f4:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - CALLS:Z_Construct_UClass_UParticleModuleLocationBase
  - FIELD@1435fa03a:LEA RCX,[RBP + -0x78]
  - FIELD@1435f9fe5:MOV qword ptr [RBP + -0x78],RBX
  - FIELD@1435fa0cf:LEA RDX,[RBP + -0x78]
  - NAME:LOCATION
  - FIELD@1435f9e52:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1435fa135:LEA RCX,[RBP + -0x78]
  - FIELD@1435f9f93:MOV qword ptr [RBP + -0x60],R15
  - CALLS:GetPrivateStaticClassBody<UParticleModuleLocationSkelVertSurface>
  - FIELD@1435f9e4e:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1435f9f89:MOV word ptr [RBP + -0x68],0x100
  - FIELD@1435fa0f4:MOV byte ptr [RBP + -0x66],0x1
  - FIELD@1435f9e56:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1435f9e27:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1435f9fb0:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@1435f9fe9:MOV byte ptr [RBP + -0x66],R15B
  - FIELD@1435fa529:MOV RCX,qword ptr [RBP + -0x78]
  - FIELD@1435fa55a:MOV qword ptr [RBP + -0x78],RBX
  - FIELD@1435fa500:MOV qword ptr [RBP + -0x60],R15
  - CALLS:Z_Construct_UEnum_UParticleModuleLocationSkelVertSurface_ELocationSkelVertSurfaceSource
  - FIELD@1435f9f8f:MOV byte ptr [RBP + -0x66],DIL
  - FIELD@1435fa4f0:MOV byte ptr [RBP + -0x66],0x1
  - FIELD@1435fa0ee:MOV word ptr [RBP + -0x68],0x100
  - FIELD@1435fa4ea:MOV word ptr [RBP + -0x68],0x100

#101 SCORE=518 REFS=3 CALLS=27 FIELDS=25
NAME: CompressRotation_11_11_10
ADDR: 142cf27c0
  - FIELD@142cf27f3:MOVAPS xmmword ptr [RAX + -0x88],XMM10
  - FIELD@142cf30c1:MOVAPS XMM10,xmmword ptr [R11 + -0x68]
  - FIELD@142cf30cb:MOVAPS XMM13,xmmword ptr [R11 + -0x98]
  - FIELD@142cf2f92:MULSS XMM5,dword ptr [RBP + -0x70]
  - FIELD@142cf30ad:MOVAPS XMM6,xmmword ptr [R11 + -0x28]
  - FIELD@142cf27c9:LEA RBP,[RAX + -0x78]
  - NAME:ROTATION
  - FIELD@142cf27d8:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@142cf30c6:MOVAPS XMM11,xmmword ptr [R11 + -0x78]
  - FIELD@142cf27e9:MOVAPS xmmword ptr [RAX + -0x68],XMM8
  - CALLS:CompressRotation_Identity
  - FIELD@142cf2816:MOVAPS xmmword ptr [RAX + -0xc8],XMM14
  - FIELD@142cf30b7:MOVAPS XMM8,xmmword ptr [R11 + -0x48]
  - FIELD@142cf2cc7:LEA RCX,[RBP + -0x6c]
  - FIELD@142cf30bc:MOVAPS XMM9,xmmword ptr [R11 + -0x58]
  - FIELD@142cf27dc:MOVAPS xmmword ptr [RAX + -0x58],XMM7
  - FIELD@142cf2ce1:MOV EAX,dword ptr [RBP + -0x6c]
  - FIELD@142cf30d3:MOVAPS XMM14,xmmword ptr [R11 + -0xa8]
  - FIELD@142cf30b2:MOVAPS XMM7,xmmword ptr [R11 + -0x38]
  - FIELD@142cf280b:MOVAPS xmmword ptr [RAX + -0xb8],XMM13
  - FIELD@142cf2841:MOVSS XMM1,dword ptr [RBP + -0x80]
  - FIELD@142cf2803:MOVAPS xmmword ptr [RAX + -0x98],XMM11
  - FIELD@142cf3046:DEC qword ptr [RBP + -0x68]
  - FIELD@142cf2b2b:MOV qword ptr [RBP + -0x68],RDI
  - FIELD@142cf284a:MOVSS XMM2,dword ptr [RBP + -0x7c]
  - FIELD@142cf2d61:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@142cf27ee:MOVAPS xmmword ptr [RAX + -0x78],XMM9

#102 SCORE=510 REFS=21 CALLS=399 FIELDS=29
NAME: Z_Construct_UClass_APlayerCameraManager
ADDR: 1430af9c0
  - CALLS:Z_Construct_UScriptStruct_APlayerCameraManager_FCameraCacheEntry
  - CALLS:Z_Construct_UScriptStruct_APlayerCameraManager_FTViewTarget
  - FIELD@1430b0b8d:MOV R9D,dword ptr [RBP + -0x38]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_StopAllCameraAnims
  - CALLS:GetPrivateStaticClassBody<APlayerCameraManager>
  - FIELD@1430b0754:MOV R9D,dword ptr [RBP + -0x68]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_AddCameraLensEffect
  - FIELD@1430b0925:LEA RCX,[RBP + -0x30]
  - FIELD@1430b0b08:MOV R9D,dword ptr [RBP + -0x58]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_GetCameraRotation
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_PlayCameraAnim
  - FIELD@1430b0818:LEA RCX,[RBP + -0x50]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_StopAllInstancesOfCameraAnim
  - FIELD@1430b0a79:MOV R9D,dword ptr [RBP + -0x78]
  - FIELD@1430af9c4:LEA RBP,[R11 + -0x2f8]
  - FIELD@1430b07e5:MOV EAX,dword ptr [RBP + -0x4]
  - FIELD@1430b070a:LEA RCX,[RBP + -0x70]
  - FIELD@1430afa1a:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1430b078f:LEA RCX,[RBP + -0x10]
  - CALLS:Z_Construct_UEnum_APlayerCameraManager_EViewTargetBlendFunction
  - FIELD@1430b0ab4:LEA RCX,[RBP + -0x60]
  - FIELD@1430b0a2f:LEA RCX,[RBP + -0x80]
  - FIELD@1430b0b14:MOV EAX,dword ptr [RBP + -0x54]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_GetOwningPlayerController
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_StopCameraAnimInst
  - NAME:CAMERA
  - NAME:PLAYER
  - FIELD@1430b0862:MOV R9D,dword ptr [RBP + -0x48]
  - FIELD@1430b0a85:MOV EAX,dword ptr [RBP + -0x74]
  - FIELD@1430b096f:MOV R9D,dword ptr [RBP + -0x28]
  - CALLS:Z_Construct_UScriptStruct_APlayerCameraManager_FViewTargetTransitionParams
  - FIELD@1430af9eb:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1430b0b43:LEA RCX,[RBP + -0x40]
  - FIELD@1430b097b:MOV EAX,dword ptr [RBP + -0x24]
  - FIELD@1430b0760:MOV EAX,dword ptr [RBP + -0x64]
  - FIELD@1430afa1e:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1430afa22:MOV qword ptr [R11 + -0x28],R15
  - FIELD@1430b07d9:MOV R9D,dword ptr [RBP + -0x8]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_BlueprintUpdateCamera
  - FIELD@1430b086e:MOV EAX,dword ptr [RBP + -0x44]
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_RemoveCameraLensEffect
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_GetCameraLocation
  - CALLS:Z_Construct_UFunction_APlayerCameraManager_GetWorldCameraShakeScale

#103 SCORE=506 REFS=2 CALLS=27 FIELDS=46
NAME: UpdateDesiredArmLocation
ADDR: 142d811a0
  - FIELD@142d8125d:MOVSS dword ptr [RBP + -0x7c],XMM0
  - FIELD@142d811e0:MOVAPS xmmword ptr [RAX + -0x98],XMM12
  - FIELD@142d812a8:MOVSD qword ptr [RBP + -0x80],XMM0
  - FIELD@142d811c1:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142d812af:MOV ECX,dword ptr [RBP + -0x78]
  - FIELD@142d811b3:LEA RBP,[RAX + -0x1a8]
  - FIELD@142d81218:LEA RDX,[RBP + -0x80]
  - FIELD@142d813a7:LEA RDX,[RBP + -0x80]
  - FIELD@142d8124c:MOVSS dword ptr [RBP + -0x80],XMM0
  - FIELD@142d811d3:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142d811d8:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@142d81562:LEA R8,[RBP + -0x70]
  - FIELD@142d811ce:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - NAME:LOCATION
  - FIELD@142d811e8:MOVAPS xmmword ptr [RAX + -0xa8],XMM13
  - FIELD@142d81398:LEA RCX,[RBP + -0x80]
  - FIELD@142d8126e:MOVSS dword ptr [RBP + -0x78],XMM0
  - FIELD@142d81566:LEA RDX,[RBP + -0x50]
  - FIELD@142d8121c:LEA RCX,[RBP + -0x60]
  - FIELD@142d812b2:MOVSD XMM0,qword ptr [RBP + -0x80]
  - CALLS:GetRelativeTransform
  - CALLS:UpdateChildTransforms
  - FIELD@142d812a5:MOV dword ptr [RBP + -0x78],ECX
  - FIELD@142d81220:MOVAPS xmmword ptr [RBP + -0x60],XMM0
  - FIELD@142d81571:MOV dword ptr [RBP + -0x70],EAX
  - FIELD@142d811c5:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142d811c9:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@142d81286:LEA R8,[RBP + -0x80]

#104 SCORE=505 REFS=10 CALLS=109 FIELDS=94
NAME: Z_Construct_UClass_APlayerState
ADDR: 14310e0a0
  - FIELD@14310e42e:MOV qword ptr [RBP + -0x58],R15
  - FIELD@14310e26f:MOV word ptr [RBP + -0x60],0x100
  - CALLS:Z_Construct_UFunction_APlayerState_GetExactPing
  - FIELD@14310e0f1:MOV qword ptr [R11 + -0x18],R13
  - FIELD@14310e0ed:MOV qword ptr [R11 + -0x10],R12
  - FIELD@14310e425:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14310e41f:MOV word ptr [RBP + -0x60],0x100
  - FIELD@14310e4a0:LEA RCX,[RBP + -0x70]
  - FIELD@14310e542:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14310e473:LEA RDX,[RBP + -0x70]
  - FIELD@14310e0c7:MOV qword ptr [R11 + -0x28],R15
  - FIELD@14310e2e2:MOV byte ptr [RBP + -0x5e],R15B
  - NAME:PLAYER
  - FIELD@14310e32d:LEA RCX,[RBP + -0x70]
  - FIELD@14310e55a:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@14310e554:MOV word ptr [RBP + -0x60],0x100
  - FIELD@14310e28d:MOV byte ptr [RBP + -0x5e],BL
  - FIELD@14310e42a:MOV byte ptr [RBP + -0x5e],0x1
  - FIELD@14310e55e:MOV qword ptr [RBP + -0x58],R15
  - FIELD@14310e535:LEA RDX,[RBP + -0x70]
  - FIELD@14310e275:MOV qword ptr [RBP + -0x58],R15
  - FIELD@14310e2de:MOV qword ptr [RBP + -0x70],RDI
  - FIELD@14310e279:MOVDQU xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14310e0f5:MOV qword ptr [R11 + -0x20],R14
  - FIELD@14310e595:LEA RCX,[RBP + -0x70]
  - FIELD@14310e2ad:MOV RCX,qword ptr [RBP + -0x70]
  - FIELD@14310e0a4:LEA RBP,[R11 + -0x108]
  - CALLS:GetPrivateStaticClassBody<APlayerState>

#105 SCORE=502 REFS=3 CALLS=45 FIELDS=91
NAME: transform_mcu_expand
ADDR: 14258a340
  - FIELD@14258a4ad:MOVDQA xmmword ptr [RBP + -0x60],XMM0
  - FIELD@14258a4b2:MOVDQA xmmword ptr [RBP + -0x40],XMM0
  - FIELD@14258a4cc:MOVDQA xmmword ptr [RBP + -0x50],XMM1
  - FIELD@14258a549:MOVDQA xmmword ptr [RBP + -0x40],XMM0
  - FIELD@14258a3c0:SUB RDI,-0x80
  - FIELD@14258a4d1:MOVDQA xmmword ptr [RBP + -0x30],XMM1
  - FIELD@14258a59b:MOV dword ptr [RBP + -0x54],R12D
  - FIELD@14258a453:MOVDQA xmmword ptr [RBP + -0x50],XMM0
  - FIELD@14258a468:MOVDQA xmmword ptr [RBP + -0x80],XMM1
  - FIELD@14258a482:MOVDQA xmmword ptr [RBP + -0x70],XMM0
  - FIELD@14258a473:MOVDQA xmmword ptr [RBP + -0x20],XMM1
  - FIELD@14258a5ab:MOV dword ptr [RBP + -0x44],R12D
  - FIELD@14258a47d:MOVDQA xmmword ptr [RBP + -0x10],XMM0
  - FIELD@14258a4fa:MOV dword ptr [RBP + -0x74],R12D
  - FIELD@14258a59f:MOV dword ptr [RBP + -0x4c],R12D
  - FIELD@14258a62f:MOV dword ptr [RBP + -0x60],EAX
  - FIELD@14258a5af:MOV dword ptr [RBP + -0x2c],R12D
  - FIELD@14258a352:LEA RBP,[RSP + -0x130]
  - FIELD@14258a458:MOVDQA xmmword ptr [RBP + -0x40],XMM1
  - FIELD@14258a44e:MOVDQA xmmword ptr [RBP + -0x60],XMM1
  - FIELD@14258a63f:MOV dword ptr [RBP + -0x58],ECX
  - NAME:TRANSFORM
  - FIELD@14258a45d:MOVDQA xmmword ptr [RBP + -0x30],XMM0
  - FIELD@14258a4f6:MOV qword ptr [RBP + -0x7c],R12
  - FIELD@14258a597:MOV dword ptr [RBP + -0x5c],R12D
  - FIELD@14258a52c:MOV dword ptr [RBP + -0x80],ECX

#106 SCORE=502 REFS=5 CALLS=68 FIELDS=45
NAME: ServerMoveWithRotation_Implementation
ADDR: 1428e1cf0
  - FIELD@1428e20c3:MOV byte ptr [RBP + -0x30],AL
  - FIELD@1428e20a1:MOVSD qword ptr [RBP + -0x48],XMM0
  - FIELD@1428e2128:MOV EAX,dword ptr [RBP + -0x78]
  - FIELD@1428e1cf9:LEA RBP,[RSP + -0x40]
  - FIELD@1428e2115:MOV qword ptr [RBP + -0x20],RAX
  - CALLS:SetWorldLocation
  - NAME:ROTATION
  - FIELD@1428e20cd:MOV qword ptr [RBP + -0x24],R12
  - FIELD@1428e2046:MOV dword ptr [RBP + -0x78],EAX
  - FIELD@1428e20ab:MOVSS dword ptr [RBP + -0x4c],XMM7
  - FIELD@1428e20be:MOVSD qword ptr [RBP + -0x3c],XMM0
  - FIELD@1428e20ea:MOV dword ptr [RBP + -0x28],EDX
  - FIELD@1428e20df:MOV dword ptr [RBP + -0x2c],EDI
  - FIELD@1428e2110:MOVSD XMM0,qword ptr [RBP + -0x80]
  - FIELD@1428e2125:MOV byte ptr [RBP + -0x18],AL
  - FIELD@1428e209a:MOV dword ptr [RBP + -0x40],EAX
  - FIELD@1428e20d1:MOV byte ptr [RBP + -0x2f],AL
  - FIELD@1428e20f2:MOV dword ptr [RBP + -0x24],EAX
  - FIELD@1428e20f7:MOV dword ptr [RBP + -0x28],0xffffffff
  - FIELD@1428e20b0:MOV dword ptr [RBP + -0x34],EAX
  - CALLS:ConvertFromRelativeToAttachedParent
  - FIELD@1428e20ba:MOV byte ptr [RBP + -0x50],0x2
  - FIELD@1428e1f8d:MOV dword ptr [RBP + -0x78],EAX
  - FIELD@1428e2120:MOVSD qword ptr [RBP + -0x14],XMM0
  - FIELD@1428e2041:MOVSD qword ptr [RBP + -0x80],XMM0
  - FIELD@1428e20db:MOV dword ptr [RBP + -0x1c],R12D
  - FIELD@1428e20fe:MOV dword ptr [RBP + -0x24],R12D
  - CALLS:GetMovementBaseTransform
  - FIELD@1428e1f97:MOVSD qword ptr [RBP + -0x80],XMM0

#107 SCORE=499 REFS=4 CALLS=14 FIELDS=39
NAME: ApplyLevelTransform
ADDR: 142a56f60
  - FIELD@142a57421:LEA RDX,[RBP + -0x60]
  - FIELD@142a57433:MOVSS XMM1,dword ptr [RBP + -0x54]
  - FIELD@142a5706c:LEA EAX,[RCX + -0x1]
  - FIELD@142a570e4:MOVUPS XMM3,xmmword ptr [RBP + -0x20]
  - FIELD@142a574d7:MOV dword ptr [RBP + -0x74],0x3f800000
  - FIELD@142a5719f:MOV qword ptr [RBP + -0x80],0x0
  - FIELD@142a571c0:MOVSS dword ptr [RBP + -0x70],XMM0
  - FIELD@142a570d8:MOVUPS xmmword ptr [RBP + -0x8],XMM5
  - FIELD@142a571a7:MOV dword ptr [RBP + -0x78],0x0
  - FIELD@142a57141:MOV dword ptr [RBP + -0x64],0x3f800000
  - FIELD@142a56f66:LEA RBP,[RSP + -0x60]
  - FIELD@142a574b7:MOVAPS xmmword ptr [RBP + -0x50],XMM4
  - FIELD@142a571dc:MOVAPS XMM8,xmmword ptr [RBP + -0x70]
  - FIELD@142a57310:MOV dword ptr [RDI + RCX*0x1 + -0xc],EAX
  - FIELD@142a5742f:LEA RCX,[RBP + -0x50]
  - FIELD@142a570ac:MOV qword ptr [RBP + -0x20],R14
  - FIELD@142a570e0:MOVUPS XMM4,xmmword ptr [RBP + -0x10]
  - FIELD@142a5745c:MOVSS XMM3,dword ptr [RBP + -0x60]
  - CALLS:SetRelativeLocationAndRotation
  - FIELD@142a570dc:MOVUPS xmmword ptr [RBP + -0x18],XMM0
  - NAME:TRANSFORM
  - FIELD@142a571cb:MOVSS dword ptr [RBP + -0x6c],XMM1
  - FIELD@142a5743d:MOVSS XMM2,dword ptr [RBP + -0x5c]
  - FIELD@142a571d7:MOVSS dword ptr [RBP + -0x68],XMM0
  - FIELD@142a57438:MOVSS XMM0,dword ptr [RBP + -0x58]
  - FIELD@142a57027:LEA EAX,[R9 + -0x1]
  - FIELD@142a5730a:MOVSD qword ptr [RDI + RCX*0x1 + -0x14],XMM0

#108 SCORE=498 REFS=2 CALLS=13 FIELDS=91
NAME: getBinaryMetaData
ADDR: 143c5a3b0
  - FIELD@143c5a434:MOV qword ptr [RBP + -0x10],RSI
  - FIELD@143c5a3e2:MOV qword ptr [RBP + -0x28],RSI
  - FIELD@143c5a46d:MOV qword ptr [RBP + -0x10],RSI
  - FIELD@143c5a47a:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c5a453:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c5a3d4:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@143c5a422:MOV dword ptr [RBP + -0x20],ESI
  - FIELD@143c5a44c:LEA RDX,[RBP + -0x30]
  - FIELD@143c5a465:MOV qword ptr [RBP + -0x18],0x4
  - FIELD@143c5a441:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c5a45e:MOV dword ptr [RBP + -0x1c],0x10
  - FIELD@143c5a41e:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c5a48c:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c5a425:MOV dword ptr [RBP + -0x1c],0x10
  - FIELD@143c5a490:MOV dword ptr [RBP + -0x20],0x20
  - FIELD@143c5a457:MOV dword ptr [RBP + -0x20],0x10
  - FIELD@143c5a3d0:LEA RDX,[RBP + -0x30]
  - STRING_REF:Rotation
  - FIELD@143c5a3e6:MOV dword ptr [RBP + -0x20],ESI
  - FIELD@143c5a40c:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c5a3f1:MOV dword ptr [RBP + -0x14],ESI
  - FIELD@143c5a485:LEA RDX,[RBP + -0x30]
  - FIELD@143c5a3e9:MOV qword ptr [RBP + -0x1c],0x220
  - FIELD@143c5a3f4:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c5a417:LEA RDX,[RBP + -0x30]
  - FIELD@143c5a42c:MOV qword ptr [RBP + -0x18],0x4

#109 SCORE=497 REFS=9 CALLS=94 FIELDS=81
NAME: ReplicateActor
ADDR: 142917260
  - FIELD@142917528:CMP dword ptr [R13 + 0x48],-0x1
  - FIELD@1429172f5:MOV qword ptr [RBP + -0x78],R12
  - FIELD@142917382:LEA RCX,[RBP + -0x80]
  - FIELD@1429173ba:LEA EDX,[RDI + -0x1]
  - FIELD@14291735c:MOVSXD RBX,dword ptr [RBP + -0x78]
  - FIELD@14291726a:LEA RBP,[RSP + -0x168]
  - NAME:ACTOR
  - FIELD@142917652:MOV qword ptr [RBP + -0x40],R14
  - FIELD@14291732e:LEA RCX,[RBP + -0x80]
  - FIELD@142917656:MOV qword ptr [RBP + -0x18],R14
  - FIELD@1429173df:LEA RCX,[RBP + -0x58]
  - FIELD@142917412:MOV RBX,qword ptr [RBP + -0x58]
  - FIELD@142917370:MOV dword ptr [RBP + -0x78],ECX
  - FIELD@1429175db:LEA EAX,[R9 + -0x1]
  - FIELD@142917360:MOV EDX,dword ptr [RBP + -0x74]
  - FIELD@14291730b:OR RAX,-0x1
  - FIELD@1429173c6:MOV RBX,qword ptr [RBP + -0x80]
  - FIELD@142917416:CMP dword ptr [RBP + -0x50],R12D
  - FIELD@14291738f:MOV dword ptr [RBP + -0x74],EAX
  - FIELD@1429174ae:CMP dword ptr [R13 + 0x48],-0x1
  - FIELD@1429173bd:LEA RCX,[RBP + -0x80]
  - FIELD@1429172f1:MOV qword ptr [RBP + -0x80],R12
  - CALLS:operator_enum_EMovementMode
  - FIELD@1429173ca:CMP dword ptr [RBP + -0x78],R12D
  - FIELD@142917346:LEA RDX,[RBP + -0x80]
  - FIELD@142917397:MOV RCX,qword ptr [RBP + -0x80]
  - FIELD@14291761c:LEA EAX,[RCX + -0x1]

#110 SCORE=494 REFS=2 CALLS=13 FIELDS=90
NAME: FUN_143c1f800
ADDR: 143c1f800
  - FIELD@143c1f8a5:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1f882:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c1f8a9:MOV dword ptr [RBP + -0x20],R14D
  - FIELD@143c1f89e:LEA RDX,[RBP + -0x30]
  - FIELD@143c1f8b9:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c1f8d1:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c1f847:MOV qword ptr [RBP + -0x18],R14
  - FIELD@143c1f8e3:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1f863:LEA RDX,[RBP + -0x30]
  - FIELD@143c1f872:MOV dword ptr [RBP + -0x20],R14D
  - STRING_REF:Velocity
  - FIELD@143c1f84b:MOV qword ptr [RBP + -0x10],0x4
  - FIELD@143c1f8e7:MOV dword ptr [RBP + -0x20],0x50
  - FIELD@143c1f834:LEA RDX,[RBP + -0x30]
  - FIELD@143c1f82d:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c1f897:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c1f83f:MOV qword ptr [RBP + -0x30],RSI
  - FIELD@143c1f8b5:MOV dword ptr [RBP + -0x14],R14D
  - FIELD@143c1f876:MOV qword ptr [RBP + -0x1c],0x90
  - FIELD@143c1f87e:MOV dword ptr [RBP + -0x14],R14D
  - FIELD@143c1f86e:MOV qword ptr [RBP + -0x28],R14
  - FIELD@143c1f8ee:MOV dword ptr [RBP + -0x1c],0x4
  - FIELD@143c1f843:MOV qword ptr [RBP + -0x20],R14
  - FIELD@143c1f8ad:MOV qword ptr [RBP + -0x1c],0x90
  - FIELD@143c1f86a:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1f8dc:LEA RDX,[RBP + -0x30]

#111 SCORE=494 REFS=29 CALLS=124 FIELDS=5
NAME: Z_Construct_UClass_UMediaPlayer
ADDR: 14368c1d0
  - FIELD@14368c1d4:LEA RBP,[R11 + -0xd8]
  - CALLS:Z_Construct_UFunction_UMediaPlayer_CanPause
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SetLooping
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SetRate
  - CALLS:Z_Construct_UFunction_UMediaPlayer_CanPlay
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SetMute
  - CALLS:Z_Construct_UFunction_UMediaPlayer_GetUrl
  - CALLS:Z_Construct_UEnum_UMediaPlayer_EMediaPlayerStreamModes
  - FIELD@14368c222:MOV qword ptr [R11 + -0x18],R13
  - CALLS:Z_Construct_UFunction_UMediaPlayer_IsPaused
  - CALLS:Z_Construct_UFunction_UMediaPlayer_IsLooping
  - CALLS:Z_Construct_UFunction_UMediaPlayer_Pause
  - FIELD@14368c1f7:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_UMediaPlayer_GetMute
  - CALLS:Z_Construct_UFunction_UMediaPlayer_Rewind
  - CALLS:Z_Construct_UFunction_UMediaPlayer_GetRate
  - CALLS:Z_Construct_UFunction_UMediaPlayer_Play
  - FIELD@14368c226:MOV qword ptr [R11 + -0x20],R14
  - CALLS:Z_Construct_UFunction_UMediaPlayer_Seek
  - NAME:PLAYER
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SupportsSeeking
  - FIELD@14368c21e:MOV qword ptr [R11 + -0x10],R12
  - CALLS:Z_Construct_UFunction_UMediaPlayer_IsPlaying
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SupportsRate
  - CALLS:Z_Construct_UFunction_UMediaPlayer_GetTime
  - CALLS:Z_Construct_UFunction_UMediaPlayer_OnMediaPlayerMediaOpened__DelegateSignature
  - CALLS:GetPrivateStaticClassBody<UMediaPlayer>
  - CALLS:Z_Construct_UFunction_UMediaPlayer_IsStopped
  - CALLS:Z_Construct_UFunction_UMediaPlayer_GetDuration
  - CALLS:Z_Construct_UFunction_UMediaPlayer_OpenUrl
  - CALLS:Z_Construct_UFunction_UMediaPlayer_SupportsScrubbing

#112 SCORE=494 REFS=25 CALLS=690 FIELDS=0
NAME: SpawnTab
ADDR: 142438f00
  - CALLS:RenderTransform_Static<TOptional<FTransform2D>_(__cdecl*)(void)>
  - CALLS:GetTestRenderTransformPivot
  - NAME:PAWN
  - CALLS:GetTestRenderTransform
  - CALLS:RenderTransformPivot_Static<FVector2D_(__cdecl*)(void)>

#113 SCORE=491 REFS=8 CALLS=113 FIELDS=92
NAME: Z_Construct_UClass_UCameraShake
ADDR: 1435181d0
  - FIELD@1435181d4:LEA RBP,[R11 + -0x118]
  - FIELD@143518385:MOV qword ptr [RBP + -0x50],R15
  - CALLS:Z_Construct_UScriptStruct_UCameraShake_FFOscillator
  - CALLS:GetPrivateStaticClassBody<UCameraAnim>
  - FIELD@143518557:LEA RCX,[RBP + -0x68]
  - FIELD@14351847a:MOV R14D,dword ptr [RBP + -0x80]
  - FIELD@14351849d:MOV qword ptr [RBP + -0x50],R15
  - FIELD@143518628:MOV qword ptr [RBP + -0x50],R15
  - FIELD@14351861e:MOV word ptr [RBP + -0x58],0x100
  - FIELD@1435183da:MOV qword ptr [RBP + -0x80],R15
  - FIELD@143518481:MOVDQU xmmword ptr [RBP + -0x68],XMM0
  - FIELD@14351836a:MOVDQU xmmword ptr [RBP + -0x68],XMM0
  - FIELD@14351860c:MOVDQU xmmword ptr [RBP + -0x68],XMM0
  - FIELD@143518360:LEA RDX,[RBP + -0x68]
  - FIELD@143518624:MOV byte ptr [RBP + -0x56],0x1
  - FIELD@1435184f6:MOV byte ptr [RBP + -0x56],R15B
  - NAME:CAMERA
  - FIELD@14351837c:MOV word ptr [RBP + -0x58],0x100
  - FIELD@1435183b8:LEA RCX,[RBP + -0x68]
  - FIELD@1435184f2:MOV qword ptr [RBP + -0x68],RDI
  - FIELD@143518499:MOV byte ptr [RBP + -0x56],0x1
  - FIELD@1435184ba:MOV RAX,qword ptr [RBP + -0x68]
  - FIELD@143518219:MOV qword ptr [R11 + -0x10],R12
  - FIELD@14351821d:MOV qword ptr [R11 + -0x18],R13
  - FIELD@143518493:MOV word ptr [RBP + -0x58],0x100
  - FIELD@1435181f7:MOV qword ptr [R11 + -0x28],R15
  - FIELD@143518382:MOV byte ptr [RBP + -0x56],BL
  - CALLS:GetPrivateStaticClassBody<UCameraShake>
  - FIELD@143518477:MOV ESI,dword ptr [RBP + -0x7c]

#114 SCORE=491 REFS=2 CALLS=21 FIELDS=38
NAME: EvaluateBoneTransforms
ADDR: 142d30470
  - FIELD@142d30607:LEA RDX,[RBP + -0x31]
  - NAME:BONE
  - FIELD@142d306fa:MOVAPS xmmword ptr [RBP + -0x21],XMM1
  - FIELD@142d3071c:MOVAPS xmmword ptr [RBP + -0x11],XMM2
  - FIELD@142d30679:MOVAPS xmmword ptr [RBP + -0x61],XMM3
  - FIELD@142d3080e:MOVAPS XMM0,xmmword ptr [RBP + -0x51]
  - FIELD@142d30797:MOVAPS xmmword ptr [RBP + -0x61],XMM4
  - CALLS:ConvertCSTransformToBoneSpace
  - FIELD@142d307b0:LEA R8,[RBP + -0x61]
  - FIELD@142d30720:MOVAPS xmmword ptr [RBP + -0x1],XMM4
  - FIELD@142d3051d:LEA RDX,[RBP + -0x61]
  - FIELD@142d305b5:LEA R8,[RBP + -0x61]
  - FIELD@142d30815:MOVAPS xmmword ptr [RBP + -0x51],XMM0
  - FIELD@142d30686:LEA RDX,[RBP + -0x21]
  - FIELD@142d3073e:MOVAPS XMM3,xmmword ptr [RBP + -0x61]
  - FIELD@142d307a1:MOVAPS xmmword ptr [RBP + -0x61],XMM0
  - FIELD@142d305c6:MOVAPS xmmword ptr [RBP + -0x41],XMM3
  - FIELD@142d307d7:LEA R8,[RBP + -0x61]
  - FIELD@142d3079d:MOVAPS XMM0,xmmword ptr [RBP + -0x31]
  - FIELD@142d3068a:LEA RCX,[RBP + -0x31]
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d30541:LEA R8,[RBP + -0x61]
  - FIELD@142d30620:MOVAPS XMM2,xmmword ptr [RBP + -0x61]
  - FIELD@142d3081b:MOVAPS xmmword ptr [RBP + -0x51],XMM3
  - FIELD@142d30477:LEA RBP,[RSP + -0x2f]
  - FIELD@142d3073a:MOVAPS XMM2,xmmword ptr [RBP + -0x31]
  - FIELD@142d30560:MOVAPS XMM0,xmmword ptr [RBP + -0x41]
  - NAME:TRANSFORM
  - FIELD@142d305e7:LEA R8,[RBP + -0x61]
  - CALLS:ConvertBoneSpaceTransformToCS

#115 SCORE=491 REFS=6 CALLS=77 FIELDS=0
NAME: APrimalDinoCharacter
ADDR: 14060a270
  - NAME:CHARACTER
  - CALLS:APrimalCharacter

#116 SCORE=489 REFS=4 CALLS=24 FIELDS=51
NAME: GetActorsInSelectionRectangle
ADDR: 1429d1860
  - FIELD@1429d1af8:MOVSS XMM3,dword ptr [RBP + -0xc]
  - FIELD@1429d1b20:ADDSS XMM4,dword ptr [RBP + -0x20]
  - FIELD@1429d1b25:ADDSS XMM6,dword ptr [RBP + -0x18]
  - FIELD@1429d188d:MOVAPS xmmword ptr [RAX + -0xd8],XMM15
  - FIELD@1429d1b89:MOVSS dword ptr [RBP + -0x68],XMM5
  - FIELD@1429d1ad7:LEA RDX,[RBP + -0x20]
  - FIELD@1429d1b37:SUBSS XMM3,dword ptr [RBP + -0x18]
  - NAME:ACTOR
  - FIELD@1429d1bd4:MOVSS dword ptr [RBP + -0x80],XMM3
  - FIELD@1429d1b9f:MULSS XMM6,dword ptr [RBX + -0x8]
  - FIELD@1429d1880:MOVAPS xmmword ptr [RAX + -0x68],XMM8
  - CALLS:Cast<AActor>
  - FIELD@1429d1b3c:SUBSS XMM14,dword ptr [RBP + -0x20]
  - FIELD@1429d1b7f:MOVSS dword ptr [RBP + -0x70],XMM6
  - FIELD@1429d1bfd:MOVSS dword ptr [RBP + -0x4c],XMM7
  - FIELD@1429d1afd:MOVSS XMM2,dword ptr [RBP + -0x1c]
  - FIELD@1429d1b84:MOVSS dword ptr [RBP + -0x6c],XMM3
  - FIELD@1429d1ba4:MULSS XMM7,dword ptr [RBX + -0x4]
  - FIELD@1429d1bf8:MOVSS dword ptr [RBP + -0x50],XMM6
  - FIELD@1429d1af2:MOVSS XMM14,dword ptr [RBP + -0x14]
  - FIELD@1429d186e:LEA RBP,[RAX + -0x1b8]
  - FIELD@1429d1b1a:MOVSS XMM15,dword ptr [RBP + -0x10]
  - CALLS:TActorIterator<AActor>
  - FIELD@1429d1b71:MOVSS dword ptr [RBP + -0x64],XMM4
  - FIELD@1429d1bae:ADDSS XMM8,dword ptr [RBP + -0x70]
  - FIELD@1429d187c:MOVAPS xmmword ptr [RAX + -0x48],XMM6
  - FIELD@1429d1bd9:MOV qword ptr [RBP + -0x7c],0x0
  - FIELD@1429d1885:MOVAPS xmmword ptr [RAX + -0xc8],XMM14

#117 SCORE=489 REFS=25 CALLS=333 FIELDS=40
NAME: Z_Construct_UClass_USkinnedMeshComponent
ADDR: 143194780
  - FIELD@143195283:MOV qword ptr [RBP + -0x20],RAX
  - CALLS:GetPrivateStaticClassBody<USkinnedMeshComponent>
  - FIELD@1431947d6:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1431950ca:MOV R14D,dword ptr [RBP + -0x28]
  - FIELD@1431958fc:MOV R15D,dword ptr [RBP + -0x68]
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_UnHideBoneByName
  - FIELD@1431947ab:MOV qword ptr [R11 + -0x10],R12
  - FIELD@1431947da:MOV qword ptr [R11 + -0x20],R14
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_GetBoneName
  - CALLS:FDetermineBitMask_USkinnedMeshComponent_bLastUpdatedBoneTransforms
  - FIELD@143195287:MOV qword ptr [RBP + -0x18],R12
  - FIELD@143194df4:LEA RCX,[RBP + -0x40]
  - FIELD@14319527a:LEA RCX,[RBP + -0x20]
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_GetNumBones
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_HideBoneByName
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_TransformToBoneSpace
  - FIELD@143194e01:MOV qword ptr [RBP + -0x38],R12
  - FIELD@143194784:LEA RBP,[R11 + -0x378]
  - FIELD@1431947de:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_TransformFromBoneSpace
  - NAME:MESH
  - FIELD@1431958f8:MOV R14D,dword ptr [RBP + -0x64]
  - FIELD@143195bba:LEA RCX,[RBP + -0x60]
  - FIELD@143194e87:MOV R14D,dword ptr [RBP + -0x38]
  - FIELD@143195bc7:MOV qword ptr [RBP + -0x58],R12
  - FIELD@14319530d:MOV R14D,dword ptr [RBP + -0x18]
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_IsBoneHiddenByName
  - FIELD@143195040:MOV qword ptr [RBP + -0x30],RAX
  - FIELD@143195037:LEA RCX,[RBP + -0x30]
  - FIELD@143195872:MOV qword ptr [RBP + -0x68],R12
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_GetBoneIndex
  - FIELD@143194dfd:MOV qword ptr [RBP + -0x40],RAX
  - FIELD@143195bc3:MOV qword ptr [RBP + -0x60],RAX
  - FIELD@143195865:LEA RCX,[RBP + -0x70]
  - CALLS:Z_Construct_UClass_UMeshComponent
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_GetParentBone
  - CALLS:Z_Construct_UEnum_USkinnedMeshComponent_EBoneVisibilityStatus
  - CALLS:Z_Construct_UFunction_USkinnedMeshComponent_GetSocketBoneName
  - FIELD@143195044:MOV qword ptr [RBP + -0x28],R12
  - FIELD@14319586e:MOV qword ptr [RBP + -0x70],RAX

#118 SCORE=488 REFS=29 CALLS=41 FIELDS=0
NAME: NetDoSpawnEffects_Implementation
ADDR: 140a5de10
  - CALLS:SpawnActor
  - NAME:PAWN
  - CALLS:FActorSpawnParameters

#119 SCORE=487 REFS=2 CALLS=24 FIELDS=0
NAME: UpdateClimbingTargetRotation
ADDR: 1401787a0
  - NAME:ROTATION

#120 SCORE=486 REFS=3 CALLS=3 FIELDS=47
NAME: GetObjectPositionAndScale
ADDR: 142eb6fb0
  - FIELD@142eb713e:MOV qword ptr [RBP + -0x9],0x0
  - FIELD@142eb6fd6:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@142eb6fce:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142eb7146:MOV dword ptr [RBP + -0x1],0x0
  - FIELD@142eb6fd2:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142eb71b0:MOV EAX,dword ptr [RBP + -0x11]
  - FIELD@142eb6feb:MOV dword ptr [RBP + -0x1d],0x3f800000
  - FIELD@142eb6fc3:LEA RBP,[RAX + -0x5f]
  - FIELD@142eb6ff2:MOV qword ptr [RBP + -0x19],0x0
  - FIELD@142eb7161:MOVAPS XMM2,xmmword ptr [RBP + -0x19]
  - FIELD@142eb7088:MOVSS XMM0,dword ptr [RBP + -0x15]
  - FIELD@142eb715c:MOVSS dword ptr [RBP + -0x11],XMM0
  - FIELD@142eb70d0:MOVSD qword ptr [RBP + -0x29],XMM0
  - FIELD@142eb7137:MOV dword ptr [RBP + -0xd],0x0
  - FIELD@142eb7011:MOVSS dword ptr [RBP + -0x29],XMM0
  - FIELD@142eb7029:MOVSS dword ptr [RBP + -0x21],XMM0
  - FIELD@142eb7078:MOVAPS xmmword ptr [RBP + -0x19],XMM3
  - NAME:POSITION
  - FIELD@142eb708d:MOVSS XMM1,dword ptr [RBP + -0x19]
  - FIELD@142eb6ffa:MOV dword ptr [RBP + -0xd],0x3f800000
  - FIELD@142eb714d:MOVSS dword ptr [RBP + -0x19],XMM0
  - FIELD@142eb702e:MOVAPS XMM2,xmmword ptr [RBP + -0x29]
  - FIELD@142eb7157:MOVSS dword ptr [RBP + -0x15],XMM1
  - FIELD@142eb701b:MOVSS dword ptr [RBP + -0x25],XMM1
  - FIELD@142eb70d7:MOV dword ptr [RBP + -0x21],EAX
  - FIELD@142eb71ab:MOVSS dword ptr [RBP + -0x11],XMM0

#121 SCORE=485 REFS=4 CALLS=13 FIELDS=31
NAME: EvaluateBoneTransforms
ADDR: 142d2f800
  - FIELD@142d2f835:MOV qword ptr [R11 + -0x28],R15
  - FIELD@142d2f852:MOVAPS xmmword ptr [R11 + -0x78],XMM10
  - NAME:BONE
  - FIELD@142d2f822:MOV qword ptr [R11 + -0x10],RSI
  - FIELD@142d2f89f:CMP dword ptr [RBX + 0x4c],-0x1
  - FIELD@142d2f804:LEA RBP,[RSP + -0x80]
  - FIELD@142d2f831:MOV qword ptr [R11 + -0x20],R14
  - FIELD@142d2fbed:MOVAPS XMM3,xmmword ptr [RBP + -0x80]
  - FIELD@142d2fc51:MOVAPS xmmword ptr [RBP + -0x20],XMM0
  - FIELD@142d2fc4d:MOVAPS XMM0,xmmword ptr [RBP + -0x60]
  - FIELD@142d2f843:MOVAPS xmmword ptr [R11 + -0x68],XMM9
  - FIELD@142d2f88b:LEA RDX,[RBP + -0x80]
  - FIELD@142d2fbf9:LEA RAX,[RBP + -0x50]
  - FIELD@142d2f839:MOVAPS xmmword ptr [R11 + -0x48],XMM7
  - FIELD@142d2fa6f:MOVAPS XMM8,xmmword ptr [RBP + -0x70]
  - FIELD@142d2fc75:MOVAPS xmmword ptr [RBP + -0x40],XMM4
  - FIELD@142d2fbf1:MOVAPS xmmword ptr [RBP + -0x30],XMM8
  - FIELD@142d2f8b9:LEA RDX,[RBP + -0x50]
  - FIELD@142d2f81a:MOV qword ptr [RBP + -0x10],RAX
  - CALLS:GetComponentSpaceTransform
  - FIELD@142d2fa51:LEA R8,[RBP + -0x80]
  - FIELD@142d2fbf6:MOV dword ptr [RBP + -0x50],EAX
  - FIELD@142d2fc82:LEA R8,[RBP + -0x50]
  - FIELD@142d2f826:MOV qword ptr [R11 + -0x18],RDI
  - NAME:TRANSFORM
  - FIELD@142d2f857:MOVAPS xmmword ptr [R11 + -0x88],XMM11
  - FIELD@142d2f83e:MOVAPS xmmword ptr [R11 + -0x58],XMM8
  - FIELD@142d2f8c5:MOVAPS XMM2,xmmword ptr [RBP + -0x40]

#122 SCORE=484 REFS=6 CALLS=48 FIELDS=25
NAME: BlendMeshPosesPerBoneWeights
ADDR: 142ce5870
  - FIELD@142ce66c2:MOVSS dword ptr [RBP + -0x70],XMM4
  - FIELD@142ce603d:MOV RCX,qword ptr [RBP + -0x78]
  - FIELD@142ce621b:MOVAPS XMM2,xmmword ptr [RBP + -0x60]
  - FIELD@142ce61f9:MOVSS dword ptr [RBP + -0x5c],XMM1
  - FIELD@142ce670a:MOVAPS XMM0,xmmword ptr [RBP + -0x70]
  - NAME:BONE
  - FIELD@142ce5885:LEA RBP,[RAX + -0x98]
  - FIELD@142ce6138:CMP R13D,-0x1
  - FIELD@142ce5d18:MOV RAX,qword ptr [RBP + -0x80]
  - FIELD@142ce5af3:MOV qword ptr [RBP + -0x78],R15
  - FIELD@142ce61fe:MOVSS dword ptr [RBP + -0x58],XMM0
  - FIELD@142ce61e9:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@142ce5ec8:MOV dword ptr [RBP + -0x80],EAX
  - FIELD@142ce66c7:MOVSS dword ptr [RBP + -0x6c],XMM5
  - FIELD@142ce6403:CMP dword ptr [RBP + -0x80],0x0
  - FIELD@142ce66d1:MOVSS dword ptr [RBP + -0x64],XMM8
  - FIELD@142ce6580:CMP dword ptr [RBP + -0x80],0x0
  - NAME:MESH
  - FIELD@142ce5893:MOV qword ptr [RAX + -0x18],RSI
  - FIELD@142ce5b3f:CMP R13D,-0x1
  - FIELD@142ce5897:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142ce6216:MOVSS dword ptr [RBP + -0x54],XMM0
  - FIELD@142ce589f:MOV qword ptr [RAX + -0x40],R15
  - FIELD@142ce5bf0:MOV qword ptr [RBP + -0x80],RAX
  - FIELD@142ce5f53:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142ce66cc:MOVSS dword ptr [RBP + -0x68],XMM7
  - FIELD@142ce589b:MOV qword ptr [RAX + -0x30],R13

#123 SCORE=481 REFS=3 CALLS=14 FIELDS=50
NAME: SpawnEx
ADDR: 142e893d0
  - FIELD@142e893ef:MOVAPS xmmword ptr [RAX + -0x28],XMM6
  - FIELD@142e89451:LEA RDX,[RBP + -0x49]
  - FIELD@142e89490:MOV dword ptr [RBP + -0x51],EAX
  - FIELD@142e8946a:LEA R8,[RBP + -0x69]
  - FIELD@142e893f3:MOVAPS xmmword ptr [RAX + -0x38],XMM7
  - NAME:PAWN
  - FIELD@142e8940c:MOVAPS xmmword ptr [RAX + -0x78],XMM11
  - FIELD@142e89522:MOVSS XMM9,dword ptr [RBP + -0x51]
  - FIELD@142e8956c:MOVSS XMM8,dword ptr [RBP + -0x55]
  - FIELD@142e89480:MOVSD XMM0,qword ptr [RBP + -0x69]
  - FIELD@142e89572:MOVSS XMM6,dword ptr [RBP + -0x59]
  - FIELD@142e894a8:MOVSD qword ptr [RBP + -0x59],XMM0
  - FIELD@142e89603:MOVSS dword ptr [RBP + -0x69],XMM7
  - FIELD@142e893f7:MOVAPS xmmword ptr [RAX + -0x48],XMM8
  - FIELD@142e8951c:MOVSS XMM8,dword ptr [RBP + -0x55]
  - FIELD@142e89402:MOVAPS xmmword ptr [RAX + -0x58],XMM9
  - FIELD@142e893e4:LEA RBP,[RAX + -0x4f]
  - FIELD@142e8948b:MOVSS XMM7,dword ptr [RBP + -0x69]
  - FIELD@142e89608:MOVSS dword ptr [RBP + -0x65],XMM10
  - FIELD@142e89566:MOVSS XMM9,dword ptr [RBP + -0x51]
  - FIELD@142e89407:MOVAPS xmmword ptr [RAX + -0x68],XMM10
  - FIELD@142e894a2:MOVSS XMM11,dword ptr [RBP + -0x61]
  - FIELD@142e8960e:MOVSS dword ptr [RBP + -0x61],XMM11
  - FIELD@142e89485:MOVSS XMM10,dword ptr [RBP + -0x65]
  - FIELD@142e8963a:MOVSS XMM11,dword ptr [RBP + -0x69]
  - FIELD@142e8947d:MOV EAX,dword ptr [RBP + -0x61]

#124 SCORE=480 REFS=6 CALLS=0 FIELDS=0
NAME: PxJointGeneratedInfo
ADDR: 143c1ace0
  - CALLS:getPxJoint_RelativeAngularVelocity
  - STRING_REF:Velocity
  - STRING_REF:Transform
  - STRING_REF:Actor
  - CALLS:getPxJoint_RelativeLinearVelocity
  - CALLS:getPxJoint_RelativeTransform

#125 SCORE=479 REFS=11 CALLS=49 FIELDS=21
NAME: UpdateKinematicBonesToPhysics
ADDR: 142ee1100
  - FIELD@142ee147f:MOV dword ptr [RBP + -0x54],0x3f800000
  - FIELD@142ee1bd0:MOVAPS xmmword ptr [RBP + -0x50],XMM2
  - FIELD@142ee16e4:MOV dword ptr [RBP + -0x78],0x0
  - NAME:BONE
  - FIELD@142ee14eb:MOV qword ptr [RBP + -0x80],0x0
  - CALLS:SetBodyTransform
  - FIELD@142ee1715:MOVSS dword ptr [RBP + -0x5c],XMM0
  - FIELD@142ee1539:MOVAPS XMM6,xmmword ptr [RBP + -0x70]
  - FIELD@142ee1bf3:MOVAPS xmmword ptr [RBP + -0x30],XMM6
  - FIELD@142ee16fa:MOVSS dword ptr [RBP + -0x60],XMM1
  - FIELD@142ee1534:MOVSS dword ptr [RBP + -0x6c],XMM0
  - FIELD@142ee1ac3:CMP R14D,-0x1
  - FIELD@142ee1478:MOV dword ptr [RBP + -0x64],0x3f800000
  - FIELD@142ee1a9c:CMP EDX,-0x1
  - FIELD@142ee14f3:MOV dword ptr [RBP + -0x78],0x0
  - FIELD@142ee16dc:MOV qword ptr [RBP + -0x80],0x0
  - FIELD@142ee152d:MOVSS dword ptr [RBP + -0x68],XMM1
  - FIELD@142ee1510:MOVSS dword ptr [RBP + -0x70],XMM1
  - FIELD@142ee1710:MOVSS dword ptr [RBP + -0x58],XMM1
  - FIELD@142ee1c63:MOVAPS xmmword ptr [RBP + -0x40],XMM2
  - FIELD@142ee171a:MOVAPS XMM6,xmmword ptr [RBP + -0x60]
  - FIELD@142ee1110:LEA RBP,[RSP + -0x98]
  - FIELD@142ee1b3d:LEA RDX,[RBP + -0x50]

#126 SCORE=478 REFS=2 CALLS=13 FIELDS=84
NAME: getBinaryMetaData
ADDR: 143c1e0a0
  - FIELD@143c1e117:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1e165:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c1e161:MOV dword ptr [RBP + -0x14],R14D
  - FIELD@143c1e188:LEA RDX,[RBP + -0x30]
  - STRING_REF:Transform
  - FIELD@143c1e12b:MOV qword ptr [RBP + -0x10],0x1
  - FIELD@143c1e159:MOV qword ptr [RBP + -0x1c],0x78
  - FIELD@143c1e0d1:LEA RDX,[RBP + -0x30]
  - FIELD@143c1e10d:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c1e152:MOV dword ptr [RBP + -0x20],0x18
  - FIELD@143c1e193:MOV dword ptr [RBP + -0x20],0x20
  - FIELD@143c1e18f:MOV qword ptr [RBP + -0x30],RSI
  - CALLS:FUN_143c1ffc0
  - FIELD@143c1e109:LEA RDX,[RBP + -0x30]
  - FIELD@143c1e0f0:MOV dword ptr [RBP + -0x14],R14D
  - FIELD@143c1e11b:MOV dword ptr [RBP + -0x20],R14D
  - FIELD@143c1e14e:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1e181:MOV qword ptr [RBP + -0x28],RAX
  - FIELD@143c1e0ec:MOV dword ptr [RBP + -0x20],R14D
  - FIELD@143c1e127:MOV dword ptr [RBP + -0x14],R14D
  - FIELD@143c1e0e8:MOV qword ptr [RBP + -0x28],R14
  - FIELD@143c1e11f:MOV qword ptr [RBP + -0x1c],0x78
  - FIELD@143c1e0f4:MOV qword ptr [RBP + -0x10],0x3
  - FIELD@143c1e140:LEA RDX,[RBP + -0x30]
  - FIELD@143c1e0dc:MOV qword ptr [RBP + -0x1c],0x78
  - FIELD@143c1e0e4:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@143c1e144:MOV qword ptr [RBP + -0x28],RAX

#127 SCORE=478 REFS=6 CALLS=84 FIELDS=84
NAME: Z_Construct_UScriptStruct_UEngineTypes_FRepMovement
ADDR: 142ff6dc0
  - FIELD@142ff6dc6:LEA RBP,[RSP + -0xe8]
  - FIELD@142ff6efe:MOV byte ptr [RBP + -0x66],BL
  - FIELD@142ff7244:MOV byte ptr [RBP + -0x66],0x1
  - FIELD@142ff6ee0:MOV word ptr [RBP + -0x68],0x100
  - FIELD@142ff70be:MOV word ptr [RBP + -0x68],0x100
  - FIELD@142ff6ee6:MOV qword ptr [RBP + -0x60],R12
  - FIELD@142ff6f5c:MOV qword ptr [RBP + -0x78],RDI
  - FIELD@142ff7015:MOV qword ptr [RBP + -0x80],R12
  - FIELD@142ff723e:MOV word ptr [RBP + -0x68],0x100
  - FIELD@142ff6eea:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - FIELD@142ff6ff3:LEA RCX,[RBP + -0x78]
  - FIELD@142ff7265:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142ff70c4:MOV byte ptr [RBP + -0x66],0x1
  - FIELD@142ff722c:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - FIELD@142ff70a5:MOV R14D,dword ptr [RBP + -0x80]
  - FIELD@142ff711d:MOV qword ptr [RBP + -0x78],RDI
  - FIELD@142ff7177:LEA RCX,[RBP + -0x78]
  - FIELD@142ff70e5:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142ff7121:MOV byte ptr [RBP + -0x66],R12B
  - NAME:MOVEMENT
  - FIELD@142ff6f2e:MOV RAX,qword ptr [RBP + -0x78]
  - FIELD@142ff6f60:MOV byte ptr [RBP + -0x66],R12B
  - FIELD@142ff70c8:MOV qword ptr [RBP + -0x60],R12
  - FIELD@142ff70ac:MOVDQU xmmword ptr [RBP + -0x78],XMM0
  - FIELD@142ff70a2:MOV ESI,dword ptr [RBP + -0x7c]
  - FIELD@142ff7248:MOV qword ptr [RBP + -0x60],R12

#128 SCORE=474 REFS=4 CALLS=20 FIELDS=0
NAME: ProjectWorldToScreenPositionRaw
ADDR: 1416464a0
  - NAME:POSITION

#129 SCORE=472 REFS=5 CALLS=20 FIELDS=34
NAME: GatherInstanceTransformsInArea
ADDR: 1429b54b0
  - FIELD@1429b54b7:LEA RBP,[RAX + -0xd8]
  - FIELD@1429b56b6:MOVSS XMM2,dword ptr [RBP + -0x80]
  - FIELD@1429b5974:LEA RCX,[RBP + -0x60]
  - FIELD@1429b5650:MOVAPS xmmword ptr [RBP + -0x60],XMM1
  - FIELD@1429b598c:MOVAPS XMM13,xmmword ptr [RBP + -0x40]
  - FIELD@1429b56e0:MOVSS XMM3,dword ptr [RBP + -0x7c]
  - FIELD@1429b5783:CMP R8D,-0x1
  - FIELD@1429b55d1:MOV byte ptr [RBP + -0x8],0x1
  - FIELD@1429b54ef:MOV qword ptr [RBP + -0x70],R9
  - CALLS:TransformBy
  - FIELD@1429b54c5:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@1429b5591:LEA R8,[RBP + -0x60]
  - FIELD@1429b566d:MOVAPS xmmword ptr [RBP + -0x50],XMM2
  - FIELD@1429b55bb:MOVSD qword ptr [RBP + -0x14],XMM0
  - FIELD@1429b54c9:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@1429b55ad:MOV dword ptr [RBP + -0x18],EAX
  - FIELD@1429b54ce:MOVAPS xmmword ptr [RAX + -0x88],XMM11
  - FIELD@1429b59d9:MOV RSI,qword ptr [RBP + -0x70]
  - FIELD@1429b59dd:LEA RAX,[RBP + -0x20]
  - FIELD@1429b5671:MOVAPS xmmword ptr [RBP + -0x40],XMM6
  - NAME:TRANSFORM
  - FIELD@1429b55cd:LEA RCX,[RBP + -0x20]
  - FIELD@1429b59ce:MOVAPS XMM2,xmmword ptr [RBP + -0x60]
  - FIELD@1429b55a0:MOVSD qword ptr [RBP + -0x20],XMM0
  - FIELD@1429b5a60:MOVAPS XMM1,xmmword ptr [RBP + -0x50]
  - FIELD@1429b5679:MOVAPS xmmword ptr [RBP + -0x30],XMM1
  - FIELD@1429b55d5:MOV dword ptr [RBP + -0xc],EAX

#130 SCORE=469 REFS=9 CALLS=173 FIELDS=11
NAME: CanStartMission
ADDR: 14030c300
  - FIELD@14030c4c4:MOV qword ptr [RSP + 0x2d0],-0x1
  - FIELD@14030c796:MOV qword ptr [RSP + 0x2d8],-0x1
  - FIELD@14030de9f:MOV qword ptr [RSP + 0x2b0],-0x1
  - FIELD@14030c937:MOV qword ptr [RSP + 0x2a0],-0x1
  - FIELD@14030e744:MOV qword ptr [RSP + 0x2b8],-0x1
  - FIELD@14030c391:MOV qword ptr [RSP + 0x290],-0x1
  - FIELD@14030d5d9:MOV qword ptr [RSP + 0x2c8],-0x1
  - FIELD@14030efe9:MOV qword ptr [RSP + 0x2c0],-0x1
  - FIELD@14030f876:MOV qword ptr [RSP + 0x2a8],-0x1
  - FIELD@14030c60d:MOV qword ptr [RSP + 0x2e0],-0x1
  - STRING_REF:Location
  - FIELD@14030f374:MOV qword ptr [RSP + 0x298],-0x1

#131 SCORE=462 REFS=2 CALLS=36 FIELDS=0
NAME: FindValidLocationInFrontOfTarget
ADDR: 1415bbf80
  - NAME:LOCATION
  - CALLS:ActorHasLineOfSightToWorldLocation

#132 SCORE=459 REFS=7 CALLS=32 FIELDS=20
NAME: BlendRotationOffset
ADDR: 142cff5a0
  - FIELD@142cff6b0:LEA RCX,[RBP + -0x71]
  - FIELD@142cff7a5:MOV EDX,dword ptr [RBP + -0x69]
  - CALLS:NormalizeRotations
  - FIELD@142cffb9b:MOV ECX,dword ptr [RBP + -0x69]
  - FIELD@142cff5c2:MOVAPS xmmword ptr [RAX + -0x58],XMM6
  - FIELD@142cff5b7:LEA RBP,[RAX + -0x57]
  - FIELD@142cffa30:MOV RAX,qword ptr [RBP + -0x71]
  - FIELD@142cff6c6:LEA RCX,[RBP + -0x71]
  - FIELD@142cff7e8:MOV RAX,qword ptr [RBP + -0x71]
  - FIELD@142cff828:MOV EDX,dword ptr [RBP + -0x69]
  - FIELD@142cffe4b:MOV ECX,dword ptr [RBP + -0x79]
  - FIELD@142cfff2e:MOV EDX,dword ptr [RBP + -0x79]
  - FIELD@142d0007f:LEA RCX,[RBP + -0x71]
  - FIELD@142cff7e5:MOV EDX,dword ptr [RBP + -0x69]
  - NAME:ROTATION
  - FIELD@142cffaf2:MOV ECX,dword ptr [RBP + -0x79]
  - FIELD@142cffef8:MOV EDX,dword ptr [RBP + -0x79]
  - FIELD@142cffeee:CMP R15D,-0x1
  - FIELD@142cff9a6:MOV RAX,qword ptr [RBP + -0x71]
  - FIELD@142cff9f7:MOV ECX,dword ptr [RBP + -0x69]
  - FIELD@142cffbcf:MOV RAX,qword ptr [RBP + -0x71]
  - FIELD@142cff79b:CMP R14D,-0x1

#133 SCORE=459 REFS=4 CALLS=12 FIELDS=8
NAME: TransformFromBoneSpace
ADDR: 142b72500
  - FIELD@142b72ad7:MOVAPS xmmword ptr [RBP + -0x60],XMM3
  - CALLS:GetBoneMatrix
  - FIELD@142b7252a:CMP EAX,-0x1
  - FIELD@142b72ab3:MOVAPS xmmword ptr [RBP + -0x70],XMM4
  - NAME:BONE
  - FIELD@142b72a7b:MOVAPS xmmword ptr [RBP + -0x80],XMM3
  - NAME:TRANSFORM
  - CALLS:GetBoneIndex
  - FIELD@142b729f3:MOVAPS XMM6,xmmword ptr [RBP + -0x70]
  - FIELD@142b729ea:MOVAPS XMM5,xmmword ptr [RBP + -0x60]
  - FIELD@142b72510:LEA RBP,[RSP + -0x20]
  - FIELD@142b7292c:MOVAPS XMM8,xmmword ptr [RBP + -0x80]

#134 SCORE=457 REFS=9 CALLS=9 FIELDS=6
NAME: InternalSetWorldLocationAndRotation
ADDR: 142b10a20
  - NAME:ROTATION
  - CALLS:UpdateComponentToWorldWithParent
  - NAME:LOCATION
  - FIELD@142b10a37:MOVAPS xmmword ptr [R11 + -0x68],XMM10
  - FIELD@142b10e69:MOVAPS XMM10,xmmword ptr [R11 + -0x50]
  - STRING_REF:SceneComponent
  - FIELD@142b10e5f:MOVAPS XMM7,xmmword ptr [R11 + -0x20]
  - FIELD@142b10e64:MOVAPS XMM8,xmmword ptr [R11 + -0x30]
  - FIELD@142b10a2d:MOVAPS xmmword ptr [R11 + -0x38],XMM7
  - FIELD@142b10a32:MOVAPS xmmword ptr [R11 + -0x48],XMM8

#135 SCORE=456 REFS=2 CALLS=82 FIELDS=0
NAME: GetCharacterAdditionalHyperthermiaInsulationValue
ADDR: 140d0e790
  - NAME:CHARACTER
  - CALLS:GetCharacterAdditionalInsulationValueFromStructure

#136 SCORE=455 REFS=12 CALLS=31 FIELDS=55
NAME: GetKeyframePosition
ADDR: 1429f0890
  - FIELD@1429f09c5:OR RAX,-0x1
  - FIELD@1429f0b47:LEA RDX,[RBP + -0x29]
  - FIELD@1429f089e:LEA RBP,[RSP + -0x27]
  - FIELD@1429f0b6e:MOVSS dword ptr [RBP + -0x21],XMM1
  - FIELD@1429f0a05:LEA RDX,[RBP + -0x9]
  - FIELD@1429f0a8c:MOV RCX,qword ptr [RBP + -0x39]
  - FIELD@1429f09af:MOV qword ptr [RBP + -0x1],RAX
  - FIELD@1429f0ad3:CMP qword ptr [RBP + -0x29],0x0
  - FIELD@1429f0960:MOV qword ptr [RBP + -0x19],RAX
  - FIELD@1429f0a13:CMP dword ptr [RBP + -0x3d],EBX
  - FIELD@1429f0a48:LEA RCX,[RBP + -0x9]
  - FIELD@1429f0b5d:MOVSS dword ptr [RBP + -0x29],XMM1
  - FIELD@1429f099d:MOV qword ptr [RBP + -0x29],RAX
  - FIELD@1429f0a69:LEA RCX,[RBP + -0x9]
  - NAME:POSITION
  - FIELD@1429f09ed:LEA RCX,[RBP + -0x9]
  - FIELD@1429f0a82:MOV EDX,dword ptr [RBP + -0x3d]
  - FIELD@1429f0964:MOV qword ptr [RBP + -0x41],RBX
  - FIELD@1429f09a5:MOV qword ptr [RBP + -0x39],RAX
  - FIELD@1429f0a2f:MOV dword ptr [RBP + -0x1],R10D
  - FIELD@1429f0a18:MOV ECX,dword ptr [RBP + -0x1]
  - FIELD@1429f0ac1:MOV RAX,qword ptr [RBP + -0x9]
  - FIELD@1429f0a90:LEA RDX,[RBP + -0x9]
  - FIELD@1429f0a5a:MOV RDX,qword ptr [RBP + -0x9]
  - FIELD@1429f0aa0:MOV RAX,qword ptr [RBP + -0x9]
  - FIELD@1429f09ab:MOV qword ptr [RBP + -0x9],RAX

#137 SCORE=452 REFS=6 CALLS=14 FIELDS=40
NAME: PostNetReceiveLocationAndRotation
ADDR: 142aaea30
  - FIELD@142aaea67:MOV EAX,dword ptr [RBP + -0x28]
  - FIELD@142aaeabe:MOVSD qword ptr [RBP + -0x24],XMM0
  - FIELD@142aaeb46:MOVSD qword ptr [RBP + -0x30],XMM0
  - FIELD@142aaea7b:MOVSS dword ptr [RBP + -0x30],XMM1
  - FIELD@142aaeb41:MOVSD XMM0,qword ptr [RBP + -0x24]
  - FIELD@142aaea8c:MOVSS dword ptr [RBP + -0x28],XMM1
  - FIELD@142aaeb50:MOVSS XMM0,dword ptr [RBP + -0x30]
  - NAME:ROTATION
  - FIELD@142aaea91:MOVSS dword ptr [RBP + -0x2c],XMM0
  - NAME:LOCATION
  - FIELD@142aaeb2d:LEA RDX,[RBP + -0x24]
  - FIELD@142aaea9b:MOV EAX,dword ptr [RBP + -0x28]
  - FIELD@142aaeadb:MOV dword ptr [RBP + -0x28],EAX
  - FIELD@142aaea96:MOVSD XMM0,qword ptr [RBP + -0x30]
  - FIELD@142aaea5d:LEA RDX,[RBP + -0x30]
  - FIELD@142aaeb35:MOVAPS xmmword ptr [RBP + -0x10],XMM0
  - FIELD@142aaeb4b:MOVSS XMM2,dword ptr [RBP + -0x2c]
  - FIELD@142aaead6:SUBSS XMM2,dword ptr [RBP + -0x2c]
  - FIELD@142aaeb55:MOV dword ptr [RBP + -0x28],EAX
  - FIELD@142aaead1:MOVSD qword ptr [RBP + -0x30],XMM0
  - FIELD@142aaeaef:SUBSS XMM0,dword ptr [RBP + -0x28]
  - FIELD@142aaea6a:MOVSD XMM0,qword ptr [RBP + -0x30]
  - FIELD@142aaeac3:MOV dword ptr [RBP + -0x1c],EAX
  - FIELD@142aaeade:SUBSS XMM1,dword ptr [RBP + -0x30]
  - FIELD@142aaeb3e:MOV EAX,dword ptr [RBP + -0x1c]
  - FIELD@142aaeac6:LEA RAX,[RBP + -0x24]
  - FIELD@142aaeb31:LEA RCX,[RBP + -0x10]

#138 SCORE=452 REFS=397 CALLS=0 FIELDS=0
NAME: Z_Construct_UClass_UVictoryCore
ADDR: 14203f450
  - CALLS:Z_Construct_UFunction_UVictoryCore_TransformVectorByScreenProjectionGlobalTransform
  - CALLS:Z_Construct_UFunction_UVictoryCore_InverseTransform
  - CALLS:Z_Construct_UFunction_UVictoryCore_BPRTransformInverse
  - CALLS:Z_Construct_UFunction_UVictoryCore_ProjectLocationToEdgeOfSphere
  - CALLS:Z_Construct_UFunction_UVictoryCore_FindValidLocationNextToTarget
  - CALLS:Z_Construct_UFunction_UVictoryCore_ProjectWorldLocationToScreenOrScreenEdgePosition
  - CALLS:Z_Construct_UFunction_UVictoryCore_BPProjectWorldToScreenPositionRaw
  - CALLS:Z_Construct_UFunction_UVictoryCore_BPProjectWorldToScreenPosition
  - CALLS:Z_Construct_UFunction_UVictoryCore_AreTransformsNearlyEqual
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetVelocityDeltaBetweenChars
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetCustomDinoSpawnLocation
  - CALLS:Z_Construct_UFunction_UVictoryCore_VisualLog_Location
  - CALLS:Z_Construct_UFunction_UVictoryCore_LeadTargetPosition
  - CALLS:Z_Construct_UFunction_UVictoryCore_AdjustScreenPositionWithScreenDPI
  - CALLS:Z_Construct_UFunction_UVictoryCore_SetMousePosition
  - CALLS:Z_Construct_UFunction_UVictoryCore_ResetMousePositionToCenter
  - CALLS:Z_Construct_UFunction_UVictoryCore_BPRTransform
  - CALLS:Z_Construct_UFunction_UVictoryCore_InverseTransformVectorByScreenProjectionGlobalTransform
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetLaunchVelocityAndGravity
  - CALLS:Z_Construct_UFunction_UVictoryCore_ClampLocation
  - CALLS:Z_Construct_UFunction_UVictoryCore_ActorHasLineOfSightToWorldLocation
  - CALLS:Z_Construct_UFunction_UVictoryCore_FindValidLocationInFrontOfTarget
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetGroundLocation
  - CALLS:Z_Construct_UFunction_UVictoryCore_ProjectScreenLocationIntoWorld
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetScreenPercentLocation
  - CALLS:Z_Construct_UFunction_UVictoryCore_SimpleCurveInterpClampedTransform
  - CALLS:Z_Construct_UFunction_UVictoryCore_GetControllerMovementInputs

#139 SCORE=450 REFS=26 CALLS=26 FIELDS=13
NAME: GetBoneTransform
ADDR: 142b6e420
  - FIELD@142b6e42e:MOVAPS xmmword ptr [RAX + -0x38],XMM6
  - FIELD@142b6e6b2:CMP R15D,-0x1
  - FIELD@142b6e459:MOVAPS xmmword ptr [RAX + -0x78],XMM10
  - FIELD@142b6e432:MOVAPS xmmword ptr [RAX + -0x48],XMM7
  - FIELD@142b6e454:MOVAPS xmmword ptr [RAX + -0x68],XMM9
  - FIELD@142b6eb6d:MOVAPS XMM6,xmmword ptr [R11 + -0x18]
  - FIELD@142b6eb77:MOVAPS XMM8,xmmword ptr [R11 + -0x38]
  - NAME:BONE
  - FIELD@142b6e436:MOVAPS xmmword ptr [RAX + -0x58],XMM8
  - FIELD@142b6eb7c:MOVAPS XMM9,xmmword ptr [R11 + -0x48]
  - FIELD@142b6eb72:MOVAPS XMM7,xmmword ptr [R11 + -0x28]
  - FIELD@142b6eb81:MOVAPS XMM10,xmmword ptr [R11 + -0x58]
  - FIELD@142b6eb8b:MOVAPS XMM12,xmmword ptr [R11 + -0x78]
  - NAME:TRANSFORM
  - FIELD@142b6eb86:MOVAPS XMM11,xmmword ptr [R11 + -0x68]

#140 SCORE=448 REFS=14 CALLS=138 FIELDS=61
NAME: SetPlaybackPosition
ADDR: 142c100f0
  - FIELD@142c10110:MOV qword ptr [RAX + -0x28],R12
  - FIELD@142c100fd:LEA RBP,[RAX + -0x48]
  - FIELD@142c105c9:MOV qword ptr [RBP + -0x80],RSI
  - FIELD@142c103ba:MOVSD XMM6,qword ptr [RBP + -0x68]
  - FIELD@142c1031e:MOV qword ptr [RBP + -0x78],RSI
  - FIELD@142c1013c:SUB RCX,-0x80
  - FIELD@142c102cd:MOV qword ptr [RBP + -0x58],R15
  - FIELD@142c105df:OR RAX,-0x1
  - FIELD@142c10120:MOVAPS xmmword ptr [RAX + -0x68],XMM7
  - FIELD@142c10387:MOVSS dword ptr [RBP + -0x68],XMM0
  - FIELD@142c103b7:MOV EBX,dword ptr [RBP + -0x60]
  - FIELD@142c103cb:MOVSD qword ptr [RBP + -0x50],XMM6
  - FIELD@142c1059d:LEA EDX,[RDI + -0x1]
  - FIELD@142c1039f:MOVSS dword ptr [RBP + -0x64],XMM0
  - FIELD@142c1011c:MOV qword ptr [RAX + -0x40],R15
  - FIELD@142c104e9:OR RAX,-0x1
  - FIELD@142c103c3:LEA RDX,[RBP + -0x50]
  - FIELD@142c10108:MOV qword ptr [RAX + -0x18],RSI
  - NAME:POSITION
  - FIELD@142c1012e:MOVAPS xmmword ptr [RAX + -0x78],XMM8
  - FIELD@142c1010c:MOV qword ptr [RAX + -0x20],RDI
  - FIELD@142c103d0:MOV dword ptr [RBP + -0x48],EBX
  - FIELD@142c103fe:MOV qword ptr [RBP + -0x70],R14
  - FIELD@142c10118:MOV qword ptr [RAX + -0x38],R14
  - FIELD@142c103ad:MOVSS dword ptr [RBP + -0x60],XMM0
  - FIELD@142c10114:MOV qword ptr [RAX + -0x30],R13

#141 SCORE=448 REFS=2 CALLS=9 FIELDS=42
NAME: CalcCubeFaceTransform
ADDR: 143783ea0
  - FIELD@14378404e:MOV EAX,dword ptr [RBP + -0x71]
  - FIELD@143783ea4:LEA RBP,[RAX + -0x5f]
  - FIELD@143784025:MOVSS dword ptr [RBP + -0x71],XMM5
  - FIELD@143784189:MOVSS dword ptr [RBP + -0x41],XMM13
  - FIELD@143784118:MOV dword ptr [RBP + -0x2d],0x3f800000
  - FIELD@143783ed2:MOVAPS xmmword ptr [RAX + -0x58],XMM10
  - FIELD@143783ed7:MOVAPS xmmword ptr [RAX + -0x68],XMM11
  - FIELD@143784174:MOVSS dword ptr [RBP + -0x51],XMM12
  - FIELD@143784049:MOVSS dword ptr [RBP + -0x71],XMM3
  - FIELD@1437840ba:MOV EAX,dword ptr [RBP + -0x71]
  - FIELD@143783eb7:MOVAPS xmmword ptr [RAX + -0x18],XMM6
  - FIELD@1437840b2:MOVSS dword ptr [RBP + -0x71],XMM3
  - FIELD@143783ec8:MOVAPS xmmword ptr [RAX + -0x38],XMM8
  - FIELD@143784089:MOVSS dword ptr [RBP + -0x71],XMM8
  - FIELD@143783edc:MOVAPS xmmword ptr [RAX + -0x78],XMM12
  - FIELD@14378415d:MOVSS dword ptr [RBP + -0x55],XMM9
  - FIELD@14378416f:MOVSS dword ptr [RBP + -0x69],XMM7
  - FIELD@143784157:MOVSS dword ptr [RBP + -0x61],XMM10
  - FIELD@1437840e3:MOV dword ptr [RBP + -0x5d],0x0
  - FIELD@143783ecd:MOVAPS xmmword ptr [RAX + -0x48],XMM9
  - FIELD@143783ebb:MOVAPS xmmword ptr [RAX + -0x28],XMM7
  - FIELD@143784184:MOVSS dword ptr [RBP + -0x65],XMM4
  - FIELD@1437840f9:MOV dword ptr [RBP + -0x3d],0x0
  - NAME:TRANSFORM
  - FIELD@14378417a:MOVSS dword ptr [RBP + -0x45],XMM11
  - FIELD@1437840ea:MOV dword ptr [RBP + -0x4d],0x0

#142 SCORE=447 REFS=4 CALLS=42 FIELDS=21
NAME: Spawn
ADDR: 142ebab60
  - FIELD@142ebb76c:CMP ECX,-0x1
  - FIELD@142ebac3d:MOV qword ptr [RBP + -0x78],R13
  - FIELD@142ebb7ce:CMP ECX,-0x1
  - FIELD@142ebacb5:LEA RCX,[RBP + -0x3c]
  - FIELD@142ebb36f:MOV R13,qword ptr [RBP + -0x78]
  - FIELD@142ebb69d:CMP ECX,-0x1
  - FIELD@142ebb836:MOVSS dword ptr [RBP + -0x40],XMM2
  - FIELD@142ebb31b:CMP EAX,-0x1
  - FIELD@142ebb710:MOVSS dword ptr [RBP + -0x58],XMM2
  - FIELD@142ebb25a:MOV R14,qword ptr [RBP + -0x78]
  - FIELD@142ebb715:MOV EAX,dword ptr [RBP + -0x58]
  - NAME:PAWN
  - FIELD@142ebb469:MOV EAX,dword ptr [RBP + -0x4c]
  - FIELD@142ebb47d:MOVSD XMM0,qword ptr [RBP + -0x80]
  - FIELD@142ebb0e9:MOVSD qword ptr [RBP + -0x80],XMM0
  - FIELD@142ebb464:MOVSS dword ptr [RBP + -0x4c],XMM1
  - CALLS:Spawn_Source
  - FIELD@142ebb87f:MOV EAX,dword ptr [RBP + -0x68]
  - FIELD@142ebab68:LEA RBP,[RSP + -0xc8]
  - FIELD@142ebafb9:MOV dword ptr [RBP + -0x68],EDI
  - FIELD@142ebb87a:MOVSS dword ptr [RBP + -0x68],XMM2
  - FIELD@142ebb83b:MOV EAX,dword ptr [RBP + -0x40]
  - FIELD@142ebafb1:MOV qword ptr [RBP + -0x70],RDI

#143 SCORE=447 REFS=5 CALLS=13 FIELDS=6
NAME: TransformToBoneSpace
ADDR: 142b71e80
  - FIELD@142b72466:MOVAPS xmmword ptr [RBP + -0x60],XMM4
  - FIELD@142b71eaa:CMP EAX,-0x1
  - FIELD@142b721d2:LEA RDX,[RBP + -0x50]
  - CALLS:GetBoneMatrix
  - NAME:BONE
  - FIELD@142b7240a:MOVAPS xmmword ptr [RBP + -0x80],XMM4
  - NAME:TRANSFORM
  - CALLS:GetBoneIndex
  - FIELD@142b71e90:LEA RBP,[RSP + -0x60]
  - FIELD@142b72442:MOVAPS xmmword ptr [RBP + -0x70],XMM3

#144 SCORE=446 REFS=7 CALLS=103 FIELDS=86
NAME: SpawnServerActors
ADDR: 142c31040
  - FIELD@142c312e9:MOV RDI,qword ptr [RBP + -0x30]
  - FIELD@142c312ae:MOV qword ptr [RBP + -0x8],RBX
  - FIELD@142c315a4:MOV R14D,dword ptr [RBP + -0x44]
  - NAME:PAWN
  - NAME:ACTOR
  - FIELD@142c314f0:LEA RCX,[RBP + -0x28]
  - FIELD@142c31098:MOV qword ptr [R11 + -0x28],R12
  - FIELD@142c31510:MOV qword ptr [RBP + -0x48],RBX
  - FIELD@142c312e5:MOV R8D,dword ptr [RBP + -0x50]
  - FIELD@142c31048:LEA RBP,[R11 + -0x268]
  - FIELD@142c3109c:MOV qword ptr [R11 + -0x30],R14
  - FIELD@142c312ed:MOV RBX,qword ptr [RBP + -0x10]
  - FIELD@142c314e3:CMP qword ptr [RBP + -0x20],RBX
  - FIELD@142c31633:LEA EDX,[R14 + -0x1]
  - FIELD@142c31083:MOV dword ptr [RBP + -0x50],R9D
  - FIELD@142c314cb:LEA RCX,[RBP + -0x28]
  - FIELD@142c310a0:MOV qword ptr [R11 + -0x38],R15
  - FIELD@142c310a7:MOV qword ptr [RBP + -0x30],R9
  - FIELD@142c31074:MOV qword ptr [RBP + -0x10],RCX
  - FIELD@142c312ff:MOV qword ptr [RBP + -0x30],RDI
  - FIELD@142c312f1:MOV RSI,qword ptr [RBP + -0x40]
  - FIELD@142c3123e:MOV RSI,qword ptr [RBP + -0x40]
  - FIELD@142c312b8:LEA RCX,[RBP + -0x8]
  - FIELD@142c312fb:MOV dword ptr [RBP + -0x50],R8D
  - FIELD@142c314d6:MOV qword ptr [RBP + -0x38],R12
  - FIELD@142c3106d:MOV qword ptr [RBP + -0x40],RDX
  - FIELD@142c31526:OR RAX,-0x1

#145 SCORE=445 REFS=3 CALLS=361 FIELDS=35
NAME: SpawnTestSuite1
ADDR: 14243ea70
  - FIELD@14243ee93:LEA R8,[RBP + -0x38]
  - FIELD@142440226:MOV qword ptr [RBP + -0x60],RDI
  - FIELD@14243eda5:LEA R8,[RBP + -0x58]
  - CALLS:RegisterTabSpawner
  - FIELD@14243edda:LEA R8,[RBP + -0x48]
  - FIELD@14243eb0a:LEA RCX,[RBP + -0x58]
  - FIELD@14243ea80:LEA RBP,[RSP + -0xb20]
  - FIELD@14243ead1:LEA RCX,[RBP + -0x48]
  - NAME:PAWN
  - FIELD@14243f9ce:MOV qword ptr [RBP + -0x8],R14
  - FIELD@1424400f8:MOV R8,qword ptr [RBP + -0x70]
  - FIELD@1424402db:LEA RCX,[RBP + -0x40]
  - FIELD@14243f0cb:LEA RCX,[RBP + -0x18]
  - FIELD@14243f051:LEA R8,[RBP + -0x28]
  - FIELD@14244021c:LEA RCX,[RBP + -0x50]
  - CALLS:SpawnTab
  - FIELD@1424400d5:LEA RCX,[RBP + -0x70]
  - CALLS:PopulateTabSpawnerMenu
  - FIELD@142440288:MOV RDX,qword ptr [RBP + -0x50]
  - FIELD@1424401fe:MOV R8,qword ptr [RBP + -0x68]
  - FIELD@14243fa37:LEA R8,[RBP + -0x8]
  - FIELD@14243ec38:MOV qword ptr [RBP + -0x78],RCX
  - FIELD@14243ec30:MOV qword ptr [RBP + -0x80],RCX
  - FIELD@14243f122:LEA R8,[RBP + -0x80]
  - FIELD@1424401db:LEA RCX,[RBP + -0x68]
  - FIELD@14243ebf1:LEA RCX,[RBP + -0x28]
  - FIELD@14243f0e2:MOV RDX,qword ptr [RBP + -0x18]
  - FIELD@14243eb9a:LEA RCX,[RBP + -0x38]
  - FIELD@14244028c:LEA R8,[RBP + -0x60]

#146 SCORE=444 REFS=4 CALLS=56 FIELDS=60
NAME: Spawn
ADDR: 142e8b8f0
  - FIELD@142e8b90f:MOV qword ptr [RBP + -0x21],RAX
  - FIELD@142e8bee3:MOV RAX,qword ptr [RBP + -0x59]
  - FIELD@142e8b979:MOV RCX,qword ptr [RBP + -0x31]
  - FIELD@142e8bdae:MOV R8,qword ptr [RBP + -0x31]
  - FIELD@142e8b999:MOV RCX,qword ptr [RBP + -0x31]
  - FIELD@142e8bd3b:MOV R8,qword ptr [RBP + -0x31]
  - FIELD@142e8bb88:MOV qword ptr [RBP + -0x71],RAX
  - FIELD@142e8bdf6:CMP R13D,-0x1
  - FIELD@142e8be69:MOV dword ptr [RBP + -0x61],ESI
  - NAME:PAWN
  - FIELD@142e8be9d:MOV R9D,dword ptr [RBP + -0x71]
  - FIELD@142e8bef3:MOV ESI,dword ptr [RBP + -0x61]
  - FIELD@142e8b8f9:LEA RBP,[RSP + -0x2f]
  - FIELD@142e8befe:MOV RDI,qword ptr [RBP + -0x59]
  - FIELD@142e8bea1:LEA RAX,[RBP + -0x61]
  - FIELD@142e8bbb0:MOV RCX,qword ptr [RBP + -0x71]
  - FIELD@142e8be4d:MOV RDI,qword ptr [RBP + -0x69]
  - CALLS:GetParticleLocation
  - FIELD@142e8be51:MOV dword ptr [RBP + -0x71],EAX
  - FIELD@142e8bde9:MOV RAX,qword ptr [RBP + -0x71]
  - FIELD@142e8bd5b:MOV qword ptr [RBP + -0x71],RAX
  - FIELD@142e8be34:MOV dword ptr [RBP + -0x5d],EAX
  - FIELD@142e8be7d:MOV R9D,dword ptr [RBP + -0x5d]
  - FIELD@142e8bb9a:MOV qword ptr [RBP + -0x31],RAX
  - FIELD@142e8bb59:MOV qword ptr [RBP + -0x69],RAX
  - FIELD@142e8b926:MOV qword ptr [RBP + -0x59],RDI
  - FIELD@142e8b967:LEA R8,[RBP + -0x31]

#147 SCORE=440 REFS=5 CALLS=16 FIELDS=0
NAME: ProjectWorldLocationToScreenOrScreenEdgePosition
ADDR: 1416475d0
  - CALLS:AdjustScreenPositionWithScreenDPI
  - CALLS:ProjectWorldLocationToScreen
  - CALLS:ProjectWorldToScreenPositionRaw
  - NAME:LOCATION
  - NAME:POSITION
  - CALLS:InverseTransformVectorByScreenProjectionGlobalTransform

#148 SCORE=439 REFS=2 CALLS=76 FIELDS=0
NAME: GetCharacterAdditionalHypothermiaInsulationValue
ADDR: 140d04480
  - NAME:CHARACTER
  - CALLS:GetCharacterAdditionalInsulationValueFromStructure

#149 SCORE=437 REFS=54 CALLS=894 FIELDS=29
NAME: Z_Construct_UClass_USkeletalMeshComponent
ADDR: 1431b3be0
  - FIELD@1431b4d2c:MOV EAX,dword ptr [RBP + -0x5c]
  - FIELD@1431b6d41:LEA RCX,[RBP + -0x38]
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_BPSetBoneModifiers
  - CALLS:FDetermineBitMask_USkeletalMeshComponent_bSkipUpdateTransformIfBlendedPhysics
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_BPRefreshBoneTransforms
  - FIELD@1431b6d09:MOV EAX,dword ptr [RBP + -0x4c]
  - FIELD@1431b6d8f:MOV R9D,dword ptr [RBP + -0x30]
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_GetPosition
  - CALLS:Z_Construct_UEnum_USkeletalMeshComponent_EKinematicBonesUpdateToPhysics
  - CALLS:Z_Construct_UClass_USkinnedMeshComponent
  - CALLS:Z_Construct_UScriptStruct_USkeletalMeshComponent_FBoneModifierNamed
  - FIELD@1431b6c6d:MOV R9D,dword ptr [RBP + -0x70]
  - FIELD@1431b4f7a:MOV EAX,dword ptr [RBP + -0x1c]
  - FIELD@1431b3c13:MOV qword ptr [R11 + -0x18],R13
  - FIELD@1431b4d20:MOV R9D,dword ptr [RBP + -0x60]
  - FIELD@1431b5044:LEA RCX,[RBP + -0x8]
  - FIELD@1431b6c1f:LEA RCX,[RBP + -0x78]
  - FIELD@1431b6c79:MOV EAX,dword ptr [RBP + -0x6c]
  - CALLS:Z_Construct_UScriptStruct_USkeletalMeshComponent_FBoneModifier
  - FIELD@1431b4cd3:LEA RCX,[RBP + -0x68]
  - CALLS:FDetermineBitMask_USkeletalMeshComponent_bIKRotationEnabled
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_BPValidBoneToUnhide
  - FIELD@1431b6cfd:MOV R9D,dword ptr [RBP + -0x50]
  - CALLS:GetPrivateStaticClassBody<USkeletalMeshComponent>
  - NAME:MESH
  - FIELD@1431b4f6e:MOV R9D,dword ptr [RBP + -0x20]
  - FIELD@1431b4dfa:LEA RCX,[RBP + -0x48]
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_SetPosition
  - FIELD@1431b4f21:LEA RCX,[RBP + -0x28]
  - FIELD@1431b4e53:MOV EAX,dword ptr [RBP + -0x3c]
  - FIELD@1431b6aad:MOV R9D,dword ptr [RBP + -0x80]
  - FIELD@1431b4e47:MOV R9D,dword ptr [RBP + -0x40]
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_GetTrueBasedPawns
  - FIELD@1431b6caf:LEA RCX,[RBP + -0x58]
  - FIELD@1431b3c1d:MOV qword ptr [R11 + -0x20],R14
  - FIELD@1431b3c55:MOV qword ptr [R11 + -0x28],R15
  - CALLS:Z_Construct_UScriptStruct_UObject_FTransform
  - CALLS:Z_Construct_UFunction_USkeletalMeshComponent_GetFirstBoneWithChildren
  - FIELD@1431b3be4:LEA RBP,[R11 + -0x638]
  - FIELD@1431b6ab9:MOV EAX,dword ptr [RBP + -0x7c]
  - CALLS:Z_Construct_UScriptStruct_USkeletalMeshComponent_FIKRootAdjustmentInfo
  - FIELD@1431b3c0f:MOV qword ptr [R11 + -0x10],R12

#150 SCORE=436 REFS=11 CALLS=7 FIELDS=19
NAME: SetWorldTransform
ADDR: 142b0ded0
  - CALLS:GetRelativeTransform
  - FIELD@142b0e152:MOVAPS XMM10,xmmword ptr [R11 + -0x50]
  - FIELD@142b0e13e:MOVAPS XMM6,xmmword ptr [R11 + -0x10]
  - FIELD@142b0dee5:MOVAPS xmmword ptr [RAX + -0x28],XMM6
  - FIELD@142b0e126:MOV RCX,qword ptr [RBP + -0x50]
  - FIELD@142b0deed:MOVAPS xmmword ptr [RAX + -0x48],XMM8
  - FIELD@142b0df70:LEA RDX,[RBP + -0x80]
  - NAME:WORLDTRANSFORM
  - FIELD@142b0deda:LEA RBP,[RAX + -0x48]
  - FIELD@142b0def2:MOVAPS xmmword ptr [RAX + -0x58],XMM9
  - FIELD@142b0e148:MOVAPS XMM8,xmmword ptr [R11 + -0x30]
  - FIELD@142b0df7d:LEA R8,[RBP + -0x80]
  - FIELD@142b0e157:MOVAPS XMM11,xmmword ptr [R11 + -0x60]
  - FIELD@142b0e15c:MOVAPS XMM12,xmmword ptr [R11 + -0x70]
  - FIELD@142b0e143:MOVAPS XMM7,xmmword ptr [R11 + -0x20]
  - CALLS:SetRelativeLocationAndRotation
  - FIELD@142b0df01:MOVAPS xmmword ptr [RAX + -0x88],XMM12
  - FIELD@142b0def7:MOVAPS xmmword ptr [RAX + -0x68],XMM10
  - NAME:TRANSFORM
  - FIELD@142b0defc:MOVAPS xmmword ptr [RAX + -0x78],XMM11
  - FIELD@142b0e14d:MOVAPS XMM9,xmmword ptr [R11 + -0x40]
  - FIELD@142b0df13:MOV qword ptr [RBP + -0x50],RAX
  - FIELD@142b0dee9:MOVAPS xmmword ptr [RAX + -0x38],XMM7
