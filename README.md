Youtube video: https://youtu.be/88Edgxo5ysE
# Xenoblade modding notes (Dolphin .iso)

(Dolphin itself contains gecko code mods and supports custom textures)

## Models:

+ Dolphin Configuration ['Paths'] (select the folder where the XC ISO is located to display the ISO on Dolphin's main window);

+ Right-click the ISO / Properties/ Filesystem/ Extract Whato you want by Right-clicking;

+ Use 'U8mii' to Unpack lang/en/static.arc and put all the '.pkh' files obtained where the '.pkb's are;

+ Use 'QuickBMS', select 'falo.bms' and the pkb you want (models are in CHR.pkb and OBJ.pkb), select an output folder and you'll get '.brres' files;

+ Use 'BrresViewer' to view and search for models (click “open file” and select the '.pkb' to open all the models);

+ Model Swap: put  a '.brres''s name on another, replacing the original on the folder you created with 'QuickBMS';

+ Run 'Reimport.bat' and select 'falo.bms', the '.pkb' and the folder you created again;

+ Run 'Wiiscrubber', select the Xenoblade ISO, replace the original '.pkb' with the edited one by right clicking; wait and close 'Wiiscrubber'.
___
## MAPS:

+ Use 'falo.bms' on 'map.pkb' and 'map.bms' on the 'dap' files you get (you'll end up with '.map' files that can be viewed on 'BrresViewer').

('.Brres' can be renamed into '.map and vice versa')
___
## AUDIO:

+Use 'adx.bms' on 'adx.pkb' for Music

+ Place 'ahx.pkb' on 'ahx.exe' for Voice Lines (Battle & Dialogue)

(Both can be analyzed on AFS explorer)

Cutscenes are on [ISOroot/ev/realtime/EN]
