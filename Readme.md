# Hackintosh OpenCore EFI for MSI GE70-2PE Apache Pro

## *ONLY TESTED ON MACOS CATALINA(10.15.4)*

## Specification/Ports
| Hardware | Available |
| ------ | ------ |
| CPU: I7-4700HQ | Yes |
| GPU(builtin): Intel® HD Graphics 4600 | Yes |
| GPU: Nvidia GeForce GTX860M | No |
| HDD: HGST HTS721010A9E630 | Yes |
| Lan: Atheros Killer E2200 | (Not Tested) |
| Wireless Lan: Intel Dual Band WirelessAC 3160 | Yes |
| Bluetooth: Intel Dual Band WirelessAC 3160 | Yes |
| TouchPad: Synaptics Touchpad | Yes |
| Sound Card: Realtek ALC892 | Yes |
| Card Reader: REALTEK RTS5249 Card Reader | No |
| USB: 2.0x2 + 3.0x2 | Yes |
| Webcam: 1x | No |
| Disk Drive: BD Combo / DVD Super Multi | (Not Tested) |

## Bios Setting
1. Turn off secure boot
2. Set 

## Known issues
1. Hibernate not working, may cause kernel panic.  
2. HDMI out not working, may cause kernel panic.  
3. Ethernet(killer E2200) not tested.   
4. [HeliPort App](https://github.com/OpenIntelWireless/HeliPort) is required to enable wireless Lan. 