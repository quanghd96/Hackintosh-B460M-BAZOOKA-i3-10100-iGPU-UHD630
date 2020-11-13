## MSI-B460M-BAZOOKA+i3-10100+iGPU-UHD630

### Hardware Configuration

| Configuration | model                           |
| ------------- | ------------------------------- |
| CPU           | I3-10100                        |
| Motherboard   | B460M Bazooka                   |
| RAM           | GSKILL 2666 8G\*2               |
| Graphics card | I3-10100 nuclear display UHD630 |

### CPU support

- [x] Supports all 10-generation CPUs with UHD630 cores
- [x] The 10th generation CPU of non-core display with F can also have the following independent display without drive (but cannot use nuclear display acceleration)

### Graphics card support

- [x] Support UHD630 graphics card with only CPU core display
- [x] Support AMD RX 470/480/570/570X/580/580X/590 series graphics cards
- [x] Support AMD RX 5500/5600/5700 series graphics cards (dedicated config.plist required)
  > PS: To use the independent display, you need to forcibly turn on the CPU core display in the BIOS (Advanced -> Built-in display configuration -> Integrated graphics multi-monitor (IGD Multi-monitor) -> Allow), otherwise the core display hardware decoding will fail and only use the core Obviously can be ignored

### BIOS settings

- USB device wake up from S3/S4/S5: Allow
- PS/2 mouse wake up from S3/S4/S5: Allow
- USB keyboard wake up from S3/S4/S5: any key
- Integrated graphics and multiple monitors: Allowed (otherwise the hardware decoding of the core display will fail, and those that only use the core display can be ignored)
- CFG lock: prohibited

### EFI

OpenCore: 0.6.3

macOS version: 10.15.7

EFI download link: [Download](https://github.com/quanghd96/Hackintosh-B460M-BAZOOKA-i3-10100-iGPU-UHD630/releases)

### Onboard network card settings

- System Preferences -> Network -> Ethernet (Advanced) -> Hardware -> Configuration: Manual, Speed: 100baseTX (1000baseT can be selected for Gigabit network environment), Duplex: Full Duplex, MTU: Standard 1500
