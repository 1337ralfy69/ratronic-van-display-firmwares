# Ratronic van display firmware

Encrypted firmware images for the Ratronic van display and its LIN sensor
module, installed by the Ratronic phone app. There is no source code here.

| tag | file | installs on |
|---|---|---|
| `display-v*` | `ratronic_van_display.enc` | Release displays (secure boot + flash encryption) |
| `module-v*` | `Van_sensor_module.enc` | sensor modules with bootloader v2 |

Both are encrypted and authenticated for the devices they are made for; a
device refuses any other image. They are of no use anywhere else.
