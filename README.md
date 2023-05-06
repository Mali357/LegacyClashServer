# LegacyClashServer Software (UCS0610 based)
Legacy Clash of Clans server (LCS)


This repository contains the source code of the server software used by LegacyClash. It's based on jeanbmar's public release of UCS 0610's source. It's way more modernized, made it more stable (80% the stability of UCS 0731) and added a lot more server-side and client-side stuff into it. New features for this C# server emulator are (and this is a comparison of UCS0610 and LCS)

-- Stablilty:
- 90% more stable than 0610, near the stability of ucs 7.x.x releases.
- Duplication bugs were fixed
- Idle resource generation was implemeted
- Idle building was implemented
- The server now properly handles dead clients
- All clans are loaded on startup
- Custom Maintance breaks.
- Better structure of debug log 
- Gameop commands are added (these commands can be used in the global chat, /myid4 as an example to get User IDs. IP adresses aren't saved in this server. every client has a unique user ID. (uninstalling and reinstalling the app kills ur progress btw))

-- Clans:
- Clan score calculation was implemented (calculation by combining every user's trophies)
- Everything in clans work except donating / requesting troops, and clanwars aren't implemented
- Clans load on startup
- Top clans chartlist works! (Time ticks down too)
- You can rebuild the clan castle now
- Creating the clan takes the proper balance away now.
- You can bookmark clans (Bookmarks reappear when returning from a fight (npc or person) or when restarting the client.)
- 

-- Leagues, trophies and players:
- Top player lists work and are functional
- You earn and lose trophes from fights(looting) (wacky feature)
- Leagues exist

- Other stuff:
- Obstacles work perfectly
- Achievements were added
- Client version 7.200 IS REQUIRED. Will be provided in the releases section
- You begin at town hall level 1 now, and the tutorial plays properly (its a timeskip after the goblin fight.....)
- Boosts work
- hero upgrades work
- reloading tesla, xbow and traps work
- more features

(note if compiling and using packager.bat doesnt work, you need to replace the gamefiles, lib, logs, tools, folders and ucs.exe.config file with the one from the LCS build that is on the releases page.)
LCS and it's server software is not affiliated with Supercell.

More Details: https://starboard-mali.neocities.org/projects/coc.html (the website is down, i will update this readme.md once it works, just use the discord.)

Help and Support: https://discord.gg/EKTJDK5MDC

Credit goes out to: https://github.com/jeanbmar/UCS
