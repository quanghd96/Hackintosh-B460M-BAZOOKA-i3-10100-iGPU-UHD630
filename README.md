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

### BIOS settings

- USB device wake up from S3/S4/S5: Allow
- PS/2 mouse wake up from S3/S4/S5: Allow
- USB keyboard wake up from S3/S4/S5: any key
- Integrated graphics and multiple monitors: Allowed (otherwise the hardware decoding of the core display will fail, and those that only use the core display can be ignored)
- CFG lock: prohibited

### EFI

OpenCore: 0.8.1

macOS version: 12.5

EFI download link: [Download](https://github.com/quanghd96/Hackintosh-B460M-BAZOOKA-i3-10100-iGPU-UHD630/releases)

### Onboard network card settings

- System Preferences -> Network -> Ethernet (Advanced) -> Hardware -> Configuration: Manual, Speed: 100baseTX (1000baseT can be selected for Gigabit network environment), Duplex: Full Duplex, MTU: Standard 1500

### Donating 💸

Feel free to [Buy Me a Coffee](https://www.buymeacoffee.com/quanghd96) or ![1KqjVujJduNRNWxZAAvr61fRg945WPuGhF](https://raw.githubusercontent.com/appleserial/NUC8I5BEH/master/misc/BTC.png) `1KqjVujJduNRNWxZAAvr61fRg945WPuGhF`
