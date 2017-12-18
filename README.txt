READ ME:
 

To install: 
1. Once you have pulled the files from GitHub, create a new folder in Quake 2. You will store the mod files in that folder. Name it however you wish.
2. Open the game.vcproj. You will compile the code and produce a gamex86.dll file. This gamex86.dll file will be located in Steam>steamapps>common>Quake2>Your mod folder name> debug.
3. Copy this gamex86.dll file and paste it to Steam>steamapps>common>Quake 2>baseq2. You will be told that a gamex86.dll already exists in that folder. Overwrite it.
4. Create a shortcut to the Quake 2 .exe and drop it onto your desktop. Right click the shortcut, go to properties, and add the following to the end of target after the end quotation marks: +set game-quake-2-mod-folder-name.
Apply and close the window. 




Following deliverables presented in the mod:

1. Blaster was modified into a "melee" weapon. The blaster is what the user MUST be using in order to tag other players. Death by any other means will not change a player's status.  
2. Player gains points through becoming "it." Player cannot lose points by suicide.
3. "It" player receives god mode ability. 
4. All other players receive quad ability to defend themselves.
5. When opening the user's stats in Deathmatch (F2), the UI will notify the player whether they are "it" or not.



****Special note: Due to lack of testers for this mod, the grenade was also modified to grant user the "it" role. Should the player die by holding onto a grenade for too long, they will also become "it."
Should the mod malfunction in any way and an "it" player is not assigned, suicide by holding onto the grenade will force assign the suiciding player to be "it."