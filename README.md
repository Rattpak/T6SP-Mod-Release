# T6SP-Mod | Black Ops II Singleplayer Client Modification

## How to use
Download the latest T6SP-Mod-Launcher.exe and t6sp-mod.dll and place them in the Black Ops II root folder. Run the launcher executable

## Features
- Internal Developer Console
- External Developer Console
- DVARs Unlocked
- GSC/CSC Overriding
- Non-Internal Rawfile Overriding
- Reimplemented Stripped Commands and Features
- Custom Commands and DVARs
- Reimplements Certain Game Console Outputs

## What This Mod Does NOT Do
- This mod does **NOT** enable piracy in any way
- This mod does **NOT** bypass any Steam checks

## Reimplemented Commands / DVARs
- **noclip**
- **god**
- **cg_thirdperson**
- **r_fog**
- **fx_enable**
- **dvardump**
- **listassetpool**
- **version**

## Custom Commands
- **dvardump_v** - A verbose dvardump
- **dumpLua** - Dump all loaded LUA files
- **dumpRawfile** - Dump all loaded Rawfiles
- **savepos** - Save current player position
- **loadpos** - Load saved player position
- **unlink** - Unlink the player for any active link

## Custom DVARs
- **g_dumpscripts** \<1 or 0\> - Dump scripts on next map load
- **g_friction** \<float\> - Adjust friction
- **r_drawskybox** \<1 or 0\> - Toggle skybox rendering
- **r_drawtransparent** \<1 or 0\> - Toggle transparent rendering

## How to modify game assets
(Only gsc/csc and non-internal rawfiles at the moment)
- Place assets to override into root/spmod/\<path of asset to override\>
- Example: root/spmod/maps/blackout_util.gsc
- Example: root/spmod/_load.gsc
- Example: root/spmod/vision/sp_front_end_menu.vision


## Troubleshooting
- **Launcher Not Working**: Sometimes steam cloud may get an error and prevent the game from launching properly. In this case you can just run the mod again. If the issue persists, disable steam cloud sync for Black Ops II: Campaign or leave a message in the Discord Server

## Other Info
- **T6SP-Mod Discord Server**: https://discord.gg/Wbb5YMZrHG
- **Keep Track of Development**: https://trello.com/b/WDZknymV/t6sp-mod-tester-feedback
