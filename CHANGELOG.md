# Changelog

Follow the latest changes on GitHub: https://github.com/fadeinside/s3air-mania-styled-blue-spheres

## Update v2.1 (2022.09.19) - Compatibility with the new version of AIR

* Changes for compatibility with v22.08.13.0+ (Required v22.09.10.0+).
* Sharp horizon sprites now matches the new sharp ground.
* Removed old mod check system.
* Removed mod Options.
* Small fixes.

## Release v2.0 - The Release 2

Mania-Styled Blue Spheres receives a new update in the form of a migration to the "Blue Spheres Sprite Mod Support" framework functionality and few improvements. -Fade

* Migrate to the "Blue Spheres Sprite Mod Support" framework functionality (Requre to install).
* Adjustments to support latest changes of "Sonic 3: D.A. Garden Edition" by Thorn_SRetro.
* Added compatibility with "Extra Slot Ray" by iCloudius (Install it below).
* The rings will now be moved closer to the ground when approaching the camera.
* The way of "picking up" rings is now similar to how Mania does it.
* The background horizon is now painted to fit Mania's style more.
* Updated the icons of the mod.

## Update v1.0.5 (v1.05) - The compatibility and polishing

* Added address compatibility with "Extra Slot Mighty" by iCloudius, now you don't need to use an Addon to make it work (Required latest version 3.0+ of Extra Slot Mighty, and install it below).
* Added compatibility with "Sonic 3D in 2D Ring Glow Effect" by GFX32 (Can be installed in any order).
* Added compatibility with "Blue Sphere Time Attack" (Install it below).
* Added "Switchable" mode for "Render mode" - Now you can switch characters between each other with the [Y] key.
* Tails' tail now has a full framerate, before that it was somewhat limited.
* Mighty is now correctly detected if a special stage was loaded from the Level Select.
* The second character now playing the sound of spring when touching a Yellow sphere.
* Optimized some functions.
* Reduced ring size.
* Other minor fixes.

## Update v1.0.4 (v1.04) - New year release

* The features of Extra Characters were removed from the code, and were moved to a separate mod - "Extra Characters support for Mania-Styled BS" (Install it higher, requires Extra Character Slots below). Thanks to this, the work with the checking and rendering of Extra Character has been simplified.
* Tail's tails is now rendered in its function and corresponds to the speed of the globe. Check fn009488(), I just removed the frames limit in objA0.animation.sprite to achieve full animation of the tails, instead of using the fixed speed of global.framecounter in renderhooks.
* Added the "Ground render" option. Use the Sharp to make the globe sharp. This only affects if you have enabled the Classic Blue Spheres style, otherwise, the default value will be used.
* Added the "Player render" option. Use Only Main to hide the Second character. Works only in the main game, ignoring Blue Spheres game.
* Added the "Spheres Counter" option. Use Counting Up to show the number of collected spheres instead of the remaining ones.
* Refactor of scripts folder and names of sprite files in order to avoid accidentally identical names in other mods.
* We have finally reached the cool icon for the mod.
* And few fixes.

## Update v1.0.3 (v1.03) - Mighty compatibility release

* Optimized character rendering code.
* Fixed character sprites flashing when colliding with a bumper.
* Added compatibility with Extra Slot Mighty (Install it below).

## Update v1.0.2 (v1.02) - The Final release

* The audio files have been converted and compressed for a smaller size.
* Added extra frames to fully display the Jump animation.
* Added sprites and keys for Mighty and Ray.
* Added compatibility with Ultimate Mighty (Install it below).
* Added compatibility with Ray the Flying Squirrel (Install it below).
* Correct LoopStart for "1c_speedmax".
* Other minor fixes.

## Update v1.0.1 (v1.01) - D.A. Garden compatibility release

All thanks to Thorn_SRetro for this update, if it wasn't for him, then most likely I would have released a patch for the animation speed of Miles' Tails. To work correctly with D.A. Garden Edition, install its mod below this. To play Mania MAX speed track with the Blue Sphere plus mod, install its mod above this. For the Yellow Emerald and 3D Side View Chaos Emeralds mods, it is only important that they are in the list of active mods, and not the priority value.

* Compatible with the D.A. Garden Edition mod (Install it below).
* Function ManiaSpheres.renderChaosEmerald() now correctly matches the value of the Emerald color by the stage number, including secret stages through Level select and Mini-game mode.
* Restored original mechanics of obtaining an Emerald in game Special stages.
* Music files are now at a lower volume to match the AIR.
* Added music file 1C_speedup45 to make the music and stage speed-ups align properly in the dedicated Blue Sphere mode or if random layouts are chosen for the main game.
* Fixed the max speed of Miles Tails when Special stage was been cleared.
* Fixed incorrect Yellow Sphere sound effect.
* The dev folder, unused Label_1P/Label_2P sprites and their keys were deleted.
* Various optimizations in the script.