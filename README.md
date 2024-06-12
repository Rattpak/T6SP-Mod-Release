# T6SP-Mod | Black Ops II Singleplayer Client Modification

## How to use
Download the latest T6SP-Mod-Launcher.exe and t6sp-mod.dll and place them in the Black Ops II root folder. Run the launcher executable

## Info
- **T6SP-Mod Discord Server**: https://discord.gg/Wbb5YMZrHG
- **Keep Track of Development**: https://trello.com/b/WDZknymV/t6sp-mod-tester-feedback

## Features
- Internal Developer Console
- External Developer Console
- DVARs Unlocked
- Custom GSC/CSC loading
- GSC/CSC Dumping and Overriding
- Mapent Dumping and Overriding
- Non-Internal Rawfile Overriding
- Reimplemented Stripped Commands and Features
- Custom Commands and DVARs
- Reimplements Certain Game Console Outputs
- Autoexec `config_sp.cfg` on game startup
- Autoexec `persistent_sp.cfg` on each level change

## What This Mod Does NOT Do
- This mod does **NOT** enable piracy in any way
- This mod does **NOT** bypass any Steam checks

## Reimplemented Commands / DVARs
- `noclip`
- `god`
- `cg_thirdperson`
- `r_fog`
- `fx_enable`
- `dvardump`
- `listassetpool`
- `version`
- `bind`/`unbind`
- `player_sustainAmmo`

## Custom Commands
- `dvardump_v` - A verbose dvardump
- `dumpLua` - Dump all loaded LUA files
- `dumpRawfile` - Dump all loaded Rawfiles
- `savepos` - Save current player position
- `loadpos` - Load saved player position
- `unlink` - Unlink the player for any active link
- `saveassetpool` Like listassetpool, but saves results to assetpool.txt
- `widget add <dvar name>`  Create an on-screen widget for the specified DVAR
- `widget remove <dvar name>`  Remove the on-screen widget for the specified DVAR
- `widget clear`  Remove all on-screen widgets
- `widget hideall`  Hide all on-screen widgets
- `widget showall`  Show all on-screen widgets


## Custom DVARs
- `g_dumpscripts` \<1 or 0\> - Dump scripts on next map load
- `g_dumpmapents` \<1 or 0\> - Dump mapents on next map load
- `g_friction` \<Float\> - Adjust friction
- `r_drawskybox` \<1 or 0\> - Toggle skybox rendering
- `r_drawtransparent` \<1 or 0\> - Toggle transparent rendering
- `con_maxSearchResults` \<2 to 32\> - How many commands will show in search box
- `sv_enableBounces`\<0 or 1\> Re-enables the bounce bug from COD4
- `sv_bouncescale` \<Float\> The scale of the bounce

## How to modify game assets
### Overriding Game Assets
(Only gsc/csc, mapens, and non-internal rawfiles at the moment)
- Place assets to override into root/spmod/\<path of asset to override\>
  - Example: root/spmod/maps/blackout_util.gsc
  - Example: root/spmod/_load.gsc
  - Example: root/spmod/maps/frontend.mapents
  - Example: root/spmod/vision/sp_front_end_menu.vision

### Loading Custom Assets
(Only gsc/csc at the moment)
- Place custom assets in root/spmod/custom/\<path to custom asset\>
  - Example: root/spmod/custom/maps/modmenu.gsc


