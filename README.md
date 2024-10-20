# ASUS-PRIME-H610M-A-i3-12100F-RX580-Hackintosh

## TEST MacOS Version: Montery 12.7.6 and Sequoia 15.0.1

### Hardware

| Component |        Variant         |
| :-------: | :--------------------: |
| Mainboard |  ASUS PRIME H610M-A DDR4
| Processor |  Intel Core i3 12100F |
| DDR4 RAM  |      Asgard DDR4 2133Hz 8GB*2      | 
| SSD  | Teclast SATA SSD 512GB        |
| Graphics  |  SAPPHRE NITRO+ RX 580 8G G5   |



#### Kexts

| Kext                                 | Version      | Author                                                                                                             |
Detail see files

---

### Update macOS

Check the official update-guide: [OpenCore-Post-Install/update](https://dortania.github.io/OpenCore-Post-Install/universal/update.html)

1. Backup
   - Full system backup with `Time Machine` or similar software
   - Copy current EFI to OpenCore USB-Drive for recovery purpose
2. Download
   - Latest version of OpenCore and replace files in EFI
   - Updates for all installed kexts and replace in EFI
3. Reboot
   - Boot with updated OpenCore version and kexts
   - If the system doesn't boot, use OpenCore USB-Drive to roll back
4. Update
   - Start macOS Update from `System Settings` -> `Software Update`
   - With OpenCore the update process should work automatically
   - If `Software Update` shows `Mac version is up to date`, download macOS Installer from AppStore and start the update manually

If the system doesn't boot, try to fix the problem or revert to the latest EFI or system-backup.


