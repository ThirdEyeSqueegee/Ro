## Rule 11

Modifying the list forfeits the right to ask for support. If you modify the list, it's at your own risk.

## To add your own mods to the list:

- Install a mod
- Rename the mod by adding `[NoDelete]` as a prefix to the name of the mod
  - E.g.: If you install `Mysticism`, rename it to `[NoDelete] Mysticism`
  - This prevents Wabbajack from deleting mods that you have added when you update the modlist
- You may also add this prefix to a mod whose configuration you may have changed, by altering an INI file for example
  - This will have the same effect as above, preventing Wabbajack from overwriting the mod (and your configuration) when you update the modlist

## To preserve your load order (if you've added a lot of mods):

- Click on the `Profile` dropdown and select `<Manage...>`
- Create a copy of the `Ro` profile
- Name it `[NoDelete] <your profile name>`
- Select the profile you just created and use that from now on
  - Note: using a `[NoDelete]` profile still requires you to add `[NoDelete]` to the name of every folder you've added or modifed
