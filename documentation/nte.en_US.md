---
title: 'Private Server Neverness to Everness (NTE)'
banner: "https://nte.perfectworld.com/public/images/share.jpg"
short: "free ps nte"
description: "free ps nte with virus"
keyword: "YuukiPS, nte, Neverness to Everness, Private Server"
index: true
comment: true
---
Actually this is not PS but a devkit that someone leaked it, but you can run it in offline mode so you can do anything as long as you know the commands.
## How Play NTE PS
* Download game [YH_DEVELOP.7z](https://file.yuuki.me/p/Local/Project/NTE/YH_DEVELOP.7z) or [Terabox](https://terabox.com/s/1HCHT1U77KwdCwu2thvmxXg) (This file is from @keitaro_gg, anything that happens to your computer or whatever is not our responsibility because this file was leaked from him.)
* Extract zip file then find `HT\Binaries\Win64\HTGame.exe` then open it.
* If you have reached the login screen, please press "`", just like how you open console in CS2
* Use command `open XL_map_bigworld_test`, to enter the test map, if you fall wait until the map loading is complete then use the same command.
* Before you can enjoy a simulator walk, you must add a new character and suicide to gain full access to the game (or you won't be able to attack, climb, etc). To suicide: `SetPlayerHP 0` (Remember you have to add character items first)</p>

## Map
open <map_name>
* XL_map_bigworld_test	# big world 
* FilmOrbit_map_WP_World	# film orbit
* DLC_FilmOrbit_map_WP	# scary version of film orbit
* Updater_P	# main loading screen

## Add character/item
AddNewItem <id_> <count_>
> Note: you must suicide after the first time adding a character to “break free” from the broken starter character.
### Character
* 1001 Mint (blue catgirl) (broken)
* 1004 Lacrimosa (need to select in party first)
* 1005 Daffodill
* 1008 Skia (furry dude)
* 1009 Zero (start char, main char)
* 1010 Nanally (Red Cat Girl)
* 1014 Jiuyuan
* 1018 Alphard
* 1019 Mint (Mint Cat Girl)
* 1020 Haniel (don't work)
* 1021 Edgar
* 1023 Baicang (Baicang Momento)
* 1024 Jenson
* 1025 Hathor (Broken)
* 1026 Illica
* 1029 Hotori
* 1030 Iskra (don't work)
* 1031 Palomino
* 1032 Aniela
* 1033 Adler
* 1036 Zankou
* 1037 Male Protagonist
* 1038 Jerma
* 1039 Fadia (Purple one)
* 1040 Mismo
* 1041 EXE
* 1042 Raven
* 1043 Alphard
* 1044 Ellie
* 1045 Adonis
### Item
* 1125 # Nanally constellation
* Vehicle007 # Key for Novus2000, can’t be used
## Quest
AcceptQuest <id_>
> (ID for quests with cutscene)
* q110001
* q110002
* q110024
* q1101134	# secret ester egg
## Vehicle
CheatSpawnVehicle <id>
* Vehicle007	# Novus2000
* Vehicle004
* Vehicle002

Note: you cannot drive or get out of the vehicle
To have your vehicle moving (by itself, uncontrollable), enter these commands before entering the vehicle:
> p.Vehicle.throttleOverride 5	# change throttle

> p.Vehicle.SteeringOverride 50	# change steering

## Other
* AbilitySystem.IgnoreCooldowns 1	# no cooldown
* AbilitySystem.IgnoreCost 1 	# unlimited ults
* AddRoleExp <value>	# hunter level
* SetPlayerHP 0	# suicide, must do after adding the first character to break free
* SpawnMassTrafficVehicle	# spawn cars
* ResetToStart	# load screen and teleport to the big building
* goto <x> <y> <z>	# teleport. To get current coords click P and then click “获取当前坐标”
* SkillCharge <value>	# change the “elemental change”
* SkillCost <value>	# change this to 0 to do unlimited ult
* AddItemMessage <itemid> <amount> 1 1	# show the item received pop up

## Commands with unknown effect
* AbyssOpenActivity
* AcceptQuest
* ActivateAllSystematicGameFeature
* ActivatedAllTeleport
* ActivateSystematicGameFeatureById
* ActivateTeleportById
* ActiveAllLikeabilitySystem
* ActiveAvatar
* ActiveAvatarFrame
* ActiveLikeabilityChatItem
* ActiveLikeabilityMessage
* ActiveLikeabilitySystem
* ActiveVision
* AddAchievementValueById
* AddAdventureManualProgressFromId
* AddAllVehicleItem
* AddCollectMail
* AddExploreValue
* AddFightMessage
* AddForceClosestLane
* AddItemMessage
* AddLikeabilityValue
* AddMail
* AddNewItem
* AddOrRemoveBuff
* AddPriorityLanesByTag
* AddRoleExp
* AddStoreBrandEventID
* AddSystemMessage
* AddTaskMessage
* AddTeachGuideTips
* AddTreasureboxStaticInfo
* AddVehicleModule
* AddWertheimerValue
* AntispamTest
* ATT_PrintCrameRotator
* ATT_PrintMousePosition
* ATT_PrintRotator
* ATT_ReplayRecoding
* ATT_SetCrameRotator
* ATT_SetRotator
* ATT_StartRecoding
* ATT_StartRunRandomTest
* ATT_StartRunTest
* ATT_StopRecoding
* CallMediaCanPlay
* CallOneSDKLogin
* CallOneSDKLogout
* ChangeCheckRoomMethod
* ChangeName
* ChangePlayerAttribute
* ChangeToSpectator
* CheatSpawnVehicle
* CheckLoadAllBlueprints
* CheckMails
* CheckStoreItemUnlock
* ClearAllAdventureQuests
* ClearAllGuideData
* ClearAllHTActors
* ClearAllHTVisualActors
* ClearAllMassEntity
* ClearAllNormalNpc
* ClearAllQuest
* ClearAllRealEstates
* ClearAllRedPointMessages
* ClearAllSimpleSceneActor
* ClearAllVehicles
* ClearAllVisions
* ClearAssetsLRUCache
* ClearGameData
* ClearGuideData
* ClearGuideID
* ClearMails
* ClearMapQuestIcon
* ClearMassCrowdCharacter
* ClearMassParkedVehicle
* ClearMassTrafficVehicle
* ClearMonsterDeadRecord
* ClearRecordByName
* ClearRedPoint
* ClearRentVehicle
* ClearStreetLamp
* ClearTreasureBoxRecord
* ClearVehicles
* ClearVehiclesByLaneTag
* CloneFailed
* CloseCommonProgress
* CloseTcp
* CloseUdp
* CloseUIByClass
* CollectPSO
* CompleteAchievementById
* CompleteAchievementsByTypeId
* CompleteAdventureManualFromId
* CompleteAllVisions
* CompleteAreaVisions
* CompleteCurQuestObject
* CompleteVision
* CompleteWizardAdventureManualByChapterIndex
* ConnectServer
* CopyPSO
* DebugCameraAnimSequence
* DecCommonProgress
* DelegateMissionComplete
* DeletePSO
* DeleteTreasureBoxData
* DesSpawnQusetVehicle
* EnterOrBreakState
* EnterPokemonGame
* EntireServerMailTag
* FinishCurGuide
* ForceFlushAsyncLoading
* ForceGarbageCollection
* ForceHideAllUI
* GameDataTest
* GetDBMailCount
* GetPersonTest
* GMModifyVehicleModule
* Goto
* GotoByStr
* GotoByStr2
* HideCharacters
* HideMainFormWidget
* HideMonsterHead
* HTCheat
* HTDrawDebugPoint
* HUDShowDebugInfo
* IgnoreVisionRadar
* InstanceStructSerializTest
* IsTeleportActived
* LoadAdventureManualQuests
* LoadCSVFileToDataTable
* LogAllOpActivity
* LogFunctionUnlock
* LotteryDailyRest
* ManualLockTarget
* MassAIPause
* MassAIResume
* NotifyTimerClockTimeOver
* OneKeyFinishGuide
* OpenAirFightOut
* OpenOrCloseFightUI
* OpenOrCloseWoodenUI
* OpenStoreBrand
* OpenTeachGuideTipsPanel
* OpenUI
* PassPermitActiveAdvance
* PassPermitAddExp
* PassPermitAddLevel
* PlayerStateStrength
* Position
* PrepareQuestVehicleLanes
* PrintAllHTActors
* PrintAllMovePoint
* PrintAllNpcNum
* PrintAllRedPointData
* PrintAllServerRPC
* PrintAllSpawnInfo
* PrintCurActivateVolumes
* PrintCurPlayerAbilities
* PrintDataLayersState
* PrintItemDataTableToCsv
* PrintNearByGraphLane
* PrintObjectProperty
* PrintRedPointMessages
* PrintSelfProperty
* ProintMassCrowdNum
* ProintMassVehiclesNum
* QueryProp
* QueryRecord
* QueryShaderBySHK
* RankTest
* ReadAirFightGETime
* RefreshAIThroughSpawn
* ReloadTime
* RemoveForceClosestLane
* RemovePriorityLanesByTag
* RemoveTeachGuideTips
* RemoveUI
* ResetAllAchievements
* ResetDelegateMissionCnt
* ResetInputEnvironment
* ResetInventory
* ResetLikeabilityChatSystem
* ResetToPlayerStart
* ResetToStart
* RevertVehicleData
* RoleExists
* RoleId
* SavePlayerData
* SDKFix
* SDKLogin
* SendRedPoint
* SetAchievementValueById
* SetActivationValue
* SetCharacterDead
* SetCharacterLevel
* SetCloneSaveData
* SetHTMassCrowdSpawnerDebugMode
* SetHTMassVehicleSpawnerDebugMode
* SetInputEnvironmentToGamepad"
* SetLanguage
* SetObjectPropertyValue
* SetPersonTest
* SetPlayerDisObstacleTag
* SetPlayerHP
* SetPlayerPhyAtk
* SetPreviewLanguage
* SetQuestFailed
* SetSilentEnable
* SetStaminaValue
* SetWorldLevel
* SetYahahaState
* ShowAllHTAkComponents
* ShowAllRecord
* ShowCameraState
* ShowCharacterShieldInfo
* ShowChatMain
* ShowCommonProgress
* ShowCurGuideState
* ShowDelegateMission
* ShowDescription
* ShowFindFloor
* ShowGMConsoleUI
* ShowLikeabilityMain
* ShowLocalNotice
* ShowMassCrowdAndVehicles
* ShowOtherCharacterInfo
* ShowPlayerState
* ShowPlayerState_ChangeTarget
* ShowSplineActorDebugLine
* ShowUIByClass
* ShowUIByClasses
* ShowUIByClassWithParaInt
* ShowUIByClassWithParaName
* ShowUIStreamByClass
* ShowVinesIK
* ShowZoneGraphByLaneIndex
* ShowZoneGraphByLaneTag
* SilentAll
* SilentAllAIs
* SilentPrintAll
* SilentShowDebugInfo
* SkillCharge
* SkillCoolDown
* SkillCost
* SkillHeterochrome
* SkillUnbalEfficiency
* SkipQuestWithBeginAndEnd
* SkipToQuest
* SpawnAIsFromName
* SpawnDropItems
* SpawnHTActorFromName
* SpawnMassCrowdCharacter
* SpawnMassParkedVehicle
* SpawnMassTrafficVehicle
* SpawnQusetVehicle
* StartGuide
* StoreBrandItemUnlock
* StoreBrandOnKeyItemUnlock
* StreamingCompleteTest
* SubmitDelegateMission
* SubmitDelegateMissionSingle
* SubmitQuest
* SwitchLockTargetLeft
* SwitchLockTargetRight
* SyncGameData
* TestCommonAwardsPopUpWindow
* TestCrash
* TestGameLog
* TestGetOpActivityAward
* TestHideMonsterHead
* TestLikeabilitBeginPlay
* TestLikeabilitChatRedPoint
* TestLikeabilityChatNotify
* TestLikeabilityQuestAccept
* TestLikeabilityQuestSubmit
* TestMail
* TestPublicMessage
* TestPublicMessageVarlist
* TestReadLikeabilitChatRedPoint
* TestRequestCloneScene
* TestSceneMessage
* TestSendAward
* TestSendChatSDKReq
* TestSendMailToRole
* TestServerDynamicLoad
* TestShowLineInfo
* TestShowPlayerTImes
* TestSpawn
* TestSwitchMember
* TestSwitchScene
* TestTips
* TestTransfreLoading
* TestTreasureBoxActor
* TestUnlockClone
* ToggleMassCrowdLaneShowState
* TraceRelivePlayerStartName
* TravelSingleLevel
* TravelToBigWorld
* TravelToScene
* TravelToTeleport
* UnEquipCharacter
* UnlockAllFogs
* UnlockAvarta
* UnlockAvartaFrame
* UnlockBusinessCard
* UnlockFog
* UnlockLikeabilityChat
* UpDateCharacterFormation
* UpdateQuestProgress
* VedioPathChanged
* VehicleSummon

> This handbook is taken from xoxo