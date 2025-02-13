# EFI for Intel Core I7 10700F + MSI B560M-A PRO
## Latest with macOS Sonoma 14.7.2
## OpenCore 1.0.3
### Setup Configuration:
- Intel Core I7 10700F Comet Lake
- MSI B560M-A PRO
    - Audio Codec: ALC897
        - PciRoot(0x0)/Pci(0x1f,0x3) (Dictionary)
            - layout-id (number) "23"
    - Ethernet Card: Realtek RTL 8125
    - PCI-e 1x Wifi + Bluetooth 4.2 Intel AC 7265
    - SSD SATA OR NVME
- GPU Radeon RX560 4GB

### Works Fine
- Sleep
- All USB Ports
- Rear P2 Jacks Audio Realtek
- Front P2 Jack Stereo
- Icloud Account
- Virtualization

### Don't Works
- Front P2 Mic Jack

#### Sources used to build the EFI
- https://dortania.github.io/OpenCore-Install-Guide/
- https://github.com/acidanthera
- https://github.com/OpenIntelWireless
- https://github.com/USBToolBox
- https://github.com/johnlimabravo/XHCI-unsupported/releases
- https://github.com/aluveitie/RadeonSensor
