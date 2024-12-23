# MOD Dependency and Subscription

[中文版本](#mod-依赖与订阅)

## This MOD depends on **TAB Mod Loader**.
Once you have deployed the TAB Mod Loader, simply subscribe to this MOD.

---

Due to the extensive feature descriptions, please refer to the changelog for details on new features.

### Current Features of This MOD:

- **MaxSaveBackup:** Set the maximum backup archive number. Setting it to 0 will disable the backup feature, and the default is 5.  
- **AutoDeleteBackups:** If enabled, the game will automatically delete save backup files when the game is won, lost, or a new named game is started. If the main save file is deleted from the save menu, this feature will also trigger. However, deleting backup save files will not delete the main save file or any other backup save files. **Enabled by default.**  
- **EnhancedSelection:** If enabled, you can select a unit or building by first selecting one, then holding Ctrl and dragging a selection area to select all units or buildings of the same type within the area. **Enabled by default.**  
- **DisableAutoSave:** If enabled, the game will not perform automatic saves; it is **turned off by default.**  
- **AutoSaveInterval:** Set the game's automatic save time, measured in seconds, with the default being the same as the original game at 1200 seconds.  
- **OptimizeAttackPriority:** Optimizes attack priority by raising the priority of venomous units by 1, without affecting their experience points. This feature changes game mechanics and may decrease performance, so it is **disabled by default.**  
- **GameMenuEnhancer:** Adds "EXIT" (exit without saving and return to the main menu) and "Save" (save game without returning to the main menu) options to the ESC menu. Menu saves reset the auto-save timer, which defaults to 20 minutes. **Enabled by default.**  
- **OptimizeTrainingSequence:** When enabled, assigns soldier training tasks to barracks with fewer training assignments. **Enabled by default.**  
- **DestroyAllSelectedUnits:** Allows bulk disbanding of troops with the Delete key, with a confirmation window. **Enabled by default.**  
- **FastAttack:** Speeds up attacks by automatically overriding units' attack commands, increasing attack rate but also noise. Not recommended for beginners. **Disabled by default.**  
- **KeepDisplayAllLifeMeters:** Continuously displays health bars for all units. Toggle with the Y key. **Enabled by default.**  
- **AutoGoWatchTower:** Selected units automatically seek the nearest WatchTower. Toggle with the F key. **Enabled by default.** You can increase the search radius with AutoGoWatchTowerRadius; the default range is 10.  
- **NumpadFilterVeteran:** Use Numpad1-9 to quickly select 1-9 veteran units from the current selection. Holding shift will select 1-9 new units instead. Toggle with Numpad1-9. **Enabled by default.**  
- **GameSpeedChange:** Press "+" or "-" to speed up or slow down the game. The maximum speed is 20, and the minimum is 1. Press Numpad 0 to reset to default speed. **Enabled by default.**  
- **FilterVeteranUnit:** Filters selected units to show only veterans. Holding shift will select only new units. Toggle with the V key. **Enabled by default.**  
- **AutoFindBonusItem:** In campaign mode, select the hero unit and press the shortcut key to make the hero automatically seek the nearest bonus item (excluding grenades and other materials). Toggle with the L key. **Enabled by default.**  
- **AutoDisperse:** Automatically disperses all selected units to form a more spread-out formation. Toggle with the E key. **Disabled by default.**  

The configuration files are now placed in the game’s root directory under `Mods/ModData/3357549187/`.  
The configuration file will be generated only after launching the game for the first time.

[Github Repository](https://github.com/JKstring/TABHelperMod)

---

# MOD 依赖与订阅

[English Version](#mod-dependency-and-subscription)

## 此 MOD 依赖于 **TAB Mod Loader**。
在部署 TAB Mod Loader 后，只需订阅此 MOD 即可。

---

由于功能描述较多，详情请查阅改动说明以了解新增功能。

### 此 MOD 的当前功能：

- **MaxSaveBackup:** 设置最大存档备份数量，设置为 0 则禁用备份功能，默认为 5。  
- **AutoDeleteBackups:** 若启用，游戏将在游戏胜利、失败或开始新的同名生存游戏时自动删除存档备份文件。如果在存档界面删除主存档同样会触发此功能。但删除备份存档不会删除主存档及其他备份存档。**默认开启。**  
- **EnhancedSelection:** 若启用，先选中一个单位或建筑，再按住 Ctrl 键并拖拽选区，即可选中区域内相同类型的单位或建筑。**默认开启。**  
- **DisableAutoSave:** 若启用，游戏将不会进行自动保存；**默认关闭。**  
- **AutoSaveInterval:** 设置游戏的自动保存时间，单位为秒，默认与原版游戏相同，为 1200 秒。  
- **OptimizeAttackPriority:** 通过将毒液的优先级提高 1 来优化攻击优先级，但不影响其经验值。此功能更改了游戏机制，可能会降低性能，因此**默认关闭。**  
- **GameMenuEnhancer:** 在 ESC 菜单中添加了“EXIT”（退出不保存并返回主菜单）和“Save”（保存游戏不返回主菜单）选项。菜单保存会重置自动保存计时器，默认为 20 分钟。**默认启用。**  
- **OptimizeTrainingSequence:** 启用后，将士兵训练任务分配给训练任务较少的兵营。**默认启用。**  
- **DestroyAllSelectedUnits:** 允许使用 Delete 键批量解散部队，并提供确认窗口。**默认启用。**  
- **FastAttack:** 通过自动覆盖单位的攻击命令来加速攻击，增加攻击频率但也会产生噪音。不建议初学者使用。**默认关闭。**  
- **KeepDisplayAllLifeMeters:** 持续显示所有单位的生命条。按 Y 键切换。**默认启用。**  
- **AutoGoWatchTower:** 选中的单位会自动寻找最近的哨塔。按 F 键切换。**默认启用。** 您可以通过 AutoGoWatchTowerRadius 增加搜索半径，默认范围为 10。  
- **NumpadFilterVeteran:** 使用 Numpad1-9 快速从当前选择中选择 1-9 个老兵单位。按住 shift 将选择 1-9 个新单位。按 Numpad1-9 切换。**默认启用。**  
- **GameSpeedChange:** 按 “+” 或 “-” 键加快或减慢游戏速度。最大速度为 20，最小速度为 1。按 Numpad 0 恢复默认速度。**默认启用。**  
- **FilterVeteranUnit:** 过滤所选单位以仅显示老兵单位。按住 shift 将仅选择新单位。按 V 键切换。**默认启用。**  
- **AutoFindBonusItem:** 在战役模式下，选择英雄单位并按快捷键，使英雄自动寻找最近的奖励物品（不包括手榴弹和其他材料）。按 L 键切换。**默认启用。**  
- **AutoDisperse:** 自动分散所有选中的单位，以形成更分散的阵型。按 E 键切换。**默认关闭。**  

现在配置文件被放置在游戏的根目录下 `Mods/ModData/3357549187/` 目录中。  
配置文件需要运行一次游戏后，才会自动生成。

[Github 仓库](https://github.com/JKstring/TABHelperMod)




### 修复与新增功能 / Fixes and New Features

#### 修复内容 / Fixes
1. 修复了存档备份中因特殊字符导致备份失效的问题。  
   Fixed an issue where special characters caused save backups to fail.

2. 修复了在卖出所有资源数量过多时可能引发的崩溃问题。  
   Fixed a crash that occurred when selling all resources in excessive amounts.

#### 新增功能 / New Features
1. 新增功能：通过按 +/- 调整游戏速度时，同时按住 Ctrl 键可直接将速度调整至最大或最小值。  
   New Feature: When adjusting game speed using +/-, holding Ctrl will instantly set the speed to maximum or minimum.

2. 新增 **QuickBuyResourceDelay** 配置项，可自定义 QuickBuyResource 功能的触发速度。  
   Added the **QuickBuyResourceDelay** setting to customize the trigger speed for the QuickBuyResource feature.

---

### 功能优化与扩展 / Feature Enhancements and Extensions

#### 新增功能 / New Features
1. **DeselectUnitsAfterTowerSearch**  
   - 增加了该配置项，用于设置自动分配单位进入哨塔时是否取消选中状态。  
   - Added the **DeselectUnitsAfterTowerSearch** option, allowing users to configure whether units are deselected after being automatically assigned to a watchtower.

2. **AutoGoWatchTower 功能优化 / AutoGoWatchTower Improvement**  
   - 现在可以选中哨塔后按 F 键，自动分配附近单位进入哨塔，同时会判断单位是否具备进入哨塔的条件。  
   - Improved the **AutoGoWatchTower** feature: you can now select a watchtower and press F to automatically assign nearby units to enter it. The assignment process will also check if the units can enter the watchtower.

3. **BatchCancelCommand 功能 / BatchCancelCommand Feature**  
   - 当启用时：  
     - 可选中多个需要取消命令的建筑（如兵营或正在升级的建筑），按 N 键取消命令队列中的最后一个命令；  
     - 按住 Shift 键可取消当前所有命令队列；  
     - 按住 Ctrl 键则取消当前正在执行的命令。**默认启用**。  
   - When enabled:  
     - Select multiple buildings (e.g., barracks or upgrading structures) and press N to cancel the last command in their queue.  
     - Hold Shift to cancel all commands in the queue.  
     - Hold Ctrl to cancel the currently executing command. **Enabled by default**.

4. **QuickBuyResource 功能 / QuickBuyResource Feature**  
   - 当启用时：  
     - 在市场买卖资源时按住 Ctrl 键，可以快速买入/卖出最大数量的资源；  
     - 按住 Shift 键可以持续买入/卖出资源，速度会随着鼠标左键点击次数的增加而加快。  
   - When enabled:  
     - Holding Ctrl while trading resources at the market will buy/sell the maximum amount of resources.  
     - Holding Shift will enable continuous buying/selling, with speed increasing based on the number of left mouse clicks.
