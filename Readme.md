# Reference

Using [Cascadia Code](https://github.com/microsoft/cascadia-code) as default font. For additional color schemes I recommend [terminal.sexy](https://terminal.sexy/).

## Software

Some profiles use the following software, however they are entirely optional and are commented out in `settings.json`.

| Software          |
| ----------------- |
| WSL               |
| Powershell 7      |
| ShareGate Desktop |

## Modules

The profiles have been tested using the following versions:

| Version            | Name                                                                                                                        |
| -----------------: |:----------------------------------------------------------------------------------------------------------------------------|
| `2.0.2.129`        | [AzureADPreview](https://www.powershellgallery.com/packages/AzureADPreview)                                                 |
| `2.0.4`            | [ExchangeOnlineManagement](https://www.powershellgallery.com/packages/ExchangeOnlineManagement)                             |
| `0.11.0`           | [ExchangePowerShell](https://www.powershellgallery.com/packages/ExchangePowerShell)                                         |
| `16.0.20912.12000` | [Microsoft.Online.SharePoint.PowerShell](https://www.powershellgallery.com/packages/Microsoft.Online.SharePoint.PowerShell) |
| `2.0.0`            | [MicrosoftTeams](https://www.powershellgallery.com/packages/MicrosoftTeams)                                                 |
| `1.1.183.57`       | [MSOnline](https://www.powershellgallery.com/packages/MSOnline)                                                             |
| `2.2.1`            | [PowerShellGet](https://www.powershellgallery.com/packages/PowerShellGet)

## Notable profiles

### Windows Terminal (⚡)

Starts new Windows Terminal Preview window in elevated mode.

### Update Modules

Runs `Update-Module` from [PowerShellGet](https://www.powershellgallery.com/packages/PowerShellGet) for each installed module.