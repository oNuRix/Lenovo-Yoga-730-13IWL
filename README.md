# Lenovo Yoga 730-13iwl Opencore 
<img width="579" alt="macos" src="https://user-images.githubusercontent.com/40405226/187765495-da8a41a5-531f-4c6d-a06a-61c9cdbfbf46.png">
![image](https://user-images.githubusercontent.com/40405226/197857582-3911dda2-0be8-4d26-bcaa-b6c05cc9dcae.png)


## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Lenovo Yoga 730-13iwl       |
| Processor           | Intel Core i5-8265U Products formerly 'Whiskey Lake'    |
| Memory              | 8GB 2400MMHz soldered |
| NVME                | M.2 Nvme SK Hynix HFS256GD9TNG-62A0A |
| Integrated Graphics | Intel HD Graphics 620                     |
| Monitor             | FHD 1920x1080 touchscreen (13.3 inch) |
| Sound Card          | Realtek ALC236           |
| Wireless Card       | Intel AX200NGW |


## Current Status

- **Fingerprint sensor is not working (never will work)**
- Everything else works well except Airdrop, right mouse click
- Screen rotation work on 90°(only 1080x1920) and 180°(only 1920x1080)
- CFGLock can be disable in advances Bios settings (your own risk!)
- Touchscreen (TPD1) can be disable for better battery in advances Bios settings
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values

## Misc after install:
- [Enable HiDPI](https://github.com/xzhih/one-key-hidpi) :
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
```

## Disable in Bios

- Disable Security -> Intel SGX -> Intel SGX Controller
- Disable Security -> Secure Boot
- Switch RAID to AHCI in Configuration -> SATA Controller Mode

## Advances Bios 
- F2 Boot in bios and power off
- Press one after one
- F1, 1, Q, A, Y
- F2, 2, W, S, X
- F3, 3, E, D, C
- F4, 4, R, F, V
- F5, 5, T, G, B
- F6, 6, Z, H, N
- Power on 
- F2 Boot in Bios, Can see advances section now.
- **depends your's keybord input** (Simply F1 too bottom)


**Thanks @dragonflylee and @OstapStad for their efi**
