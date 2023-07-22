# Dell-Latitude-E7240-BigSur-OpenCore-with-IntelWiFi

This Repo includes an fully functional (except the HDMI out) OpenCore install for MacOS BigSur on a Dell Latitude E7240 with IntelWiFi Module.
Please use https://github.com/corpnewt/GenSMBIOS to generate a new System ID / SMBIOS / Serial in the plist to make your System unique!

Please make yourself familiar with OpenCore (https://github.com/acidanthera/OpenCorePkg).
I will not show how to get a working installer, that is not the scope of this repo.
If you have an working installer, you can use this repo (after you generated a new SMBIOS) to get a working Bootloader with all needed kext and drivers.
Please keep in mind that you will need a 200MB FAT32 Formated Partition.
After the Installation is done, drag and drop the EFI folder to that 200MB Partition and set it as default Bootoption in the Bios of the E7240.
