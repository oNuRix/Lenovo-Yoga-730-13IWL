# Lenovo Yoga 730-13iwl Opencore 
 <img width="585" alt="macos" src="https://user-images.githubusercontent.com/40405226/184422323-52c6ba98-5c69-4425-a0e6-598551caa8a0.png">
 
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

- **Physical keyboard won't work in OpencorePicker, I don't know why. Usb keyboard work**
- **Fingerprint sensor** is not working (never will work)**
- Everything else works well
- Screen rotation work on 90° and 180°
- CFGLock can be disable in advances Bios settings (better not!)
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

**Thanks @dragonflylee and @OstapStad for their efi**
