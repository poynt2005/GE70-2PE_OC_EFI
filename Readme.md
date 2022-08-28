# Hackintosh OpenCore EFI for MSI GE70-2PE Apache Pro

## *ONLY FOR OPENCORE 0.7.8*
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

## Bios Setting (Ver.E1759IMS.52D)  
1. Advanced -> SATA Mode Selection -> AHCI  
2. Advanced -> SuperCharger  works... -> Disabled  
3. Advanced -> Intel Virtualization Technology -> Enable    
4. Boot -> Fast Boot -> Disabled  
5. Boot -> Boot Mode Select -> UEFI With CSM  
6. Security -> If there is a secure boot, disable it  
7. Other Options -> Let 'em default  
8. After installing your OS and setting up the EFI partition (adding a new OpenCore partition using *[EasyUEFI](https://www.easyuefi.com/)*), go to Boot -> UEFI Hard Disk Drive BBS priorities -> Set OpenCore partition to Boot Option #1

## Known issues
1. Hibernate not working, may cause kernel panic.  
2. HDMI out not working, may cause kernel panic.  
3. Ethernet(killer E2200) not tested.   
4. [HeliPort App](https://github.com/OpenIntelWireless/HeliPort) is required to enable wireless Lan. 
