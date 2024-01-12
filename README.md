# EFI for Intel Core I7 10700F + MSI B560M-A PRO
## Latest with macOS Sonoma 14.2.1
## OpenCore 0.9.7
### Setup Configuration:
- Intel Core I7 10700F Comet Lake
- MSI B560M-A PRO
    - Audio Codec: ALC897 (layout-id 66)
    - Ethernet Card: Realtek RTL 8125
    - PCI-e 1x Wifi + Bluetooth 4.2 Intel AC 7265
    - SSD SATA SANDISK 1TB
- GPU Radeon RX580 2048SP 8GB (Bios Mod to RX570)
### Works Fine
- Sleep
- Wi-fi 2.4G and 5G Networks
- Bluetooth 4.2
- All USB Ports
- Rear P2 Jacks Audio Realtek
- Front P2 Jack Stereo
- Icloud Account
- Virtualization

### Don't Works
- Front P2 Mic Jack
- Airdrop

#### Sources used to build the EFI
https://dortania.github.io/OpenCore-Install-Guide/
https://github.com/acidanthera
https://github.com/OpenIntelWireless
https://github.com/USBToolBox
https://github.com/johnlimabravo/XHCI-unsupported/releases
https://github.com/aluveitie/RadeonSensor
