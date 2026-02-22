# Spesifikasi Lengkap Laptop Acer Aspire 4739

## Informasi Sistem
- **Manufacturer:** Acer
- **Product Name:** Aspire 4739
- **Version:** V1.05
- **Serial Number:** NXRP0SV002206225547600
- **UUID:** 76f435be-9a40-3e4a-aad3-047d7b4e6aa0
- **SKU Number:** Calpella_CRB
- **Family:** Intel_Mobile

## Motherboard
- **Manufacturer:** Acer
- **Product Name:** HMA_CP
- **Version:** Base Board Version
- **Serial Number:** 204FCECMBQC00777
- **Type:** Motherboard

## Processor (CPU)
- **Model:** Intel(R) Core(TM) i3 CPU M 380 @ 2.53GHz
- **Family:** Core 2 Duo
- **Socket:** ZIF Socket
- **Core Count:** 2
- **Thread Count:** 4
- **Base Clock:** 1066 MHz
- **Current Speed:** 2539 MHz
- **Max Speed:** 2533 MHz
- **Architecture:** 64-bit capable
- **L1 Cache:** 32KB
- **L2 Cache:** 256KB
- **L3 Cache:** 3MB

## Memory (RAM)
- **Total RAM:** 4GiB (3.5GB usable)
- **Tipe:** DDR3 Synchronous 1067 MHz (0.9 ns)
- **Form Factor:** SODIMM (laptop memory)
- **Voltase:** 1.5V
- **Slot Configuration:** 4 slot (2 terisi, 2 kosong)
- **Slot Terisi:**
  - Slot DIMM0: NT2GC64B88B0NS-CG, 2GiB, SODIMM
  - Slot DIMM1: ACR16D3LS1NGG/2G, 2GiB, SODIMM
- **Maksimum Total:** 16GB (4x4GB)

## Graphics (GPU)
- **Model:** Intel Corporation Core Processor Integrated Graphics Controller
- **Type:** Integrated Graphics
- **Revision:** rev 18
- **Driver:** i915 (Intel Graphics Driver)
- **Kernel Module:** i915
- **Status:** ✅ Active (Framebuffer: i915drmfb)
- **Firmware:** Multiple firmware files supported
- **Features:** DRM/KMS, 3D acceleration

## Audio
- **Model:** Intel Corporation 5 Series/3400 Series Chipset High Definition Audio
- **Type:** Integrated Audio
- **Revision:** rev 05
- **Driver:** snd_hda_intel (Intel HDA Driver)
- **Kernel Module:** snd_hda_intel
- **Codec:** Realtek (detected via snd_hda_codec_realtek)
- **Status:** ✅ Active
- **Features:** HD Audio, HDMI audio passthrough

## Network
- **Ethernet:** Qualcomm Atheros AR8152 v2.0 Fast Ethernet (rev c1)
  - **Driver:** atl1c (Atheros L1C Driver)
  - **Kernel Module:** atl1c
  - **Interface:** enp1s0
  - **Status:** ✅ Active
  - **Speed:** Fast Ethernet (100Mbps)
  
- **Wireless:** Qualcomm Atheros AR9485 Wireless Network Adapter (rev 01)
  - **Driver:** ath9k (Atheros 802.11n Driver)
  - **Kernel Module:** ath9k
  - **Interface:** wlp2s0
  - **Status:** ✅ Active
  - **Standard:** 802.11n WiFi

## USB Devices
- **WebCam:** Chicony Electronics Co., Ltd WebCam (ID: 04f2:b209)
  - **Driver:** uvcvideo (USB Video Class Driver)
  - **Interface:** Video (Class UVC)
  - **Status:** ✅ Active
  - **Features:** USB Video Class compliant
  
- **Mouse:** Xenta 2.4Ghz wireless optical mouse receiver (ID: 1d57:130f)
  - **Driver:** usbhid (USB HID Driver)
  - **Interface:** Human Interface Device
  - **Status:** ✅ Active
  - **Type:** Wireless optical mouse

## Battery
- **Vendor:** SANYO
- **Model:** AS10D31
- **Serial:** 8AA9
- **Type:** Lithium-ion
- **Capacity:** 39.93% (degraded)
- **Design Capacity:** 48.84 Wh
- **Full Capacity:** 19.50 Wh
- **Current Charge:** 62%
- **Voltage:** 11.143 V
- **Technology:** Rechargeable

## Chassis
- **Type:** Notebook
- **Manufacturer:** Chassis Manufacturer
- **Lock:** Not Present
- **Power Cords:** 1

## SSD Utama (System)
- **Model:** RX7 2.5 120GB
- **Type:** SSD (Solid State Drive)
- **Kapasitas:** 120GB (111.8GB usable)
- **Serial Number:** AA000000000000003437
- **Version:** A25E
- **Interface:** SATA
- **Form Factor:** 2.5 inch
- **Driver:** ahci (SATA AHCI Driver)
- **Device:** /dev/sda
- **Status:** ✅ Active
- **Mount:** / (root filesystem)

## HDD Sekunder (Data)
- **Model:** ST500LT012-1DG142
- **Type:** HDD (Hard Disk Drive)
- **Manufacturer:** Seagate
- **Kapasitas:** 500GB (465.8GB usable)
- **Serial Number:** W3PDWG8Z
- **Version:** SDM1
- **Interface:** SATA
- **Form Factor:** 2.5 inch
- **Driver:** ahci (SATA AHCI Driver)
- **Device:** /dev/sdb
- **Status:** ✅ Active
- **Mount:** /media/petrick/DATA

## Konfigurasi Storage
- **Total Storage:** 620GB
- **SSD untuk OS dan aplikasi**
- **HDD untuk data dan file besar**
- **Dual storage configuration optimal untuk performance dan kapasitas**

## BIOS
- **Vendor:** INSYDE
- **Version:** V1.05
- **Release Date:** 05/30/2011
- **ROM Size:** 1MiB
- **Capacity:** 2MiB

## Operating System
- **OS:** Linux (berdasarkan command yang dijalankan)
- **Desktop Environment:** XFCE
- **Kernel:** Linux

## Ringkasan Performa
- **CPU:** Entry-level (i3 first gen)
- **RAM:** Minimal untuk modern computing (upgrade recommended)
- **Storage:** Hybrid (SSD+HDD) - good configuration
- **Graphics:** Integrated - basic tasks only
- **Age:** ~2011 (legacy hardware)
- **Upgrade Priority:** RAM > Battery > Storage

## Driver Status Summary
- **Graphics:** ✅ i915 - Intel GPU driver active
- **Audio:** ✅ snd_hda_intel - Intel HDA driver with Realtek codec
- **Ethernet:** ✅ atl1c - Atheros L1C driver active
- **WiFi:** ✅ ath9k - Atheros 802.11n driver active
- **Storage:** ✅ ahci - SATA AHCI driver for both SSD/HDD
- **USB:** ✅ uvcvideo (WebCam), usbhid (Mouse) - standard drivers
- **System:** ✅ mei_me - Intel Management Engine driver active

## System Components Driver Info
- **Chipset:** Intel 5 Series/3400 Series Chipset
- **USB Controller:** Intel USB2 Enhanced Host Controller (ehci-pci)
- **PCI Bridge:** Intel PCI Express Root Port (pcieport)
- **Thermal:** Intel Thermal Subsystem (intel_ips)
- **Management:** Intel HECI Controller (mei_me)
