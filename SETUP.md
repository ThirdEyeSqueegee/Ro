# First-Time Setup Instructions

## Do this BEFORE you launch the game

### Required Reading

- [FAQ](/FAQ.md)
- [Keybinds](/KEYBINDS.md)

### Framerate limit

- Set the framerate limit to your monitor's refresh rate (if using Lossless Scaling Frame Generation, set it to 1/2 or 1/3 of your monitor's refresh rate) in `SSEDisplayTweaks.ini`. The default limit is `55`, set up for use with Lossless Scaling 3x.

### Ultrawide support

1. Enable the `Dynamic Interface Patcher - Various Patches and Experiments - Universal UI Unsquisher` version corresponding to your monitor's aspect ratio (found in the `Optional - UI` section)
2. Unhide `DIP` in MO2's executables menu and click "Run"
   1. ![Edit MO2 Executables](/assets/edit_mo2_executables.png)
   2. ![Unhide DIP](/assets/unhide_dip.png)
3. Select the patch you enabled in step 1 and click "Patch!"
4. Close the window

### ParallaxGen

1. Select ParallaxGen in MO2's executables menu and click "Run"
   1. ![ParallaxGen](/assets/parallaxgen.png)
2. Press `Enter` once ParallaxGen launches to begin mesh patching
3. Wait for ParallaxGen to finish; press `Enter` to close the window when ParallaxGen finishes running
4. Cut-paste the `Ro\Tools\ParallaxGen\ParallaxGen_Output` folder to `Ro\mods`
5. Refresh MO2 and enable the newly-created `ParallaxGen_Output` mod
   1. ![Refresh MO2](/assets/refresh_mo2.png)
6. Place the `ParallaxGen_Output` mod at the very end of the modlist (overwriting everything)

### Optional mods

- There are several optional mods under the `Optional - ...` separators. If you'd like to use them:
  1. In the right pane of ModOrganizer, click on the `Plugins` tab and scroll all the way to the bottom. You should see `Occlusion.esp` at the end of this list.
  2. In the left pane of ModOrganizer, enable the optional mods you'd like to use.
  3. You'll see several new plugins pop up below `Occlusion.esp` in the right pane. Move these plugins **above** `DynDOLOD.esp`.

## Do this AFTER you launch the game

### MCM Configuration

- Go through the MCM settings and modify as you see fit, although everything has been preconfigured. You may want to look at the modpages for each mod before changing any settings.
