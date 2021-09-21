# MSI-B250M-PRO-VDH-i5-7600K
 <p align="center">
  <img src="Docs/AboutThisMac.png" align=center">
 </p>
  <p align="center">
  <img src="Docs/AboutThisMac2.png" align=center">
 </p>
 <p align="center">
  <img src="Docs/PCI.png" align=center">
 </p>
 
 ## Specs
 | **Component** | **Model** |
| ------------- | --------- |
| CPU | i5-7600K |
| RAM | DDR4 16GB (4x4GB) 2400MHz |
| Audio Chipset | Realtek ALC887. Works with layout-id 1 |
| dGPU | GeForce GT 710. Works OOB |
| iGPU | Intel HD Graphics 630 |
| Lan |  Realtek 8111H Gigabit LAN controller |
| WiFi | Fenvi T919. Works OOB |
| OS Disk | 256GB Samsung 850 Pro SATA |
| macOS | Big Sur 11.6/OpenCore 0.7.3

## BIOS
| **Setting** | **Value** |
| ------------- | --------- |
| Above 4G memory | Enabled |
| Initial Graphics Adapter | PEG if dGPU or IGD if iGPU |
| Intergrated Graphics Share Memory | 128MB |
| Thunderbolt Support | Enabled |
| SATA Mode | AHCI Mode |
| Intel Serial I/O | Disabled |
| XHCI Hand-off | Enabled |
| Legacy USB Support | Auto |
| Serial (COM) Port0 | Disabled |
| Parallel(LTP) Port | Disabled |
| Windows 8.1/10 WHQL Support | Enabled |
| Windows 7 Installation | Disabled |
| MSI Fast Boot | Disabled |
| Fast Boot | Disabled |
| Intel VT-D Tech | Enabled |
| C1E Support | Enabled |
| CFG Lock | Disabled |

## USB config
All USB ports are working. I have made a custom USB-B250.kext that maps them. It should be used together with XhciPortLimit kernel quirk.
