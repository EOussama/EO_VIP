# EO_VIP
---

## DESCRIPTION
This is a project started in the 1th September 2016, It's an ongoing project, which would provide new features every update,
This is a VIP based system filerscript, which would focus on granting you an ideal VIP system, and the less complicated overall previous on.

## INSTALLATION
- **1** put **EOVIP.pwn** inside of your *filterscripts* folder.
- **2** put **eovip.inc** inside of *pawno/include* folder.
- **3** open the EOVIP.pwn with your text editor and compile it.
- **4** go to your **server.cfg** and add : `EOVIP` on *filterscripts* line.
- **5** open up **database.sql** and execute the code to create a database with the `VIPs` table.

## Credits
> a_samp		      by **SA_MP team**

> a_mysql			    by **BlueG**			>	github.com/pBlueG/SA-MP-MySQL/releases/tag/R41-2

> streamer		    by **incognito**			>	github.com/samp-incognito/samp-streamer-plugin/releases/tag/v2.9.1

> sscanf2			    by **Y_Less**			>	github.com/maddinat0r/sscanf/releases/tag/v2.8.2

> iZCMD			      by **Zeex and Yashas** 		>	github.com/YashasSamaga/I-ZCMD

> YSI\y_timers		by **Y_Less and Misiur**		>	github.com/Misiur/YSI

> eovip			      by **Oussama**

## Features
- [X] VIP Expiration is even more solid.
- [X] Code optimization.
- [X] More control over the filterscript.
- [X] Detailed information on /vipaccount.

## Update Log
```
Version 1.8(13/7/2017)================================
VIP Expiration is more solid
re-Added VIP Toys
Menu bug fixes

Version 1.7(10/7/2017)================================
Converted to MySQL

Version 1.6(30/1/2017)================================
Converted from INI to SQLite
New RCON admin command /vipcount
Many bug fixes

 Version 1.0(13/10/1026)================================
organize the vipcmds
game text for player when demoted/promoted
string extended
text colors
/isvip see whe is a vip(need fix) or simply click on his name
weather id dialog shows only availabe level weather ids
level 4 can load any weapon preset
vipacc yes/no bug
toys(objects)

 Version 1.0(11/10/1026)================================
/vipbtp for level 4
/vipcmds updated
/viphelp updated
armour level 4 reduced to 90
change weather command
mistakes text fixed
fix acount types mixing bug
change time
fix vehicle sound when using fixing commands
spawn in base
vip tag removing
vip random tips each 15 mins
playsoudplayer hear only in outside near the door
/givecash from distance
advertising to VIP STATS VIA A TO ALL MESG
vipacc Account type bug/optimization
change skin
/vips turned into dialog based cmd(need to test)

 Version 0.8(9/10/1026)================================
script optimizastion
vip gate auto close
Gate make noice when operating
car 3d label
a client message would be sent to only VIP inside of the loung if someone enters/left the vip lounge
3d taxt would be destroyed with the vehicle, and respawned with it
VIP GUN PACKS(3 packs)
/viptag to show off your vip level
nitro added to vip cars
cars set to 37 cars
/vipnos add nitrous
/vipefix fix a vehicle's engine
/vehicle flip a vehicle
/vipbfix vehicle body fix

 Version 0.5(8/10/1026)================================
vip car color set to yellow
vip cars reject non vip players
vip gate (functionable)
vipcmd updated
color changing to various text colors
disconnect data save
timer expires in connect
text when you get in the house

 Version 0.3.5(7/10/2016)===============================
Added /vipacc command - Displays extra info about one's VIP level (Rank, Account type, registration date, days left...)
Added /carc command - Changed vehicle color (only for VIP level 2, 3 and 4)
/vipcmd is updated
added Level 3 VIP would spawn with 40% armour
added Level 4 VIP would spawn with 100% armour
/carc command would charge VIP levels with different costs + discounts depending you how high the level is
Chat clear on spawn
VIP account will expire after 30 days
Data base 
Script optimization
The date when the VIP account was set is now saved into the VIP .in! file to provide extra information
Bug Fixes 
Console printf bug fixed
VIP Lounge walls and lot was specified and partly mapped(work wtill in process)
3D label included

 Version 0.2(6/10/2016)===============================
/vipcmd - displays a usefull collection of commands related to your VIP level
/viphelp - additional information about your VIP leve; e.g(features)
/vips - list of connected VIPs
spawn Client message bug fix
armour at spawn for lvl 3 and 4 (40% and 100%)

 Version 0.1(5/10/2016)===============================
4 different VIP levels (1-Silver/2-Gold/3-Platinum/4-Diamond)
Strong and secure DATA saving system with YSI\y_less a VIP chat

=====================================================
```

## Using terms
If you consider using this filerscript on your sever or edit it for any reason, you MUST all contributers,
please do not ignore this!
