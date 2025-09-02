# MinerFergus_SourceCode

## MinerFergus GitHub: [이동](https://github.com/ACEDIA2567/MinerFergus) </br>
## 소스코드: [다운로드](https://github.com/user-attachments/files/21837635/Script.zip)    
## 소스코드(제가 작성한 코드만 모아둔 파일입니다.): [다운로드](https://github.com/user-attachments/files/22098118/MinerFergus.zip)    

<hr>

📦Script     
 ┣ 📂Data  ▶ 데이터 구조   
 ┃ ┗ 📜EquipmentData.cs     
 ┣ 📂Entity  ▶ 게임 내 오브젝트 관련    
 ┃ ┣ 📂Collider  ▶ 충돌관련 로직    
 ┃ ┃ ┣ 📜MapMoveCollider.cs     
 ┃ ┃ ┗ 📜TutorialCollider.cs     
 ┃ ┣ 📂Fade  ▶ 인&아웃   
 ┃ ┃ ┗ 📜Fade.cs     
 ┃ ┣ 📂Light  ▶ 빛 관련    
 ┃ ┃ ┗ 📜MineLight.cs     
 ┃ ┣ 📂Ore  ▶ 광물    
 ┃ ┃ ┣ 📜Ore.cs     
 ┃ ┃ ┣ 📜OreDropObject.cs     
 ┃ ┃ ┗ 📜RandomOre.cs     
 ┃ ┣ 📂Quest  ▶ 퀘스트  
 ┃ ┃ ┣ 📜MainQuestOrder.cs     
 ┃ ┃ ┣ 📜QuestOrder.cs     
 ┃ ┃ ┗ 📜QuestUI.cs     
 ┃ ┣ 📂Smith  ▶ 제작    
 ┃ ┃ ┗ 📜Blacksmith.cs     
 ┃ ┣ 📂Teleport  ▶ 맵 이동   
 ┃ ┃ ┣ 📜GameOver.cs     
 ┃ ┃ ┗ 📜MapMove.cs     
 ┣ 📂Interface  ▶ 인터페이스   
 ┃ ┣ 📜IDamageable.cs     
 ┃ ┣ 📜IItemEffect.cs     
 ┣ 📂Inventory  ▶ 플레이어의 인벤토리    
 ┃ ┣ 📜Inventory.cs     
 ┃ ┣ 📜InventoryManager.cs     
 ┃ ┣ 📜InventoryUI.cs     
 ┃ ┣ 📜ItemTradeButton.cs     
 ┃ ┗ 📜Slot.cs     
 ┣ 📂Manager  ▶ 게임을 제어하는 싱글톤 매니저    
 ┃ ┣ 📜AddressableManager.cs     
 ┃ ┣ 📜DataManager.cs     
 ┃ ┣ 📜EndingManager.cs     
 ┃ ┣ 📜EventManager.cs     
 ┃ ┣ 📜GameManager.cs     
 ┃ ┣ 📜LoadManager.cs     
 ┃ ┣ 📜MapManager.cs     
 ┃ ┣ 📜PoolManager.cs     
 ┃ ┣ 📜QuestManager.cs     
 ┃ ┣ 📜ResourcesManager.cs     
 ┃ ┣ 📜SaveLoadManager.cs     
 ┃ ┣ 📜Singleton.cs     
 ┃ ┣ 📜SoundClip.cs     
 ┃ ┣ 📜SoundManager.cs     
 ┃ ┗ 📜UIManager.cs     
 ┣ 📂Map  ▶ 맵 생성  
 ┃ ┣ 📜MapGenerator.cs     
 ┃ ┗ 📜Node.cs     
 ┣ 📂MiniGame ▶ 미니 게임  
 ┃ ┣ 📜BlacksmithMiniGame.cs     
 ┃ ┣ 📜ForgeMiniGame.cs     
 ┃ ┗ 📜MiniGameNode.cs     
 ┣ 📂Player ▶ 플레이어의 기능     
 ┃ ┣ 📜Player.cs     
 ┃ ┣ 📜PlayerAnimation.cs     
 ┃ ┣ 📜PlayerComponent.cs     
 ┃ ┣ 📜PlayerController.cs     
 ┃ ┣ 📜PlayerEquip.cs     
 ┃ ┣ 📜PlayerExp.cs     
 ┃ ┣ 📜PlayerInputController.cs     
 ┃ ┣ 📜PlayerInteraction.cs     
 ┃ ┣ 📜PlayerMining.cs     
 ┃ ┣ 📜PlayerMovement.cs     
 ┃ ┗ 📜PlayerStatus.cs     
 ┣ 📂SaveLoad ▶ 저장&불러오기    
 ┃ ┗ 📜PlayerSaveLoad.cs     
 ┣ 📂Scene ▶ 씬 제어     
 ┃ ┣ 📜Intro.cs     
 ┃ ┣ 📜Main.cs     
 ┃ ┣ 📜Mine.cs     
 ┣ ┗ 📜Tutorial.cs     
 ┣ 📂Sound ▶ 사운드 제어     
 ┃ ┣ 📜BGMSource.cs     
 ┃ ┗ 📜ButtonSound.cs     
 ┣ 📂UI ▶ UI 관련 컴포넌트  
 ┃ ┣ 📂Button ▶ 버튼    
 ┃ ┃ ┣ 📜UI_ButtonFunction.cs     
 ┃ ┃ ┣ 📜UI_Escape.cs     
 ┃ ┃ ┣ 📜UI_Intro.cs     
 ┃ ┃ ┣ 📜UI_Option.cs     
 ┃ ┃ ┣ 📜UI_ReTutorialSkip.cs     
 ┃ ┃ ┗ 📜UI_TutorialSkip.cs     
 ┃ ┣ 📂Interact ▶ 상호작용   
 ┃ ┃ ┣ 📜UI_Interact.cs     
 ┃ ┃ ┣ 📜UI_Interact_Base.cs     
 ┃ ┃ ┣ 📜UI_Interact_Escape.cs     
 ┃ ┃ ┣ 📜UI_Interact_Forge.cs     
 ┃ ┃ ┣ 📜UI_Interact_GuildGuide.cs     
 ┃ ┃ ┣ 📜UI_Interact_Merchant.cs     
 ┃ ┃ ┣ 📜UI_Interact_Next.cs     
 ┃ ┃ ┣ 📜UI_Interact_Quest.cs     
 ┃ ┃ ┗ 📜UI_Interact_Smithy.cs     
 ┃ ┣ 📂Player ▶ 장비창        
 ┃ ┃ ┣ 📜PlayerEquipMentWindow.cs     
 ┃ ┃ ┗ 📜PlayerEquipMentWindowSlot.cs     
 ┃ ┣ 📂Press ▶ 누르기   
 ┃ ┃ ┗ 📜UI_PressButton.cs     
 ┃ ┣ 📂Slider ▶ 슬라이드    
 ┃ ┃ ┣ 📜UI_SliderFunction.cs     
 ┃ ┃ ┗ 📜UI_SoundOption.cs     
 ┃ ┣ 📜CanvasController.cs     
 ┃ ┣ 📜DebugButton.cs     
 ┃ ┣ 📜DebugConsole.cs     
 ┃ ┣ 📜InitCraftButton.cs     
 ┃ ┣ 📜InteractUI.cs     
 ┃ ┣ 📜UIMover.cs     
 ┃ ┣ 📜UI_Acquire.cs     
 ┃ ┣ 📜UI_AcquireItem.cs     
 ┃ ┣ 📜UI_Cave.cs     
 ┃ ┣ 📜UI_Check.cs     
 ┃ ┣ 📜UI_ClearEquipmentSlot.cs     
 ┃ ┣ 📜UI_DestructionPreventionSelectSlot.cs     
 ┃ ┣ 📜UI_DestructionPreventionSlot.cs     
 ┃ ┣ 📜UI_Ending.cs     
 ┃ ┣ 📜UI_EndingCheck.cs     
 ┃ ┣ 📜UI_EquipmentUpgrade.cs     
 ┃ ┣ 📜UI_EquipmentUpgradeSlot.cs     
 ┃ ┣ 📜UI_Exp.cs     
 ┃ ┣ 📜UI_Function.cs     
 ┃ ┣ 📜UI_GameOver.cs     
 ┃ ┣ 📜UI_GuildGuide.cs     
 ┃ ┣ 📜UI_InputFunction.cs     
 ┃ ┣ 📜UI_Loading.cs     
 ┃ ┣ 📜UI_Merchant.cs     
 ┃ ┣ 📜UI_MineInfo.cs     
 ┃ ┣ 📜UI_MineLevel.cs     
 ┃ ┣ 📜UI_MineStair.cs     
 ┃ ┣ 📜UI_MoveItem.cs     
 ┃ ┣ 📜UI_Next.cs     
 ┃ ┣ 📜UI_QuestClear.cs     
 ┃ ┣ 📜UI_QuestSlot.cs     
 ┃ ┣ 📜UI_QuestView.cs     
 ┃ ┣ 📜UI_Shop.cs     
 ┃ ┣ 📜UI_SuccessRateUpSelectSlot.cs     
 ┗ ┗ 📜UI_SuccessRateUpSlot.cs     

