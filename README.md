# 🔧 OpenCore EFI for Gigabyte Z790 GAMING X AX
👉 This repository contains OpenCore EFI configuration files for the Gigabyte Z790 GAMING X AX motherboard, designed to run macOS Ventura 13.3.1 on an Intel® Core™ i7-13700KF CPU and an ASUS Radeon™ RX 5700 XT ROG Strix Gaming OC 8GB GPU. Note that a Fenvi T919 wireless card is required for AirDrop and Handoff.

## ⚠️ Attention
You need to generate your own iMacPro1,1 SMBIOS using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).

## 🔧 Recommended BIOS Settings
#### 🚫 Disable
- Fast Boot
- Secure Boot
- VT-d
- Compatibility Support Module (CSM)
- Intel Platform Trust
- CFG Lock (MSR 0xE2 write protection)
- Above 4G Decoding
- Resizable BAR
#### ✅ Enable
- VT-x
- Hyper-Threading
- EHCI/XHCI Hand-off
- OS type: Other OS
