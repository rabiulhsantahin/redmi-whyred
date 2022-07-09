# redmi-whyred
How to install twrp

adb devices -l 
adb start-server
adb reboot bootloader
fastboot devices
fastboot flash recovery .\twrp-whyred.img
fastboot boot .\twrp-whyred.img

If 
fastboot boot .\twrp-whyred.img
< waiting for any device >
Fix https://www.youtube.com/watch?v=Oc-YTzGJVE0
find zip in repo
