# tf2-competitive-server-menu
SourceMod custom menu used for the TF2 competitive setups

## Features
- reduced map pool in the *Choose Map* submenu to competitive maps only + a few fun custom maps
- moving certain players to another team/spectators
- moving all players to the spectators
- **LAST TO SPECT** center message for all players
- kanker-on/off configs disabling offclassing on 6v6 mode
- mały's slow bball config with slow respawns
- switching on/off:
  - tv_delaymapchange_protect
  - mp_switchteams
  - mp_tournament
  - tftrue_freezecam
- on-click ETF2L, UGC and RGL configs in their perspective submenus
- Ready-UP mode setup (experimental, doesn't work while the SOAP-DM is enabled on the server)


## Dependencies:
- SourceMod (can be 1.8 or later), I suggest using development version: https://www.sourcemod.net/downloads.php?branch=dev
  - basecomm.smx, basevotes.smx, adminmenu.smx, basebans.smx **must** be enabled
- "Change Team" (1.0.1) by MrSquid (a plugin used for moving players between teams): https://forums.alliedmods.net/showthread.php?p=2612092

## Instalation
Download this repository as a ZIP file and unpack it in the **tf** folder.