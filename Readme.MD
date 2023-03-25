<p align="center">
  <img src="https://user-images.githubusercontent.com/80191638/227436579-681b90ba-4cdb-4f13-8cb1-4f32e6fe07a4.png" />
</p>

# Important
## Edits needed before booting:
### SMBIOS:
- Generate SMBIOS using GenSMBIOS
- Put the values in their place following Dortania's guide
- Save using Ctrl/Cmd+S
### Kexts:
###### follow if your ethernet card is not RTL8100:
- Download the kext for your ethernet card
- Put it in the EFI/OC/Kexts folder
- Open EFI/OC/config.plist in ProperTree
- Press Cmd/Ctrl+R and select EFI/OC folder
- Save using Ctrl/Cmd+S
## Post-install
### To fix Graphics Acceleration:
- Launch OpenCore Legacy Patcher
- Run Post Install Patches(google to find solutions if there are any further requirements)
### To fix blur
- Go into Settings - Non-metal settings
- Turn on Beta Blur

# Tools used:
1. ProperTree. https://github.com/corpnewt/ProperTree 
2. GenSMBIOS. https://github.com/corpnewt/GenSMBIOS
3. Pike's ssdtPRGen.sh. Used for generating SSDT-PM (CPU Power Management SSDT)

# What works:
- Ethernet
- Accelerated Graphics(with GT 1030)
- macOS Monterey
- WiFi(kexts required)
- sleep/hibernate

# Credits:

Thanks for [Apple](https://www.apple.com/ "Apple") For MacOS<br/>
Thanks for [Acidantera](https://github.com/acidanthera "Acidantera") for OpenCore<br/>
Thanks for [Dortania](https://dortania.github.io/OpenCore-Install-Guide/ "Dortania") for the Guide<br/>
Thanks for [Mieze](https://github.com/Mieze "Mieze") for providing RTL8100 Driver<br/>
Thanks for [Sniki](https://github.com/Sniki "Sniki") and [RehabMan](https://github.com/RehabMan "RehabMan") for USBInjectAll.kext<br/>
