# Hackintosh-STRIX-G-G531GV
OC folder for Hackintosh ROG Strix G G531GV with OpenCore

## ROG Strix G G531GV Specification:
| Hardware | Specification |
| - | - |
| CPU | Intel i7-9750H |
| iGPU | Intel UHD Graphics 630 |
| dGPU | Nvidia RTX 2060 6GB |
| Wifi | Intel(R) Wireless-AC 9560 |
| Bluethooth | Intel(R) Wireless Bluetooth(R) |
| Sound | Realtek ALC294 |
| Touchpad | ELAN1203 |

## macOS version
Big Sur

## What's working?
* iGPU
* Wifi
* Bluetooth
* Sound (need to disable bootup sound)
* Touchpad (polling mode)
* Brightness control
* 120Hz screen
* Keyboard led control (using [OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB))
* Some fn combination keys (mute, volume control, playback control)

## What isn't working?
* dGPU
* CAPS LOCK led
* Remaining fn combination keys

## TODO
* Create SDDT patch to use touchpad in GPIO mode
