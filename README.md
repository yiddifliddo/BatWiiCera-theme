# BatWiiCera (distribution copy)

Version 0.1.24 of the BatWiiCera theme for Batocera, laid out for the Themes
Downloader: theme.xml is at the root of this repository.

## Installed from Batocera's Themes Downloader?

The downloader installs the theme only, into `/userdata/themes/BatWiiCera-theme`.
Select it under *Main Menu > UI Settings > Theme set*.

To add the **Plaza** channel (the online stadium that comes with the theme),
copy one file from the installed theme to the Ports folder, over the network
share:

    \\BATOCERA\share\themes\BatWiiCera-theme\_plaza\installer\Plaza.sh
    ->  \\BATOCERA\share\roms\ports\Plaza.sh

Then open **Ports** in EmulationStation and start **Plaza** once. It installs
the channel from the theme folder and restarts EmulationStation by itself.
Nothing to type: the public server is built in. x86_64 PCs only for now.

## Everything else

Source, version history, the single-zip installer (theme and Plaza together),
change control and the Plaza documentation live in
https://github.com/yiddifliddo/BatWiiCera (folder v0.1.24).

Author: yiddifliddo. Licence: CC BY-NC-SA 4.0 (see LICENSE); the Plaza is MIT.
