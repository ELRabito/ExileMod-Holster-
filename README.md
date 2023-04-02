# ExileMod-Holster+
- Keeps the firemode on weapon switch/holstering instead of resetting every time. 
- Also works for under-barrel modes or sidearms with full auto mode.

# Installation

Make a Customcode override for the following three Exile functions in your missionfile or merge the code if they already exist!
* 1. ExileClient_gui_hud_event_onKeyDown
* 2. ExileClient_gui_hud_event_onKeyUp
* 3. ExileClient_object_player_stats_reset

* __For merging the code parts are commented with /* Holster+ Start*/ & /* Holster+ End*/__
* 1. ExileClient_gui_hud_event_onKeyUp contains multiple code blocks for the buttons 1,2,3,4 (Search for the /* Holster+ Start*/ & /* Holster+ End*/ parts).
* 2. ExileClient_gui_hud_event_onKeyDown is for the binocular related stuff. 
