# hardware-software-notes
Notes for Computer Hardware and Softwares

# System Unit Main Parts
## Power Supply
## CD - ROM
SDRAM: Synchronous Dynamic Random Access Memory  
 - SDRAM can only read/write one time per clock cycle  
DDR: Double Data Rate  
 - transfer data twice per clock cycle, enhancing the speed and efficiency of your system  
 - DDR transfers data to the processor on both the downbeat and upbeat of the clock signal, so twice per cycle.  


| Specification   | DRAM     | DDR      | DDR2     | DDR3      | DDR4       | DDR5        |
|-----------------|----------|----------|----------|-----------|------------|-------------|
| **Prefetch**    | 1-bit    | 2-bit    | 4-bit    | 8-bit     | Bit per Bank | 16-bit     |
| **Data Rate**   | 100-166  | 266-400  | 533-800  | 1066-1600 | 2133-5100  | 3200-8000+  |
| **Transfer Rate** | 0.8-1.3 | 2.1-3.2 | 4.2-6.4 | 8.5-14.9  | 17-25.6    | 38.4-51.2   |
| **Voltage**     | 3.3      | 2.5-2.6  | 1.8      | 1.35-1.5  | 1.2        | 1.1         |
## Graphics Card (Optional)
### Ray Tracing: Mimic real-world light bbehavior, creating life like visuals
### Variable Rate Shading: Optimizes rendering resources
### Tensor Cores: Accelerate matrix computations.
## Storage Devices (HDD/ SSD/ NMVe)
## CPU
## CPU Fan
## Cooling Fans (Optional)
## Motherboard
## Case

# System Unit Peripherals
## SATA
## Monitor Cable (HDMI/ VGA)

# Default Boot Priotity
1. HDD, SSD, or NVMe
2. CD - ROM
3. External Devices

# Partition Style
## MBR  (Master Boot Record): Partion style for older versions if Windows, Linux, and MacOS [Legacy BIOS]
## GPT (GUID Partition Table): Newer partition style or updated version of MBR [EUFI]

# Firmware System
## UEFI (Unified Extensible Firmware Interface): Is replacement for traditional BIOS having improved boot speed, graphical interface(With mouse support), secure boot(Prevents unwanted programs to boot during startup for security), UEFI shell (Execute advanced commands directly in firmware interface), and backwards compatability with traditional BIOS.

## Legacy BIOS (Basic Input/Output System): Software embedded in motherboard that initialized for hardware components and operating system to communicate.

# File Systems
## FAT32 (File Allocation Table): Is older version of file system introduced in 1996 has maximum file size limit of 4GB and Maximum capacity of 2TB and has low security features. Default file system for Windows 7 and lower.

## exFAT (Extended File Allocation Table): Is just an improved version of FAT32 but on steriods. Has maximum file size of 16 exabytes and maximum capacity of 128 petabytes. Primarily designed to be compatible with multiple operating system like Windows, Linux, and MacOS and other various consumers such as USB Flash drive, SD Card, and Removable Storage. Default file system for USB Flash drives.

## NTFS (New Technology File System): Is more advanced file system and has improved performace comapred to FAT32. Supports upto 16TB file size and maximum capacity of 256TB and also has more advance security features. Default file system for Windows 10 and higher.

# Storages Devices
## HDD (Hard Disk Drive): Slower than the other two storage devices because of its moving parts to read/ write data. But longer life span than the other two.

## SSD (Solid State Drive): Faster than HDD because it has no moving parts that connects using SATA. But shorter life span than HDD.

## NVMe (Non-Volatile Memory Express): A subtype of SSD that connects to PCIe unlike traditional SSD that connects to SATA improving its read/ write because attached directly to motherboard unlike SATA that has wire. Commonly used for workstations, servers, and gaming pc's.

# Storage Devices Connectors
## PCIe (Peripheral Component Interface Express): Commonly used to connect NVMe, Graphics Card, Network card, amd Sound card to motherboard.

## SATA (Serial Advanced Technology Attachment): Commonly used to connect SSD and HDD to motherboard.

# Monitor Cable Connectors
## VGA (Video Graphics Array)
## HDMI (High-Definition Multimedia Array)

# Cracker Notes
...


# Definition of Terms 
WinPE - Windows Pre Installation
