# iCUEbluetooth
Bluetooth toggle scripts for Corsair iCUE software. 

These scripts let you toggle bluetooth ON/OFF using a custom action from within the corsair iCUE software. eg you can toggle bluetooth via a specific button or macro from your keyboard.

## How to use
1. Enable execution of custom powershell (ps1) scripts by running the following command in a powershell window: 

`Set-ExecutionPolicy Unrestricted -Scope CurrentUser`

More info: https://superuser.com/tags/powershell/info

2. Create a "LAUNCH APPLICATION" action from within the iCUE software and point to `bluetooth.ps1` eg:

`powershell -File "C:\Program Files (x86)\Corsair\CORSAIR iCUE Software\bluetooth\bluetooth.ps1"`

![image](https://user-images.githubusercontent.com/9061803/88001460-32a57780-cace-11ea-9329-56cbfd71dff5.png)

3. Tie the created action to a key / macro
