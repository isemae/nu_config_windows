# nu_config_windows
nah is only for windows

```
winget install nushell

git clone https://github.com/isemae/nu_config_windows.git

Move-Item -Path ./nu_config_windows/config.nu -Destination "$env:AppData/nushell/config.nu"

Remove-Item -Path ./nu_config_windows -Recurse -force

```
