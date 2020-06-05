# iCUEbluetooth
Bluetooth toggle scripts for Corsair iCUE software. 

These scripts let you toggle bluetooth ON/OFF using a custom action from within the corsair iCUE software. eg you can toggle bluetooth via a specific button or macro from your keyboard.

## How to use
1. Enable execution of custom powershell (ps1) scripts by running the following command in a powershell window: 

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

More info: https://superuser.com/tags/powershell/info

2. Modify the path defined in`toggle.cmd` to an absolute path pointing to `bluetooth.ps1`
3. Create a "LAUNCH APPLICATION" action from within the iCUE software and point to `toggle.cmd`
4. Tie the created action to a key / macro
