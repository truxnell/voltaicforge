---
title: "Finishing up the install"
image: steam_bigpicutre_retrogaming.png
weight: 5
---

### Setup for steam controller.

If you have a steam controller, you may need to setup a custom profile for the emulator. Then, when you enter each game for the first time you will need to set the profile, else steam will send the wrong button commands and you will get... undesired results.

Alternatively, just use a Xbox controller for emulator games. It is much more plug and play for emulation on the Steam Link/Big Picture.

### Finished

Sit back on the couch, grab a controller and your favourite beverage, and enjoy.

Many emulators are fine for multiple controllers if the game supported it, so get your friends over for a game!

### Troubleshooting

**Q. My game is missing from the Steam list!**

A. Check the Ice command line window for information. Does the game show up on its list as being added? Has the console and emulator show up as detected? If not, check your setup for whichever is missing. Ensure the extension in the `console.txt` is correct.

**Q. My game is missing cover art**

A. Download and set your own custom art manually. It's worth the effort!.

**Q. The link does nothing in Steam**

A. Check in steam if the link is working by inspecting the build shortcut link in steam. Find the game, and check the link in `Right click -> Properties -> Target`. You should be able to copy this into a command line and execute it with a working ROM. If it doesn't work, check all the paths are correct, and if not correct them in your config files.
[Steam Controller]: {{< relref "/post/2016/2016-09-18-steam-controller-worthy-addition" >}}
