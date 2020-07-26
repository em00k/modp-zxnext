# modp-zxnext
 Amiga Module Player dotcommand for the ZX Spectrum Next - NO pi0 required

As always best results on hardware.

.modp by David Saphier / em00k  - ModPlayer by Mike Dailly (c)2020
Mike's git here : https://github.com/mikedailly/mod_player

https://www.youtube.com/watch?v=Xo5NORTXqXs

Note playback rate is 12750 mono, samples will be "resampled"

.modp will play Amiga MOD files, currently not all effects are supported. 
Effects 1,2,B,C,D,F are supported. Some MODs will require adjustments.  

requires modvol.dat file in /SYS, this has been included. 
modp should be placed in to your /DOT folder

Please note that banks 16 onwards are used depending on the size of
the module. Banks 16-17 are backed up and restored on exit. Next Basic
should assign banks from the end of RAM, this should help avoid 
bank clashing. 

run the demo modp-example.bas 

Usage :

From NextBasic

 .modp mymodule.mod 

If you want to suppress the text set reg 127 to something other than 255. 
Please note not every module will work at this time so you may be better writing one
within the limits of the current player - the following modules stay within these 
limits. 

mods included 

- complications by Tomas Danko
- feel by firefox
- jagtitle by nuke
- axelf by unknown 
- macrocosm by firefox
- belevme by bbd 
- saturation by uncle ben
- quadrangular_ball by uncle ben
- jarresque by heatbeat 
- Monty-Hiscore.mod cover by romeo knight original by Rob Hubbard 
