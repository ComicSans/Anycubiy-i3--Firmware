# ANYCUBIC PRUSA I3 XL

This repository adds custom configurations for the **Anycubic i3+** (also known as **Anycubic i3 XL** or **Anycubic i3 Ultrabase**) of the [Marlin Firmware](http://marlinfw.org/).

This printer is based on the Prusa i3 design and comes with a heat bed (the Anycubic Ultrabed) and an MK8 extruder.

Please note that the **Anycubic i3 Mega** needs a different firmware (see [here](https://github.com/ANYCUBIC-3D/I3-MEGA)).

You can find the original fork (based on Marlin 1.1.0-pre8) in the *ANYCUBIC_PRUSA_I3_XL* folder. This version came preinstalled on your printer.

Precompiled firmwares in hex format are in the corresponding sub folders. You could use the [OctoPrint FirmwareUpdater Plugin](https://github.com/OctoPrint/OctoPrint-FirmwareUpdater) to easily flash them. SSH on your Pi and run:

```bash
sudo apt-get update
sudo apt-get install avrdude
exit
```

Then use these settings:

<img src="avrdude-settings.png" />
