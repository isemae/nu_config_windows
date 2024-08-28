# nu_config_windows
nah is only for windows

```
winget install nushell

git clone https://github.com/isemae/nu_config_windows.git

New-Item "$env:AppData/nushell" -ItemType Directory

Move-Item -Path ./nu_config_windows/config.nu -Destination "$env:AppData/nushell/config.nu"
Move-Item -Path ./nu_config_windows/env.nu -Destination "$env:AppData/nushell/env.nu"

Remove-Item -Path ./nu_config_windows -Recurse -force

```
