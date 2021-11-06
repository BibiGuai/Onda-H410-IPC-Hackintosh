# Onda-H410-IPC-Hackintosh
Onda H410 IPC Hackintosh Bios&ACPI(SSDT)&USBMap  
昂达 H40 IPC 黑苹果 Bios、ACPI和USBMap  

**Bios**  
Already setup:  
已设置：  
Fast Boot -> Disable  
Secure Boot -> Disable(After install can be Enabled)  
COM Port -> Disable  
VT-d -> Disable  
CSM -> Disable  
Intel SGX -> Disable  
CFG Lock -> Disable  
VT-x -> Enable  
Above 4G decoding -> Enable  
Hyper-Threading -> Enable  
XHCI Hand-Off -> Enable  
DVMT Pre-Allocated -> 64MB  
SATA Mode -> AHCI  
  
Setup manually:  
需手动设置：  
Parallel Port -> Disable ---- Bios > Advanced > SIOConfiguration  
  
**ACPI**  
SSDT-AWAC  
SSDT-EC-USBX  
SSDT-PLUG  
SSDT-RHUB  
SSDT-SBUS-MCHC  
  
**USBMap**  
All USB port (with a bluetooth USB)  
所有USB口，包括蓝牙内建USB  
PS: For this motherboard USBMap is unnecessary  
对于该主板USB地图非必需配置  
