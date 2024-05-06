
## Powershell as an Open World Text Adventure

About OWTA's:

https://github.com/roguebro/roguebro/blob/main/owta.md

## Setup

Recent version of Windows contain Powershell 5.1+ by default. Type one of the following in the Windows-menu:

- `powershell`
- `terminal`

A different variant (Powershell **Core**) can be installed on macOS and many Linux-distro's: https://github.com/PowerShell/PowerShell. You can even install it side-by-side on Windows and arguably it provides a cleaner and nicer sandbox than default 5.1. If you're on Windows, why not try both? Once installed it can usually be started with `pwsh`.

> On Windows, don't confuse a PowerShell-prompt with good old Windows-`cmd` which is an evolution of old-school DOS.

> You might like to explore https://github.com/microsoft/terminal. Windows 11 has it by default. On Win10/11 also check the Microsoft Store.

Check your PowerShell-version:

    Write-Output $PSVersionTable

## Start Exploring

Some suggestions:

    Get-Help
    Get-Command
    Get-Module
    Get-Module -ListAvailable
    Get-Alias

For full immersion, consider downloading the help-documents locally (you might need an Administrator-terminal): 

    Get-Help Update-Help -Online

Have fun!

