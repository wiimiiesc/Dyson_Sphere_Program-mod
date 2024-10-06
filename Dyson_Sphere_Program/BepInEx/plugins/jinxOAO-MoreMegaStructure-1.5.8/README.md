# More Mega Structures  更多巨构建筑

- Open Dyson sphere editor (press "Y") and you can find buttons in the bottom-left corner, to select which megastructure you plan to construct. Then you can design your megastructure, just like designing a Dyson sphere.   
- You need to launch the corresponding rockets (see new items in the images below) in the silo to build the megastructure. Besides, you still need to eject [solar sail] to fill the shell of the megastructure, aiming to provide energy for the mega structure.   

- 打开戴森球编辑器面板（按下Y），就可以在左下角选择要在当前恒星上修建哪一种巨构建筑。之后你就可以像设计戴森球一样设计新的巨构建筑。  
- 你需要在发射井发射对应的火箭，此外你仍然需要弹射太阳帆来填充壳面，以此来为巨构建筑供能。像戴森球一样，更多的结构和壳面能够提升巨构建筑的最大效能。但与戴森球不同的是，太阳帆在被壳面吸收前不提供任何效能或产出。   

![pressY](https://s2.loli.net/2022/02/26/4ToCAsJBg7vP8jq.png)
![editor3.png](https://s2.loli.net/2022/02/26/pLtRzAfbyP9dgsc.png)
![replicator.png](https://s2.loli.net/2022/02/26/5sP8KY9O2tETIvM.png)   

## Matter Decompressor  

- Extract matter from black hole and accretion disks, which can be received on the ground as iron, copper, silicon, titanium, unipolar magnet or graphite by ray reconstructors (ray receivers).   
- Can only be built on black holes.   

## Science Nexus  

- When researching, the Science Nexus will automatically upload additional hash blocks to greatly increase research speed, without building any receivers or consuming any matrices. You can view the additional research speed provided by the Science Nexus in the Megastructure Editor (Y). In addition, the [Research speed] technology will also enhance the Research Speed of the Science Nexus.  
- Science Nexus will provide metadata. It cannot be superimposed with the metadata provided by matrix production. The higher of the two values will be used as the metadata provided by this archive.   

## Warp Field Broadcast Array

- Use the energy of the star to broadcast the warp energy field to the entire galaxy, which will directly increase the warp speed of the logistics vessels, without requiring any receivers. You can view the warp speed bonus provided by the Warp Field Broadcast Array in the Megastructure Editor (Y). And this bonus can be stacked with the [Logistics carrier engine] technology.  
- You can only build one Warp Field Broadcast Array. Max bonus = 250 light-years per second (without counting technology bonuses).   

## Interstellar Assembly  
- Building an interstellar assembly allows you to assemble items on a MegaStructure. You can set up up to 15 recipes, and you need to build the [Exchange Logistic Station] ![exchangeLS.png](https://s2.loli.net/2022/11/05/v8PClEyqBNZUcIT.png)  on the ground of the same star system, in order to provide resources, materials or to receive products. The production speed is influenced by the energy assignment and the production speed of the recipe itself. The overage energy will be automatically used for produce [multi-functional components] ![integratedcomponents.png](https://s2.loli.net/2022/02/25/cfWPK6xV9h2pGoH.png), which can be directly assembled into a variety of production buildings and logistics items at great speed, even satellite substations and artificial stars, and do not require any additional materials. This means you can go out with just a bunch of [integrated components].   
![QQ20221105212003.png](https://s2.loli.net/2022/11/05/6kt5HpVFIoyJh49.png)
![quickRecipes.png](https://s2.loli.net/2022/02/26/XLTB8NwbltguEZi.png)   

- Warning: The [Component integration station] in the old version is not deleted, but they will not work any more, and you can no longer make them. Besides, those buildings will harm the efficiency of the Interstellar Assembly now. So you'd better remove them. If you want to receive [multi-functional components], use [Exchange Logistic Station] ![exchangeLS.png](https://s2.loli.net/2022/11/05/v8PClEyqBNZUcIT.png).  
- Warning: It is not recommended to choose a fractional formula, which will consume raw materials with exaggerated proportions and produce very little products.
- Tip: If you use an interstellar assembly to produce the interstellar assembly carrier rocket and you do not set up the slot of this kind of rocket, then the rocket will be automatically used to build the frame of this interstellar assembly itself.
- Tip: If a product of one recipe is the material of another recipe (in the same interstellar assembly), it can be automatically transported inside the megastructure without the necessity to set that item's slot in the [Material Exchange Logistics Station] on the ground.

## Crystal Reconstructor 

- Guide photons to strip crystallites from neutron stars or white dwarfs and send them to the surface. You need to build a ray reconstructor (ray receiver) on the surface to produce Casimir crystal or optical grating crystal.   
- Can only be built on neutron stars or white dwarfs.   

## Nicoll-Dyson Beam (Star Cannon) 

- The star cannon can store the energy of the star to stimulate another star's energy surge, guiding its own energy to attack the dark fog hive.   
- Building a star cannon goes through multiple stages. You can only build one star cannon.   

### Other Tips  

- You cannot change the type of a megastructure unless all shells, frames and nodes have been removed.   
- [Graviton lens] work with all kinds of receivers.   
- When you build receivers on planets that don't match megastructures, they won't work.  
- Science Nexus and Warp Field Broadcast Array do not require any receivers to work.
- Most of the content of this mod is unlocked in late game technology. The yield factor for megastructures may be unreasonable and will be adjusted in future versions. Any suggestions or feedback questions are welcome.

### Installation (If Manually)  

1. Install BepInEx.    
2. Intsall LDBTool, DSPModSave and CommonAPI.    
3. Drag MoreMegaStructure.dll into "Dyson Sphere Program/BepInEx/plugins/".  
4. Drag "mmstabicon" into the same folder of MoreMegaStructure.dll 

### Change log
V1.5.8: Added anomaly detection and correction for Star Cannon countdown.  

V1.5.7: Fixed an error when updating the star cannon's properties.  

V1.5.6: Fixed an error of Star Assembly. (When player had Blue Buff activated from TCFV and the Star Assembly's statistic product/consume register is null, it would cause the error.)

V1.5.5: Updated to work with game version 0.10.30.23272.  

V1.5.4: Added Star cannon lasers in starmap UI. 
&emsp;&emsp;&emsp;Compatibility changes for TheyComeFromVoid V3.2.0.

V1.5.3：Removed a Postpatch on PlanetById(), which should fix a Compatible issue with GS.   

V1.5.2: Added a button in Receiver's UI which will let you apply the setting to all the receivers on this planet. 
&emsp;&emsp;&emsp;Added a config setting which can prevent the Interstellar Assembly UI always showing up when open Megastructure Editor Panel.

V1.5.1: Fixed a bug where the log file' size would rapidly increase.   

V1.5.0: Remove all additional ray receivers . Now the Matter Decompressor and Crystal Reconstructor will use the vanilla ray receivers (renamed to ray reconstructors) to receive items. You will need to set the receive item on the receiver's UI panel.  
&emsp;&emsp;&emsp;The special receivers/reconstructors in old versions can still work in this version, but they can not be made any more.  
&emsp;&emsp;&emsp;The Matter Decompressor can produce magnet now.  

<details>
  <summary> Click to view all </summary>  
  
V1.4.1: Fixed a bug where the effects direction was incorrect when firing a star cannon.  
&emsp;&emsp;&emsp;Fixed a bug where the successful paste prompt did not pop up when successfully pasting a receiver's config.  
&emsp;&emsp;&emsp;Known issue: Reading the archive while the star cannon is firing may result in the convergence laser display pointing to the wrong direction.  
&emsp;&emsp;&emsp;Added performance statistics (under testing).

v1.4.0: Added raw ore mode to the relevant receiver of the mater decompressor. Now, you can choose to produce raw ore instead of smelted ingots.   
&emsp;&emsp;&emsp;Megastructure related receivers will be set to substance generation mode when built, except for the vanilla ray receivers.  

v1.3.11: Added a compatible feature with Genesis Book, which allows the new chemical recipe type meet the Stellar reactor's specialization request.

v1.3.10: Added the feature to adapt the new TCFV version.  

v1.3.9: Fixed an error with GS2.  

v1.3.8: Change the droplet's stack size to 10 to match the new TCFV gameplay. 
&emsp;&emsp;&emsp;Changed the droplet's description to tell players that they need to change the space fleet type to use droplets.  

v1.3.7: Corrected the droplet's description error.  

v1.3.6: Reduced charging time for the first few stages of the star cannon. Increased the fire duration of the first stage to 2 minutes.
&emsp;&emsp;&emsp;Update to prepare for the mod They Come From Void 3.0.0.  

v1.3.5: Fix an abnormal increase in memory usage when saving the game. But from this version on, the production statistics data of Interstellar Assembly will not be saved any more. Meaning that each time you load the game, you will lose all the Interstellar Aseembly production statistics data before.  
&emsp;&emsp;&emsp;Removed unnecessary calculations from production statistics and reduced the consumption of game performance by the mega structure statistics.

v1.3.4: Fix a bug that some recipes disappeared when installed with GenesisBook.   

v1.3.3: Fix an error of ProductionStatistics with GS2.

v1.3.2: Fix an recipe conflict with GenesisBook.  
&emsp;&emsp;&emsp;Hide the Nicoll-Dyson Beam tech by default.  

v1.3.1: Fix an incompatible bug with BlueprintTweaks.  

V1.3.0: New: Nicoll-Dyson Beam Technology and Star Cannon, capable of long-range shooting and destroying space dark fog hive. The values of the star cannon are currently being tested.  
&emsp;&emsp;&emsp;Production speed of each recipe of the interstellar assembly can add an extra specific speed limit. (default unlimited, only limited by energy alloction).
&emsp;&emsp;&emsp;Add upgrade options to the vanilla ray receiver, which can be upgraded to different types of receivers.
&emsp;&emsp;&emsp;Fixed some index out of range errors.

v1.2.1: Fixed an error when working with GigaStationsUpdated. Now this mod should be compatible with GigaStationsUpdated, or at least the game can be loaded.  

v1.2.0: Updated to work with game version 0.10.28.21247.  
&emsp;&emsp;&emsp;The number of recipes for all Interstellar Assembly has increased from 4 to 15, but the recipe slots will gradually be unlocked as the total speed of the Interstellar Assembly increases.   
&emsp;&emsp;&emsp;The Interstellar Assembly now can be specialized to different types, to gain additional buffs (speed buff or productive buff). Specialization progress requires certain conditions to be met before it begins, and you have to maintain a period of time to complete the specialization conversion process in order to obtain the buffs. Different specializations can switch between each other, but it also takes time.  
&emsp;&emsp;&emsp;Add an increase in production indicator to the recipes of the Interstellar Assembly. If the input raw materials have been sprayed by proliferator, you can see the increase in production symbol and statistical information in the UI.  
&emsp;&emsp;&emsp;Now the Interstellar Assembly has it's own statistics panel page. Press P and select your Interstellar Assembly at the top right corner to see its statistics. Compatible with bottleneck.  
&emsp;&emsp;&emsp;Put all the megastructure's receivers in the quick build bars.  
&emsp;&emsp;&emsp;Fixed a text error in the megastructure editor.  
&emsp;&emsp;&emsp;Fixed a bug where the output quantity of a formula for extra production is incorrect.  
&emsp;&emsp;&emsp;Updated some rocket icons, which are provided by L.

v1.1.10 & v1.1.11: Now building receivers that don't match the mega structure type won't harm the megastructure's energy or function any more. The wrong receivers will not work, regardless of its mode. When the receiver doesn't match the mega structure's type, you can see the note "type not match" on it's receiver UI panel. 

v1.1.9: Now the Science Nexus rocket's recipe need tech "Mission completed!".  
&emsp;&emsp;&emsp;Change some balance settings of the Science Nexus ONLY FOR the mod GenesisBook: Now you need to eject universe matrix rather than solar sail to build the shell. And, if you change the megastructure type to the science nexus, it will automatically remove all the solar sails you've already ejected. In GenesisBook, the Science Nexus rocket's recipe need tech "Certificate of Not Being a Noob Anymore".  

v1.1.8: Fixed a bug that the exchange logistic station will not be unlocked correctly when you've install the mod They Come From Void.  

v1.1.7: Tiny fix for the logic of launching silo.  

v1.1.6: This mod now aupports 1000 star systems, only if you set the Support1000Stars to true in the config file. (You need to launch the game first, then you can see the new config options.)  
&emsp;&emsp;&emsp;Now the Interstellar Assembly will not waste sufficient resources by default when some of them are insufficient. You can change this back to the previous version by editing the config file.  

v1.1.5: This mod is now compatible with GenesisBook mod, now if you install both mods, some recipes and pre-techs will be modified appropriately to avoid incompatibility problems.  
&emsp;&emsp;&emsp;Fixed a bug that the interstellar assembly might occur "divided by 0" error.  
&emsp;&emsp;&emsp;Added internal storage displayment, which shows the specific number of products that cannot be received by the ground station and are temporarily stored in the interstellar assembly itself.  
&emsp;&emsp;&emsp;Added a new setting that allows you to adjust the power distribution of the Interstellar Assembly non-linearly. Specifically, the energy distribution ratio can be adjusted more finely (minimum 0.01%) at low distribution amounts.  
&emsp;&emsp;&emsp;The Interstellar Assembly's megastructure edit page now displays the Interstellar Assembly's total work speed instead of energy wattage.   

v1.1.4: Now the Interstellar Assembly will stop consuming materials, only if ALL kinds of the recipe's products are full (10000) in the Interstellar Assembly's storages. (Note that the items in the Interstellar Assembly storage will not be saved in the game archive).  
&emsp;&emsp;&emsp;Fixed a bug that the exchange station might consume the items added by hand, when the storage limit is less than 10000.  
&emsp;&emsp;&emsp;Fixed a bug if you set negative speed ratio.  

v1.1.3: Fixed a bug which has caused the energy distribution between multiple interstellar assembly to affect each other.  
&emsp;&emsp;&emsp;Fixed an error that occurs when the interstellar assembly is working in a star system, which does not have any surface output/consumption (this will not occur in normal games).  
&emsp;&emsp;&emsp;Fixed a bug that the interstellar assembly will not produce items for a long time if it had negative energy for a period of time.  
&emsp;&emsp;&emsp;Change default value of speed ratio, if you've installed version1.1.2 before, this will not affect your game.  

v1.1.2: Fixed an error caused by the null [Exchange Logistic Station].   

v1.1.1: Since the speed of Interstellar Assembly might not be balance, players can now adjust the speed factor in config file.  
&emsp;&emsp;&emsp;Fixed a bug that the real speed is much slower than it should be.  

v1.1.0: REMAKE THE Interstellar Assembly! Now you can make anything in the interstellar assembly. Please read the chapter of Interstellar Assembly.  

v1.0.3: [multifunctional components] can now synthesize [quantum chemical plant].  
&emsp;&emsp;&emsp;Receivers can be switched to each other by upgrading (but are limited by the upgrade logic, the intermediate building is necessary when switch buildings with 3 and more levels distance), which MIGHT make this MOD adapt to BlueprintTweaks.  
&emsp;&emsp;&emsp;Fixed a text error when entering the Dyson Sphere Editor interface.  

v1.0.2: Fixed an issue where some buttons could not be clicked at 2k or higher resolutions.  
&emsp;&emsp;&emsp;Provides a config setting that players can turn off the button show and hide animation (so that it will show or hide immediately).  

v1.0.1: The button for planning megastructures has been put back in the lower left corner of the megastructure panel. In order to avoid obscuring the original buttons in the game, the new buttons will be automatically hidden when not in use.  
&emsp;&emsp;&emsp;Fixed some text errors.  
&emsp;&emsp;&emsp;Fixed an error that the star cannon's construction progress is negative.   
&emsp;&emsp;&emsp;Increased the amount of metadata production through the Science Nexus in later game.   
&emsp;&emsp;&emsp;Tooltips for multi-components that are automatically transported into the inventory no longer pop up repeatedly when editing a megastructure.  

v1.0.0: Now, the multi-functional components produced by the Interstellar Assembly can be directly teleported to the mech inventory. See the Interstellar Assembly above for a details.   
&emsp;&emsp;&emsp;Now Science Nexus will provide a small amount of metadata according to the speed of producing hash points.    
&emsp;&emsp;&emsp;Fix some text error. Move the megastructure buttons to the top to avoid blocking other buttons.   
&emsp;&emsp;&emsp;Add Nicoll Dyson beam for mod *TheyComeFromVoid*. Note that this new megastructure is only available if you have *TheyComeFromVoid* with version higher than 2.0.0 installed. Science Nexus research speed has been nerfed to 1/3 *only in the mod TheyComeFromVoid* for balance.     

v0.4.1 & v0.4.2: Updated to work with game version 0.9.25.11985.

v0.4.0: Change some icons, add some instructions. Fix a bug, which may cause error when you try to open DysonEditorPanel in space.  

v0.3.3: Optimize the calculation logic of the output research speed of the science nexus.  
&emsp;&emsp;&emsp; Science Nexus can now independently complete the entire process of unlocking any technology.

v0.3.2: The basic research speed of the Science Nexus has been restored to the original version, but the bonus provided by each level of technology has been reduced from 100% to 1%.

v0.3.1: Fix an issue with missing icon.

v0.3.0: Now the new items (except the receiver buildings) can be seen in the production statistics panel;   
&emsp;&emsp;&emsp;  Add 2 new receivers to product graphite and optical grating crystal.

v0.2.0: The basic research speed of the Science Nexus has been reduced to 1/10;
&emsp;&emsp;&emsp;   Changed some Dyson Sphere text descriptions.  
</details>

## 物质解压器  

- 从黑洞和吸积盘中提取物质，可在地面上由射线重构站（射线接收器） 接收为铁、铜、硅、钛、单极磁石或高能石墨（就像射线接受器生成光子一样）。  
- 只能在黑洞上建造。  

## 科学枢纽  

- 在研究科技时，科学枢纽将自动上传额外的哈希块来大幅提升研究速度，无需建造任何接收器，也不消耗任何矩阵。你可以在巨构编辑器（Y）查看科学枢纽提供的额外研究速度。此外，研究速度加成科技将同样能强化科学枢纽的研究速度。     
- 科学枢纽将提供元数据（不与矩阵生产提供的元数据叠加，二者取较大值）。随着科学枢纽Hash产量的提高，提供的元数据也将增加，但增长量会越来越不明显。    

## 折跃场广播阵列  

- 利用恒星的能量将折跃能量场广播到全星区，这将直接提升全星区的物流运输船的曲速速度，无需建造任何接收器。你可以在巨构编辑器（Y）查看折跃场广播阵列提供的曲速速度加成。且该加成可以和运输船引擎科技叠加。   
- 全星区最多只能建造一个。折跃场广播阵列提供的曲速加成最多为250光年/秒。   

## 星际组装厂  

- 建造星际组装厂可以让你在恒星上制造物品，你最多能设置4种配方，同时需要在同一个星系内的地表建造[物资交换物流站] ![exchangeLS.png](https://s2.loli.net/2022/11/05/v8PClEyqBNZUcIT.png) 来为星际组装厂提供原材料并接受产物。生产速度受星际组装厂分配给该配方的能量以及该配方本身的制作速度。富裕的能量会自动用来生产[集成组件] ![integratedcomponents.png](https://s2.loli.net/2022/02/25/cfWPK6xV9h2pGoH.png)，它可以以极快的速度直接组装成多种生产建筑以及物流相关的物品，甚至包括卫星配电站和人工恒星，并且不需要任何其他材料。这意味着你可以出门只带一堆集成组件。  
![QQ20221105212003.png](https://s2.loli.net/2022/11/05/6kt5HpVFIoyJh49.png)
![quickRecipes.png](https://s2.loli.net/2022/02/26/XLTB8NwbltguEZi.png)   

- 警告：原本的[组件集成装置]没有被删除，但是已经无法再制作，也已经无法使用。并且会伤害星际组装厂的工作效率，因此建议你拆除他们。如果你想接收[集成组件]，请使用[物资交换物流站] ![exchangeLS.png](https://s2.loli.net/2022/11/05/v8PClEyqBNZUcIT.png)。
- 注意：不建议选择分馏配方，这会以极其夸张的比例消耗原材料并产出很少的产物。
- 小提示：如果你用星际组装厂生产星际组装厂运载火箭，且你没有设置接收该火箭的槽位，那么该火箭会优先自动被使用来建造星际组装厂的框架。
- 小提示：同一个星际组装厂内的一个配方的产物如果是另一个配方的原材料，则可以自动在巨构内部输送，而不需要你在地表建造的[物资交换物流站]中保留对应物品的槽位。

## 晶体重构器  

- 引导光子从中子星或白矮星中剥离微晶，并送至地表。你需要在地表建造射线重构站（射线接收器）来产出卡西米尔晶体或光栅石。   
- 只能在中子星或白矮星上建造。   

## 尼科尔·戴森光束（恒星炮）

- 恒星炮能够储存恒星的能量，用以激发另一个恒星的能量涌动，引导其自身的能量攻击其所在星系的黑雾巢穴。   
- 恒星炮的建造需要经过多个阶段，你最多建造一个恒星炮。

### 其他提示  

- 在拆除所有壳面、框架和节点前，你不能改变巨构建筑的类型。  
- 引力透镜对各种不同的接收器均有效。  
- 当你在行星上建造与巨构建筑不相符的接收器，这些错误的接收器无法工作。 
- 科学枢纽和折跃场广播阵列不需要任何接收器就可以工作。在同一星系内建设任何接收器都会使其工作效率下降，无论接收器的模式如何。   
- 此mod大部分内容在游戏后期的科技解锁。巨构建筑的产出系数可能不够合理，因而会在未来的版本被调整。欢迎提出任何建议或反馈问题。    

### 安装（如果手动安装）  

1. 安装 BepInEx框架；   
2. 安装 LDBTool, DSPModSave 和 CommonAPI；  
3. 将MoreMegaStructure.dll 放入 "Dyson Sphere Program/BepInEx/plugins/"；   
4. 将"mmstabicon" 文件放入与MoreMegaStructure.dll 相同的文件夹。  

### 更新

V1.5.8：增加了恒星炮倒计时的异常检测和修正功能.  

V1.5.7：修复了一个更新恒星炮属性过程中的错误.  

V1.5.6：修复一个和蓝BUFF联动报错的bug.  

V1.5.5: 更新以适配游戏版本0.10.30.23272.

V1.5.4: 在星图界面中为恒星炮增加了激光束. 
&emsp;&emsp;&emsp;为深空来敌V3.2.0进行适配调整.

V1.5.3：移除了对PlanetById的Postpatch，以修复一个和GS的兼容性问题。  

V1.5.2：在接收器增加了一个按钮，允许你将设置应用到整个星球的全部接收器上。  
&emsp;&emsp;&emsp;增加了一个配置文件设置，可以阻止星际组装厂的UI在每次打开巨构编辑器时都强制显示。  

v1.5.1: 修复了日志文件会快速增大的bug。  

v1.5.0: 移除了所有额外的接收器/重构器，现在你可以使用游戏原本的射线接受器（已更名为射线重构站）接收物质解压器或晶体重构器的产出。你需要在UI面板设置需要接收的物质种类。    
&emsp;&emsp;&emsp;以前版本的特化接收器、重构器在新版本仍然可以使用，但你无法再制造它们。  
&emsp;&emsp;&emsp;物质解压器现在支持磁铁。  

<details>
  <summary>点击展开更新日志 | Click to view all </summary>
v1.4.1: 修复了一个恒星炮开火时特效方向不正确的bug。  
&emsp;&emsp;&emsp;修复了一个复制粘贴巨构接收器的模式时，粘贴成功却不弹出粘贴成功提示的bug。  
&emsp;&emsp;&emsp;已知问题：读取恒星炮正在开火时的存档会出现汇聚激光指向错误方向的问题。  
&emsp;&emsp;&emsp;新增了性能统计数据（测试中）。  

v1.4.0: 为物质解压器的相关接收器增加了原矿模式，现在，你可以选择产出原矿而非冶炼后的矿锭。  
&emsp;&emsp;&emsp;除了游戏原本的射线接受器外，巨构相关的接收器在被建造时会被默认设置为物质合成模式。  

v1.3.11: 增加了一个新的兼容性改动，恒星反应釜现在会正确地将创世之书新引入的化工配方类型视为化工配方。

v1.3.10: 增加了新的特性来适应新版的深空来敌mod.    

v1.3.9: 修复了一个和GS2冲突而产生的错误。  

v1.3.8: 将水滴的叠加数量增加至10来匹配深空来敌的游戏性。
&emsp;&emsp;&emsp;同时，更新了水滴的描述来告诉玩家需要更改太空编队的类型来使用水滴。   

v1.3.7: 更正了水滴的描述错误。  

v1.3.6: 恒星炮前几阶段的充能时间被缩减，第一阶段的开火时间增加至2分钟。  
&emsp;&emsp;&emsp;适配深空来敌3.0.0。  

v1.3.5: 修复了一个存档时内存使用异常增加的bug，但这个版本后，（仅）星际组装厂的生产统计数据不再会被存档，意味着你每次读挡都会丢失他们。  
&emsp;&emsp;&emsp;移除了数据统计的不必要计算，减少了巨构数据统计部分对游戏性能的消耗

v1.3.4: 修复了一个和创世之书一起安装时部分配方消失的bug。  

v1.3.3: 修复了一个和GS2一起导致统计数据更新时报错的bug。  

v1.3.2: 修复了一个和创世之书的配方冲突的bug。
&emsp;&emsp;&emsp;默认隐藏尼科尔-戴森光束的科技。  

v1.3.1: 修复了一个和BlueprintTweaks不兼容的bug。  

v1.3.0: 新增：尼科尔-戴森光束科技及恒星炮巨构，可以远程射击并摧毁太空黑雾巢穴。恒星炮的数值目前正在测试中。   
&emsp;&emsp;&emsp;星际组装厂的每个配方现在可以输入额外的生产速度限制（默认无限制）。  
&emsp;&emsp;&emsp;为原始的射线接受器添加升级选项，可以升级为不同种类的接收器。  
&emsp;&emsp;&emsp;修复了一些数组越界的bug。  

v1.2.1: 修复了一个和GigaStationsUpdated不兼容的bug。  

v1.2.0: 更新以适配游戏版本0.10.28.21247。  
&emsp;&emsp;&emsp;所有星际组装厂的配方数量由4个提升到15个，但后续的配方槽位将随星际组装厂总速度倍率提升而逐渐解锁。  
&emsp;&emsp;&emsp;新增星际组装厂特化功能，当星际组装厂的配方设定满足一定要求时，星际组装厂会逐渐向特化进行，特化完成后为某些配方提供额外的速度或增产加成。  
&emsp;&emsp;&emsp;现在，星际组装厂的产出统计在统计面板中具有专门的选项页，就像一个独立的行星一样，并且支持bottleneck。  
&emsp;&emsp;&emsp;为星际组装厂的配方增加增产指示，如果输入的原材料已喷涂了增产剂，你可以在UI中看到已增产的标志和统计信息。  
&emsp;&emsp;&emsp;现在巨构接收器具有独立的一行快捷建造栏。    
&emsp;&emsp;&emsp;修复一个巨构编辑器界面的文本错误。  
&emsp;&emsp;&emsp;修复一个增产的配方统计产出数量错误的bug。  
&emsp;&emsp;&emsp;更新了火箭图标，该图标由创世之书1群群友L提供。  
  
v1.1.10 & v1.1.11: 现在建造和巨构类型不相符的接收器不再会影响巨构的正常功能或正常能量产出，当然这些错误的接收器也无法再工作了（无论设置成什么模式）。当你建造了错误的接收器，你会在接收器的UI面板里看到告诉你 “巨构不符” 的提示。

v1.1.9: 科学枢纽的火箭前置科技已被更改为任务完成科技。  
&emsp;&emsp;&emsp;仅针对创世之书mod做出了如下平衡性调整：科学枢纽现在需要你去发射宇宙矩阵来填充壳面（而非以前的太阳帆）。此外，在你将巨构类型更改为科学枢纽后，所有已发射在本星系的太阳帆将被自动移除。在创世之书中，科学枢纽火箭的前置科技为：不再是菜鸟的证明。  

v1.1.8: 修复了一个bug，该bug曾导致如果你安装了深空来敌mod，物资交换站无法随着正确的科技解锁。

v1.1.7: 对发射井逻辑的微小修复。  

v1.1.6: 现在此mod支持1000个星系，但这需要你在配置文件中将Support1000Stars设置为true。（你需要先运行一次游戏才能在配置文件中更改此项设定）  
&emsp;&emsp;&emsp;现在星际组装厂不再会浪费原材料。你也可以通过修改配置文件将这个设定改回之前的版本。  

v1.1.5: 完成对创世之书mod的兼容，现在如果你同时安装了此mod和创世之书mod，部分合成配方、科技路线将会适当修改以避免不兼容的问题。    
&emsp;&emsp;&emsp;修复了一个星际组装厂在工作时除以0的bug。  
&emsp;&emsp;&emsp;新增星际组装厂内部仓储显示，现在地面未能接收的产物被暂存在星际组装厂的巨构中的具体数量是可见的。  
&emsp;&emsp;&emsp;新增了一个设置，该设置可以让你非线性地调整星际组装厂的能量分配。具体来说，能量分配比例可以在低分配量时更精细地调整（最小0.01%）。  
&emsp;&emsp;&emsp;现在，星际组装厂的巨构编辑页面会显示星际组装厂的总工作速度倍率，而非能量瓦数。

v1.1.4: 现在，仅当一个配方的所有产物都填满了星际组装厂内部的储藏空间（10000个/类物品）时，该配方将停止消耗原材料并停止生产。  
&emsp;&emsp;&emsp;修复了一个将物品手动放入物资交换物流站上限不足10000的槽位时，交换物流站会将这些溢出上限的物品吞掉的bug。  
&emsp;&emsp;&emsp;修复了一个将速度比例设置为负数可能产生的问题。  

v1.1.3: 修复了一个bug，该bug曾导致多个星际组装厂之间的能量分配互相影响。  
&emsp;&emsp;&emsp;修复了一个因为星系不存在任何地表产出/消耗而导致星际组装厂报错的问题（正常游戏中并不会出现这种情况）。  
&emsp;&emsp;&emsp;修复了一个因为星际组装厂能量值为负导致能量回正后长时间无产出的bug。  
&emsp;&emsp;&emsp;修改了速度比例的默认数值，如果你之前安装过1.1.2版本，这个改动不会影响你的游戏。  

v1.1.2: 修复了一个因为交换站导致null报错的bug。  

v1.1.1: 星际组装厂的制造基准速度可能不合理，因而现在可以被玩家修改，请在config文件中修改。  
&emsp;&emsp;&emsp;修复了一个星际组装厂实际制造速度和显示的理论最大速度相差60倍的bug。

v1.1.0: 重做星际组装厂，现在他可以选择配方来制造几乎任何物品。请查看星际组装厂介绍。

v1.0.3: [集成组件]现在可以合成[量子化工厂]。
&emsp;&emsp;&emsp;各种接收器可以通过升降级互相切换（但受限于游戏升降级建筑的逻辑，相距超过2级的需要中间建筑才能互相切换），这可能会使得该mod适配BlueprintTweaks。  
&emsp;&emsp;&emsp;修复了一个进入戴森球编辑器界面时的文本错误。  

v1.0.2: 修复了一个在2k或更高分辨率下较高的按钮无法被点击的问题。  
&emsp;&emsp;&emsp;提供了一个可以关闭按钮弹出和收回动画（从而使其立即弹出或收回）的config设置。  

v1.0.1: 规划巨构建筑的按钮被放回了巨构面板的左下角，为了避免遮挡游戏原有按钮，新的按钮会在不用时自动隐藏。  
&emsp;&emsp;&emsp;更正了一些文本错误。  
&emsp;&emsp;&emsp;修复了一个导致恒星炮建造进度是负数的错误。  
&emsp;&emsp;&emsp;增加了游戏后期通过科学枢纽获取元数据的数量。   
&emsp;&emsp;&emsp;自动放入背包的多功能组件提示信息不再会在编辑巨构时反复弹出。  

v1.0.0: 现在，星际组装厂产出的多功能组件可以选择直接被远程传送至机甲或使用接收器接收。具体描述见上方星际组装厂。    
&emsp;&emsp;&emsp;现在科学枢纽将根据产出科研点的速度提供少量元数据。  
&emsp;&emsp;&emsp;更正了一些文本错误。将巨构按钮移到了上方以免遮住游戏原本的一些按钮。       
&emsp;&emsp;&emsp;与另一个mod *They Come From Void* 进行联动并添加了新的巨构：尼克尔戴森光束。尼克尔戴森光束只有在你安装了该mod的2.0版本后才可用。为平衡，科学枢纽的研究速度仅在该mod中被削弱至1/3。 
 
v0.4.1 & v0.4.2: 更新以适配游戏版本0.9.25.11985。

v0.4.0: 修改了一些物品图标，新增了一些指示说明。修复了一个在外太空航行时打开巨构编辑界面会导致报错的bug。

v0.3.3: 优化科学枢纽产出研究速度的计算逻辑。  
&emsp;&emsp;&emsp;现在科学枢纽可以独立完成解锁任何科技的全过程。

v0.3.2: 科学枢纽的基础研究速度还原至最初版本，但每级科技提供的加成由100%下调至1%。

v0.3.1: 修复一个图标缺失的问题。

v0.3.0: 现在新物品（除了新的接收器）可以出现在生产统计面板中；   
&emsp;&emsp;&emsp;  新增了两种接收器来接收高能石墨和光栅石。

v0.2.0: 科学枢纽的基础研究速度被降至原有的1/10；
&emsp;&emsp;&emsp;  修改部分游戏内的戴森球文本描述。

</details>
