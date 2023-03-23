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
