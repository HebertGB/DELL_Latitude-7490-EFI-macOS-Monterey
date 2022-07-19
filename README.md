# Laptop Dell Latitude 7490 Hackintosh EFI | 8th Kaby Lake
# OpenCore 0.8.2
# macOS 12.4 Monterey
# Author: Hebert G. Barbosa

## System configuration
- Intel 8th gen Kaby Lake R quad-core i7-8650U 1.9GHz CPU
- 16Gb DDR4-2400 RAM
- Intel UHD 620 Graphics
- M.2 2280 512GB SATA SSD (in Key M slot)
- Dell DW1820A M.2 802.11ac combo wireless card (PCI ven id 0x14e4, dev id 0x43a3) + Bluetooth 4.1 (PCI ven id 0x0a5c, dev id 0x6412) 
- Intel i219-LM Gigabit Ethernet (PCI ven id 0x8086, dev id 0x15d7)
- integrated Realtek HD webcam (USB internal, PCI ven id 0x0bda, dev id 0x5650)
- integrated Realtek RTS525A microSD 4.0 card reader (PCI ven id 0x10ec, dev id 0x525a): RaltekCardReader.kext, RealtekCardReaderFriend.kext
- Alps I2C HID Multi-Touch Touchpad (PCI ven id 0x1028, dev id 0x081c): AlpsHID.kext - including tap-to-click and multi-finger gestures
- Alps I2C HID TrackPoint (PCI ven id 0x044e: dev id 0x1212)

## DockStation Dell WD15
- HDMI, mini-DP and VGA outputs - just one monitor: all 3 outputs (HDMI, DP, VGA) register under same CONx
- all USB ports 2.0 and 3.0: OK
- sound: OK (Front headset jack) / Rear line-out jack not work
- GigEthernet RJ45 port (Realtek RTL8153 USB3-to-Ethernet converter, 0x0bda:0x8153): AppleRTL815XEthernet110.kext


```
Plataforma: Laptop DELL 7490 | 8th Kaby Lake
Processador: Intel i7-8650U Kaby Lake R quad-core
Ram: 16Gb DDR4-2400
Video: iGPU UHD620 
SSD NVME: M.2 2280 512GB SATA SSD
Audio: Realtek ALC256 High Def audio
Combo WiFi + Bluetooth: Dell DW1820A M.2 802.11ac combo wireless card
LAN: Intel i219-LM Gigabit Ethernet
SMBIOS: macbook14,2
macOS: Monterey 12.4
Opencore: 0.8.2
Dual-Boot Linux Mint 20.3 / macOS 12.4
integrated Realtek HD webcam
integrated Realtek RTS525A microSD 4.0 card reader
Alps I2C HID Multi-Touch Touchpad
Alps I2C HID TrackPoint
SmartCard Reader
DisplayPort on USB Type-c
DockStation DELL WD15
Monitor principal: LG Ultra Wide 29" 2560x1080
Monitor secundário: LG 20" 1600x900
Teclado e Mouse: Logitech K540
```