(╯°□°）╯︵ ┻━┻) 
by CoreLogic 2015 

#[What is it?] 
A fun mod that turns each death into table flipping fun. 
But, that's just getting started. The real fun is you are free to add/remove and select any objects in the GTA V universe to spawn and flip! 

#[How does it work?] 
The mod starts by scanning the area and building a list of unique "seenPeds", then checks this list if any have died. When a dead ped is found, we apply force to the body, then remove it and then spawn the list of objects, applying force to each. The mod will loop over FTT.objects[] list and spawn them at each ped's death. You can have one or none, or a long list, it's up to you. 

#[How To Play]	
Use the 'del' key to start, (you will see msg over map change) then go to work. You are invincible while the module is loaded. 

#[HUD] 
-T:{n} - Number of new seen peds (targets) 
-K:{n} - Number of peds killed 
-O:{n} - Number of objects spawned 

#[Flip All The THINGS!] 
Try different objects and settings, even with only one object (like a dumpster) can be a lot of fun. Experiment with type and number of objects, force direction and force height settings.	Record your results and share on Youtube and Reddit/r/gtav_mods/. 

#[How do I change objects?] 
1) See included list_of_GTAV_objects.txt for string names. 

2) Select the names you want to use, copy the list (note, some objects just don't work, any help here welcome) 

3) For each object name, enter/edit/add FTT.objects[] list as you need 

4) Set FTT.settings["force_height"] value to the force you want applied (currently set to 5 by default) 

5) Set both FTT.settings["force_pos_x"] and FTT.settings["force_pos_y"] to change the directly objects will spawn under force 

6) Set the max number of objects you can spawn FTT.settings["max_objects"], the mod will delete all objects from the game world when this number is reached 

#[Background] 
This mod started as a clone of Death Race, an old 1970's arcade game that allowed players to drive a car and run over stick-figure peds. Each ped would then trun into a tombstone and block the path. The player would receive points for each tombstone (dead ped). It was in fact the first video game to cause public outrage and was soon banned! lol. 

Read more here: http://gamestudies.org/1201/articles/carly_kocurek 

Well, for some reason I can't get tombstones to spawn, so instead I changed the game into flipping tables. The same core game mechanics of Death Race are still in this mod, in fact if you set to Dumpster object alone, it will work in must the same way as the original game. Driving over peds causes a dumpster to appear and block your path, like the tombstones did in the original game. That said, you can play the game on foot with guns just the same. 

#[Installation] 
1. Install Script Hook https://www.gta5-mods.com/tools/script-hook-v 
2. Install the LUA script plugin for Scripthook https://www.gta5-mods.com/tools/lua-plugin-for-script-hook-v 
3. Download the FlipAllTheThings.lua file 
4. Put the FlipAllTheThings.lua file in your \Grand Theft Auto V\scripts\addins folder. 
5. Text will appear above the mini-map when installed correctly 


Copy/edit and share code. Just give credit please. 

Enjoy! 

#[Weapons] 
WEAPON_PISTOL 
WEAPON_COMBATPISTOL 
WEAPON_CARBINERIFLE 
WEAPON_ASSAULTSHOTGUN 
WEAPON_PROXMINE 
WEAPON_MOLOTOV 
WEAPON_RPG 
WEAPON_MINIGUN 
WEAPON_KNIFE 
WEAPON_HAMMER 
WEAPON_GOLFCLUB 
WEAPON_MICROSMG 
WEAPON_ASSAULTSMG 
WEAPON_ADVANCEDRIFLE 
WEAPON_COMBATMG 
WEAPON_PUMPSHOTGUN 
WEAPON_SAWNOFFSHOTGUN 
WEAPON_BULLPUPSHOTGUN 
WEAPON_HEAVYSNIPER 
WEAPON_GRENADELAUNCHER 
WEAPON_SMOKEGRENADE 
WEAPON_DAGGER 
WEAPON_HATCHET 
WEAPON_HEAVYSHOTGUN 
WEAPON_MARKSMANRIFLE