📦Script     
 ┣ 📂ScriptableObject     
 ┃ ┣ 📂Catalyst  ▶ 강화 재료 데이터   
 ┃ ┃ ┗ 📜CatalystSO.cs     
 ┃ ┣ 📂Equipment  ▶ 장비 데이터  
 ┃ ┃ ┣ 📜EquipmentSO.cs     
 ┃ ┃ ┣ 📜EquipmentStat.cs     
 ┃ ┃ ┗ 📜EquipmentUpgrade.cs     
 ┃ ┣ 📂GameEventSO  ▶ 게임 이벤트 트리거    
 ┃ ┃ ┣ 📜Close Canvas Event.asset     
 ┃ ┃ ┣ 📜Failure Mini Game Evnet.asset     
 ┃ ┃ ┣ 📜OnBoxChanged.asset     
 ┃ ┃ ┣ 📜OnCloseInventory.asset     
 ┃ ┃ ┣ 📜Open Blacksmith Evnet.asset     
 ┃ ┃ ┣ 📜Open Forge Mini Game Event.asset     
 ┃ ┃ ┣ 📜Quest UI Update Event.asset     
 ┃ ┃ ┗ 📜Success Mini Game Event.asset     
 ┃ ┣ 📂ItemEffect  ▶ 사용 가능 아이템 데이터   
 ┃ ┃ ┣ 📂InventoryUp  ▶ 인벤토리 확장  
 ┃ ┃ ┃ ┣ 📜InventoryUpgrade1.asset     
 ┃ ┃ ┃ ┗ 📜InventoryUpgradeEffect.cs     
 ┃ ┃ ┣ 📂LightUp  ▶ 빛 게이지 상승   
 ┃ ┃ ┃ ┣ 📜LightUp.asset     
 ┃ ┃ ┃ ┗ 📜LightUpEffect.cs     
 ┃ ┃ ┗ 📜ItemEffectSO.cs     
 ┃ ┣ 📂LoadingTip  ▶ 로딩 시 팁 데이터    
 ┃ ┃ ┣ 📜LoadingTip.cs     
 ┃ ┃ ┗ 📜TipData.asset     
 ┃ ┣ 📂Ore  ▶ 광물 데이터    
 ┃ ┃ ┣ 📜AdamantiteData.asset     
 ┃ ┃ ┣ 📜CoalData.asset     
 ┃ ┃ ┣ 📜CopperData.asset     
 ┃ ┃ ┣ 📜DiamondData.asset     
 ┃ ┃ ┣ 📜GoldData.asset     
 ┃ ┃ ┣ 📜IronData.asset     
 ┃ ┃ ┣ 📜MithrilData.asset     
 ┃ ┃ ┣ 📜SilverData.asset     
 ┃ ┃ ┣ 📜StoneData.asset     
 ┃ ┃ ┗ 📜TutorialStoneData.asset     
 ┃ ┣ 📂OreDropTable  ▶ 드랍 광석 데이터    
 ┃ ┃ ┣ 📜Adamantite.asset     
 ┃ ┃ ┣ 📜Coal.asset     
 ┃ ┃ ┣ 📜Copper.asset     
 ┃ ┃ ┣ 📜Diamond.asset     
 ┃ ┃ ┣ 📜Gold.asset     
 ┃ ┃ ┣ 📜Iron.asset     
 ┃ ┃ ┣ 📜Mithril.asset     
 ┃ ┃ ┣ 📜Silver.asset     
 ┃ ┃ ┗ 📜Stone.asset     
 ┃ ┣ 📂RandomMine  ▶ 광산 데이터   
 ┃ ┃ ┣ 📜Mine Data 1.asset     
 ┃ ┃ ┣ 📜Mine Data 2.asset     
 ┃ ┃ ┣ 📜Mine Data.asset     
 ┃ ┃ ┗ 📜Tutorial Mine Data.asset     
 ┃ ┣ 📜GameEvent.cs     
 ┃ ┣ 📜GameEventLisntner.cs     
 ┃ ┣ 📜ItemSO.cs     
 ┃ ┣ 📜MineRandomOre.cs     
 ┃ ┣ 📜OreDropSO.cs     
 ┃ ┣ 📜OreScriptableObject.cs     
 ┃ ┗ 📜QuestSO.cs     



