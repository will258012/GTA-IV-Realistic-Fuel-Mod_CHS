
## GTAIV-Realistic-Fuel-Mod 汉化版

该脚本基于Pedro Rodrigues制作的[Ultimate Fuel Script v2.1.0.0](https://www.gtainside.com/en/gta4/mods/47700-ultimate-fuel-script-v2)和Sandakelum制作的[Realistic Fuel Script 2.3.145.20929](https://www.gtagaming.com/realistic-fuel-mod-2-2-0-5-f22621.html)。
这个脚本适用于GTA IV完整版 (1.2.0.xx) 。

# 安装
## 在安装此脚本之前，请先安装[GTAIV完整版 的汉化补丁](https://b9348.gitee.io/index.html)。
这是显示中文字符的前提条件。
将[Releases](https://github.com/will258012/GTA-IV-Realistic-Fuel-Mod_CHS/releases)中下载的文件解压缩至游戏根目录。

# 注意
此脚本还使用了原版本的GUID（3583e09d-6c44-4820-85e9-93926307d4f8）。
所以不要同时使用这两个脚本，否则会在某些事件中引发冲突。

# USAGE
You don't need to worry, every help and which keys you should use will be
provided to you as ingame instructions when you using this script. And almost
everything is customizable to your needs.

# 工具
如果需要更改燃油表的显示位置，请使用DashboardPositioner.exe。

# 更新日志


2.4.x.x
FIX Ported to GTA IV version 1.2.0.43.

2.3.x.x
NEW A whole lot of fuel stealing locations all around Liberty City, and more to come. (Thanks to yoshiko, for providing a lot of locations)
NEW Added a new fuel station that somehow we've never noticed.
NEW Optional parameter DISPLAY added to all fuel station types. Read stations section at ini file.
NEW Optional software download to simplify moving the fuel gauge around the screen. Check section HELPFUL DOWNLOADS of this file.
CHANGE Big changes in the message display system, might still not be perfect.
CHANGE Fuel bottles now give you 12 of a tank, instead of 13.
CHANGE Mod version scheme, changed to Major.Minor.Revision.Build, you can get the specific code for a version by checking out the trunk folder with the revision specified in the mod version.
FIX Compatability fix for indicator mods.
FIX Fixed potential script crash when using fuel bottle in a bus.
FIX Reserve sound path incorrect.
FIX Minor fixes to Emergency Fuel Service animations.
NOTE Some of the new features might miss source code comments.

2.2.0.4
NEW Emergency Fuel Service! Call to GET-555-FUEL (438-555-3835) or press K (if phone number checks are not working on yours) to call a emergency fuel bouser, which will enter your scene when you ran out of all options (no fuel bottles and couldn't reach to a fueling station in time).
NEW Now you can set how much fuel bottles player can carry as maximum (MAXFUELBOTTLES).
NEW Now you can set how much free fuel bottles should be added to the player's inventory when the game loaded (FREEBOTTLES).
NEW Now you can set how much should player spend to get one fuel bottle (FUELBOTTLECOST).
NEW Now you can set how much should player cost to get emergency fuel service call (SERVICECOST).
NEW Now you can set which key should press to call emergency fuel service if phone number checks are not working (calling won't work) by SERVICEKEY.
NEW Added text notification configurations for EMERGENCYCALLTEXT, EMERGENCYONWAYTEXT, EMERGENCYAGENTTEXT, EMERGENCYDONETEXT.
CHANGE Optimized FuelScript_Tick() function to be calculated a little more faster.
CHANGE Added back Play() function to play embedded sound when player enters to the reserved fuel on a vehicle.
FIX Fixed few percentage and amount calculators to use String.Format() which is a little more faster in overall performance (Solution by Pedro).
FIX Beta versions doesn't say that it's a beta properly.
FIX Crash when player gets back to vehicle after refueling his vehicle with a fuel bottle.
FIX Crash when player luckily gets to a fueling station even when no fuel (using the speed he gained in the vehicle).
FIX Fixed few comments which were commented with wrongful meaning.
FIX Fixed script crash when player taking too much time to get back in vehicle after injecting a fuel bottle (known when player runs on lower FPS than game playable FPS, it crashes as player takes too much time to get back on vehicle).
FIX Fixed unwanted double if checks which can be collapsed into one check.
FIX Dozen more minor bugs has been fixed.
NOTE Fully commented newly added features and functions on the source code.

# FAQ
Q. GTA prompted an error  GTA IV FATAL ERROR Invalid resource detected - Please re-install the game.
A. Just retry, the error should be gone. It sometimes happens when running the script for the first time.

Q. Can I add entries in the settings (.ini) file for added, not replaced cars 
A. Yes, use a trainer (Simple Native Trainer is recommended) and take note of the HASH code for that specific car. Open the settings file copy and paste any carbikeboatheli entry, and change the name of vehicle (inside []) to the hash code of your car. The values specified in this new entry should be loaded for your added cars, there is no limit to how many entries you can have.

Q. 能添加偷取燃油的点位吗？
Q. 如果你想添加一个新的点位，
