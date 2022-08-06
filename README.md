# Boundless-Third-Person-Mod

Provided “As is” 

Update: Now supports being updated through the "MemAddress" and "JoyX MemAddress" inputs in the f4 menue.  Request new Addresses from Jiivita on the Boundless forums or DIY with the help of this video: 
"How to Update the 3rd Person Mod"
https://youtu.be/v0qZT9Los7E


Usage: To enable zooming the camera in and out in third person for a better view.

The script will need an update with each new release of Boundless (testing servers not supported), and I will do my best to do so in a timely manner.

Extract the " Boundless Third Person Mod.exe " And " Third_Person_Mod.ini " to the same location and run the .exe AFTER launching Boundless.

Alternately you can use the Boundless Third Person Mod.ahk (if available) instead of the .exe if you have autohotkey installed.

You can alter settings and hotkeys by hitting the menu hotkey (F4 by default) or by editing the .ini directly (though making a backup would be advised). If an unrecognized hotkey is entered then the default for that control will be loaded.  However if you edit the .ini and change the default to an invalid hotkey… then the functionality will break.

Sample Defaults:
DefaultZoom_Out=+WheelDown 
DefaultZoom_In=+WheelUp 
DefaultCam_up=^WheelDown
DefaultCam_down=^WheelUp
DefaultZoom_Step=0.75
DefaultCam_Step=0.05
DefaultMv=0
DefaultGv=16
DefaultHv=1.5
DefaultMenu=F4

for more information on valid hotkey names see:
https://autohotkey.com/docs/KeyList.htm
and:
https://autohotkey.com/docs/Hotkeys.htm
For modifier symbols (shift, alt, ctrl, etc) 
