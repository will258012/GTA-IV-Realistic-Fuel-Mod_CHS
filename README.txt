该脚本基于Pedro Rodrigues制作的Ultimate Fuel Script v2.1.0.0和Sandakelum制作的Realistic Fuel Script 2.3.145.20929。这个脚本适用于GTA IV完整版 (1.2.0.xx)。

安装

在安装此脚本之前，请先安装GTAIV完整版汉化补丁（https://b9348.gitee.io/），这是显示中文字符的前提条件。
将所有文件解压缩至游戏根目录即可。

注意

此脚本还使用了原版本的GUID（3583e09d-6c44-4820-85e9-93926307d4f8）。所以不要同时使用这两个脚本，否则会在某些事件中引发冲突。

使用

不必担心，每一个帮助和你应该使用的键都会在你使用此脚本时作为游戏内说明提供给你。而且几乎一切都可自定义。

工具

如果需要调整燃油表的显示位置，请使用DashboardPositioner.exe。
压缩文件中的“dsound.dll” 是由ThirteenAG制作的Ultimate ASI Loader（https://github.com/ThirteenAG/Ultimate-ASI-Loader/）。

FAQ

Q. 在启动游戏时闪退或提示“GTA IV FATAL ERROR Invalid resource detected - Please re-install the game”。

A. 请多尝试几次。在第一次使用脚本时，这些情况可能会发生。

Q：我可以在设置（.ini）文件中添加新车辆的条目吗？

A.可以，请使用修改器，并记下该车辆的HASH代码。打开设置（.ini）文件，在“车辆燃油设置”部分复制一份条目,将车辆名称（方括号[]内部）更改为你的车辆的HASH代码。这个新条目中指定的值应该为你添加的车辆加载。你可以拥有的条目数量没有限制。

Q. 能添加偷取燃油的点位吗？

A. 如果你想添加一个新的点位，在设置（.ini）中的“汽车、摩托车的偷油点位”部分按格式添加。

更新日志

2.5.0.38350

新增

    汉化整个模组
    添加对EFLC部分的支持
    添加检查更新机制

调整

    因为支持问题，无法再通过电话呼叫应急燃油服务
    优化应急燃油服务的体验

修复

    修复燃油耗尽时无法显示提示的问题
    修复无法购买应急燃油瓶的问题

2.4.x.x

FIX Ported to GTA IV version 1.2.0.43.

2.3.x.x

新增

A whole lot of fuel stealing locations all around Liberty City, and more to come. (Thanks to yoshiko, for providing a lot of locations)

Added a new fuel station that somehow we've never noticed.

Optional parameter DISPLAY added to all fuel station types. Read stations section at ini file.

Optional software download to simplify moving the fuel gauge around the screen. Check section HELPFUL DOWNLOADS of this file.

调整

Big changes in the message display system, might still not be perfect.

Fuel bottles now give you 12 of a tank, instead of 13.

Mod version scheme, changed to Major.Minor.Revision.Build, you can get the specific code for a version by checking
out the trunk folder with the revision specified in the mod version.

修复

Compatability fix for indicator mods.

Fixed potential script crash when using fuel bottle in a bus.

Reserve sound path incorrect.

Minor fixes to Emergency Fuel Service animations.

注意

Some of the new features might miss source code comments.

2.2.0.4

新增

Emergency Fuel Service! Call to GET-555-FUEL (438-555-3835) or press K (if phone number checks are not working on yours) to call a emergency fuel bouser, which will enter your scene when you ran out of all options (no fuel bottles and couldn't reach to a fueling station in time).

Now you can set how much fuel bottles player can carry as maximum (MAXFUELBOTTLES).

Now you can set how much free fuel bottles should be added to the player's inventory when the game loaded (FREEBOTTLES).

Now you can set how much should player spend to get one fuel bottle (FUELBOTTLECOST).

Now you can set how much should player cost to get emergency fuel service call (SERVICECOST).

Now you can set which key should press to call emergency fuel service if phone number checks are not working (calling won't work) by SERVICEKEY.

Added text notification configurations for EMERGENCYCALLTEXT, EMERGENCYONWAYTEXT, EMERGENCYAGENTTEXT, EMERGENCYDONETEXT.

调整

Optimized FuelScript_Tick() function to be calculated a little more faster.

Added back Play() function to play embedded sound when player enters to the reserved fuel on a vehicle.

修复

Fixed few percentage and amount calculators to use String.Format() which is a little more faster in overall performance (Solution by Pedro).

Beta versions doesn't say that it's a beta properly.

Crash when player gets back to vehicle after refueling his vehicle with a fuel bottle.

Crash when player luckily gets to a fueling station even when no fuel (using the speed he gained in the vehicle).

Fixed few comments which were commented with wrongful meaning.

Fixed script crash when player taking too much time to get back in vehicle after injecting a fuel bottle (known when player runs on lower FPS than game playable FPS, it crashes as player takes too much time to get back on vehicle).

Fixed unwanted double if checks which can be collapsed into one check.

Dozen more minor bugs has been fixed.

注意

Fully commented newly added features and functions on the source code.