
# Xol-metrix Assembly

This project assumes you know how to build the standard XOL 2 toolhead with this build assembly thrown into the mix.

|	Notes	|	Image	|
|	--------------------	|	--------------------	|
|Remove the support material in orange. They should break away with ease.|<img src='images/cutter_arm_with_support.png' width=300 /><img src='images/extruder_adapter_bottom_with_support.png' width=300 /><img src='images/extruder_adapter_top_with_support.png' width=300 />	|
|Next drill out the 2 `Flanged M2` Heatset Inserts with a `5/64 inch drill bit`. Then use the `#2 center drill bit` to chamfer the top of one and the bottom of the other. ⚠⚠ **Make sure you thuroghly clean the inserts of brass when done!** ⚠⚠|<img src='images/m2_flang_view.png' width=300 />|
|Insert the `Flanged M2` heatset with the **top chamfer** into the `extruder_adapter_bottom.stl` with the flang surface flush with the printed surface.|<img src='images/m2_bottom_insert.png' width=300 />|
|Insert the `Flanged M2` heatset with the **bottom chamfer** into the `extruder_adapter_top_(your_choice_here).stl` with the flang surface flush with the printed surface.|<img src='images/m2_top_insert.png' width=300 />|
|Next insert the 3 `M2x3.5x4 Heatsets` into the 3 holes in the `extruder_adapter_top_(your_choice_here).stl`.|<img src='images/m2_top_insert_3.png' width=300 />|
|Screw the `extruder_adapter_top_(your_choice_here).stl` and `extruder_adapter_bottom.stl` together with `M2x8 SHCS` ⚠Do not over tighten!⚠ |<img src='images/top_bottom_together.png' width=300 />|
|Clean the inside of the filament path with a `5/64 inch drill bit` it may have some ooze from istalling the Heatset inserts.|<img src='images/filament_path_view.png' width=300 />|
|Place the `5.5mm Ball Bearing` in the hole on top of the extruder adapter.|<img src='images/ball_install.png' width=300 />|
|Put the `Omron D2F` (with no lever) into slot with clicker behind the Ball Bearing, secure with `M2x10 Self Tapping Screws`.|<img src='images/filament_switch_install.png' width=300 />|
|Insert one `M2.5x3.5x4 Heatset` into the hotend mount (rest of hotend heatsets are not explained refer to Xol 2 Docs).|<img src='images/frame_heatset_install.png' width=300 />|
|Install extruder adapter onto the `HE Mount` of your choice and install on your carriage of choice. (Tap option shown in picture)|<img src='images/toolhead_mounted.png' width=300 />|
|Select the Blades of your choice `#4` (Yellow) or `OLFA KB4-F/5` (Green).|<img src='images/blade_holders.png' width=300 />|
|Use the Blade Jig that coresponds with your blade of choice #4 / OLFA and clamp the blade in it with the blade sticking in. **Final length should be ~20mm.**|<img src='images/blade_jig.png' width=300 />|
|Use the `blade_install_tool.stl` to install the blade. ⚠⚠ **Take extra precaution as the blades do not care and will go through your skin with no remorse and then the red sauce comes out!** ⚠⚠|<img src='images/blade_install.png' width=300 />|
|Insure that the blade is squared up with the `[b]_blade_holder_(your_choice_here).stl`. The hole on top is big enough for an `M3 Grub Screw` or you can glue the blade in.|<img src='images/blade_squared.png' width=300 />|
|Slide the Blade Holder into the Extruder adapter carefully aligning the blade into the slot.|<img src='images/blade_holder_install.png' width=300 />|
|Install the Spring into the slot on the `[a]_cutter_arm.stl`.|<img src='images/cutter_arm_spring_install.png' width=300 />|
|Slide the cutter arm into the slot on the Hotend Frame partially **Do not kink the spring**.|<img src='images/cutter_arm_partial_install.png' width=300 />|
|Use a small slim screwdriver of sorts to persuade the spring into the recess in the extruder mount while sliding the arm into its final position.|<img src='images/spring_arm_full _install.png' width=300 />|
|Install the 2 `M2.5x15 SHCS` into the frame and blade holder to finish up the cutter install.|<img src='images/arm_screw_install.png' width=300 />|
|If using XolPAP Install the `M2.5x15 SHCS` on the back side of the arm shown here. (Thanks to scheini79 for the suggestion!)|<img src='images/xolpap_screw_install.png' width=300 />|
|After all this the rest of the XOL 2 will go together the same as the standard one.|<img src='images/final_build.png' width=300 />|
