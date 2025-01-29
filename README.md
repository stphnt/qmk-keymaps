## QMK Configurator Keymaps

[QMK Configurator](https://config.qmk.fm) keymaps for my keyboards.

### Update procedure

1. Update the keymap
   1. Upload the `*.json` keymap to the QMK Configurator
   1. Modify as necessary
   1. Download new keymap JSON file.
1. Update keymap images (this is a _very_ hacky way to get the color and size I want)
   1. Click "Print Keymap" to print the keymap to PDF.
   1. Using a screen shot tool take a rectangular screenshot of each keyboard and save them as each `*.png` file.
1. Commit the changes and push.

### Flashing procedure

1. Download the firmware from the QMK Configurator by clicking "Firmware".
1. With the keyboard connected to the computer run the following command and follow the instructions on screen.

   ```
   qmk flash <downloaded-hex-file>
   ```

1. For a split keyboard, repeat the last step but connected directly to the other half.
