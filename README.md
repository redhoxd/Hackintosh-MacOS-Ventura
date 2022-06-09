# Hackintosh-MacOS-Ventura
successfully install Hackintosh macOs Ventura 13.0 on Msi Modern 14 B10Mw
Bugs WIFI
![Screen Shot 2022-06-09 at 19 34 36](https://user-images.githubusercontent.com/38489058/172849644-190216c4-b13f-47ec-a072-88c95a29878a.png)
#macos #hackintosh #hackintoshventura #hackintoshmacOSbeta
Disable boot-args : -lilubetaall SecureBootMOdel=0 keepsyms=1 debug=0x100
![Screen Shot 2022-06-09 at 22 20 45](https://user-images.githubusercontent.com/38489058/172883826-d2370aab-aa01-4125-b731-f0f9875b7d43.png)

Before Update :

Requirements
latest opencore update (Opencore 8.1)
Update all Kext

Next....

Disable boot-args : -lilubetaall SecureBootMOdel=0 keepsyms=1 debug=0x100 (note Use SecureBootMOdel=0 For MSI Modern 14 B10MW )

Edit Your Config.plist
Booter-Quirks = ((AvoidRuntimeDefrag Set NO)) 
![Screen Shot 2022-06-09 at 22 22 59](https://user-images.githubusercontent.com/38489058/172886037-dbb87173-3c7e-48b6-9adc-057fc24701bb.png)


Update MacOS Monterey 14.4 to MacOS Ventura 13.0 Beta
Downlaod Beta Profile
And Upadate From OTA


If your device does not support, please change Smbios to 2017 or later, adjust to the one that is close to the specifications of your device
*opencore configurator

thank you
good luck :)
