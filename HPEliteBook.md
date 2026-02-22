# Hardware Specifications - HP EliteBook 8470p

## System Information
- **Model**: HP EliteBook 8470p (A1G60AV)
- **Architecture**: x86_64
- **BIOS**: 64KiB

## Processor (CPU)
- **Model**: Intel(R) Core(TM) i5-3320M CPU @ 2.60GHz
- **Cores**: 2 cores, 4 threads (2 threads per core)
- **Socket**: 1
- **Base Frequency**: 2.60GHz
- **Max Frequency**: 3.30GHz
- **Cache**: 
  - L1: 64KiB (32KiB instruction + 32KiB data per core)
  - L2: 256KiB per core
  - L3: 3MiB shared
- **Virtualization**: VT-x supported

## Memory (RAM)
- **Total**: 12GiB System Memory
- **Configuration**:
  - 8GiB SODIMM DDR3 Synchronous 1600 MHz
  - 4GiB SODIMM DDR3 Synchronous 1600 MHz
- **Current Usage**: 4.4GiB used / 7.2GiB available
- **Swap**: 13GiB

## Storage
- **Primary Drive**: 500GB WDC WD5000LPVX-8
- **Partitions**:
  - /dev/sda1: 511MiB Windows FAT volume (boot/efi)
  - /dev/sda2: 465GiB EXT4 volume (root) - 32GB used / 403GB available
- **Optical Drive**: CDDVDW SN-208DB

## Graphics
- **Integrated GPU**: Intel HD Graphics 4000 (3rd Gen Core processor Graphics Controller)
- **Framebuffer**: /dev/fb0

## Network
- **Ethernet**: Intel 82579LM Gigabit Network Connection (enp0s25)
- **Wireless**: Intel Centrino Advanced-N 6205 [Taylor Peak] (wlo1)

## Audio
- **Controller**: Intel 7 Series/C216 Chipset Family High Definition Audio Controller
- **Devices**: HDA Intel PCH with multiple audio inputs/outputs

## USB Controllers
- **USB 3.0**: Intel 7 Series/C210 Series Chipset Family USB xHCI Host Controller
- **USB 2.0**: Intel 7 Series/C216 Chipset Family USB Enhanced Host Controller

## Input Devices
- **Keyboard**: AT Translated Set 2 keyboard
- **TouchPad**: SynPS/2 Synaptics TouchPad
- **Webcam**: HP HD Webcam [Fixed]
- **Other inputs**: Wireless hotkeys, accelerometer, HP WMI hotkeys

## Additional Features
- **Card Reader**: SD/MMC Host Controller
- **FireWire**: IEEE 1394 Host Controller
- **Bluetooth**: BCM20702A0
- **Security**: Intel MEI Controller, TPM-like functionality

## Power Management
- **Battery**: CC06055XL
- **Power buttons**: Sleep Button, Power Button
- **Lid Switch**: Present

## System Status
- **Kernel**: Linux (current running)
- **Memory Usage**: ~39% used
- **Disk Usage**: ~7% used on root partition
- **Temperature**: Not monitored in this report

## Driver Status
- **Graphics**: Intel i915 driver (active)
- **Audio**: snd_hda_intel with IDT codec (active)
- **Ethernet**: e1000e driver (active)
- **Wireless**: iwlwifi driver (active)
- **USB**: xhci_hcd (USB 3.0) and ehci-pci (USB 2.0) drivers (active)
- **Bluetooth**: btusb with Intel/Broadcom modules (active)
- **Card Reader**: sdhci-pci driver (active)
- **FireWire**: firewire_ohci driver (active)
- **SATA/Storage**: ata_piix driver (active)
- **Management Engine**: mei_me driver (active)
- **PCI Express**: pcieport driver (active)

## Security Vulnerabilities
- **Mitigations Active**: Most speculative execution vulnerabilities are mitigated
- **Status**: Generally well-protected with current microcode

*Report generated on: $(date)*
*System: HP EliteBook 8470p*
