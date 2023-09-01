# Lenovo-M710q-QNCT-DW1560-Hackintosh
EFI for Lenovo-M710q-QNCT-DW1560 with OpenCore 0.9.4 bootloader  
Test for macOS bisgur and macOS 14 beta

### Computer Spec:

| Component        | Specifications                         |
| ---------------- | ---------------------------------------|
| CPU              | Intel® Xeon® E5-2680 v4                |
| iGPU             | Dual AMD Radeon RX Rx580 8GB.          |
| RAM              | 2 * 16GB DDR4 2666Mhz ecc              |
| NVMe             | Kioxia RC10 512GB / WD SN520 512GB     |
| LAN              | Realtek RTL8168G/8111G                 |
| Audio            | Realtek ALC294                         |
| WiFi & Bluetooth | Combo USB TLINK                        |
| SMBIOS           | ImacPro 1,1                            |
| BootLoader       | OpenCore 0.9.4                         |

### What works:

- [x] Dual Rx580 8GB
- [x] ALC294 Internal Speakers
- [x] ALC294 & DP Audio Output
- [x] ALC294 Audio Input
- [x] All USB Ports
- [x] Realtek RTL8168G/8111G 
- [x] Broadcom Wi-Fi & Bluetooth
- [x] NVRAM

### BIOS Settings:

* Update BIOS to M1AKT50A  
* Disable:  
CSM   
* Boot this OpenCore
* Press the space bar
* Choose "SetupVar"
* Run code to set 64M DVMT:
```
setup_var 0x7AC 0x2   
```
* Reboot to install macOS



## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://github.com/dortania) for great and detailed guides.
