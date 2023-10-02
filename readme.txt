Scripts in this folder are designed to obtain a list of currently installed workshop mods, update those mods, and startup the barotrauma server.

ListGen.bat creates mods.txt containing all mods within the barotrauma servers installed mods path

Barotrauma Mod Installer launches SteamCMD executing the modinstaller.txt script, the mods within this script need to be manually updated(TODO: automation). The script installs all the workshop mods and updates them.

copy.bat moves all the mods from the default SteamCMD install path to the correct barotrauma server path.

Barotrauma Startup launches SteamCMD executing the startup.txt script. This runs the actual server.

The mods obtained in this way are not automatically added to the Barotrauma server config, and must be added manually(TODO: automation)