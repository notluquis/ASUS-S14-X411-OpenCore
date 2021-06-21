# ASUS VIVOBOOK S14 X411UF HACKINTOSH with OPENCORE

## Specification
- Model : ASUS X411UF
- CPU : Intel Core i5-8250U
- RAM : 8 GB DDR4 2400Mhz. (1 free, 1 onboard)
- Audio Codec : Conexant CX8050 Layout-ID 13
- iGPU : Intel UHD 620
- dGPU : Nvidia MX130 (disabled)
- Ethernet Card: NO
- Wifi/BT Card: QCA9377, replaced with Fenvi BCM94360NG (bought on Aliexpress)
- Touchpad : ASUS Precision Touchpad ELAN1300
- BIOS revision: 308
- Storage : SSD WDC WDS 120GB + HDD TOSHIBA MQ04ABF100 1TB.

## What works
- Sleep/Wake (sometimes)
- Sound
- Wi-FI (with Fenvi card)
- Bluetooth (with poor range, 4.0 BT)
- HDMI
- USB A & C ports
- Touchpad with gestures (random freeze)
- Brightness
- Sidecar
- Airdrop
- Siri
- Battery Status
- Fn keys

## Not tested 
- Power Management

## Not working status
- dGPU : Nvidia MX130 (disabled)
- Default Wi-Fi card (QCA9377)
- Realtek Card Reader (works only once)

## Sources
-  Dortania's guide and everyone involve.
-  [hieplpvip](https://github.com/hieplpvip/Asus-Zenbook-Hackintosh) for initial EFI (0.6.4/5) and video memory problem. (PCI and framebuffer)
- cputscsync problem solved thanks to [anonymous-writer](https://github.com/acidanthera/bugtracker/issues/1676) and the respective forum.

**REMEMBER YOU NEED TO ADD YOUR OWN SERIAL NUMBER!**
