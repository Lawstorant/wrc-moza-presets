# Improved Moza Racing presets for EA Sports WRC

To update your presets go to the `game installation directory -> Content -> input -> windows`.
Copy over all the files in this repository and overwrite if asked to. You need to restart your game for this changes to take effect.

### action_defines.xml:
- Removed protections. It's now possible to rebind menu, photomode etc. controls again.

### device_defines.xml:
- Added entry for the upcoming CRP2 pedal set. The product ID is a guess for now so it's not final. I'll update it when they arrive

### Pedals:
- Modified deadzone values for all axes. 1% by default, 20% for clutch.
- Added preset for the upcoming CRP2 pedal set.
- Fix `sub_device_name` in CRP preset. Preset shows up in the game UI now.

### SGP Sequential Shifter:
- Reversed the upshift/downshift mappings (pull for gear up, push for gear down).

### HBP Handbrake:
- Modified deadzone values.
- Map both button mode / axis mode in both presets.

### CS V2P Rim:
- Swap the usage of `BOX`/`FL` buttons to be more ergonomic (`FL` button is easier to access as `select` mapping).
- Map `dial_press`, `dial_left` and `dial_right` to both rotaries (right rotary uses `dial_2_*` variant).

### RS V2 Rim:
- Create preset based on the modified CS V2P preset
- Change `R` button usage to `reset_vehicle`
- Change `TR` button usage to `roadside_repair`
- Utilise `P` button as `pause`
- Utilise `N` button as `look_back`
- Utilise `S1` and `S2` buttons as `context_3` and `context_4`
