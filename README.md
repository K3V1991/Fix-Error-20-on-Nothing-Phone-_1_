<p align="center"><img src="https://i.ibb.co/2s2SBY5/Fix-Error-20.png" width="200"></a>
<h1 align="center"><b>Fix Error 20 (update failed! ERROR is :20) on Nothing Phone (1)</b></h1>
<br />

<p align="center">
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white">
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white">
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white">
</p>
<hr>
<br />

## NFO:
Error 20 is caused because root is installed (Timestamp changed)
<br />
<br />

## How-To 1 - Restore Boot Image:
1. Open Magisk
2. Click on "Uninstall Magisk" > "RESTORE IMAGES"
3. Reboot
4. Search & install the Update from "Options" > "About phone" > "Software info" > "NOTHING OS (1)" > "Check for update"
<br />

## How-To 2 - Flash Stock Boot Image:
https://github.com/K3V1991/How-to-flash-Android-Kernel-and-Recovery
<br />
<br />

## How-To 3 - Reinstall Full ROM:
1. Download the Full Version of the Firmware you installed
2. Create a Folder named "ota" in the Root of Phone
3. Put the Update Zip in the created Folder
4. Open the Dialer and type: *#*#682#*#*
5. Local System Update opens, select the Update Zip
6. Tap "PROCEED & REBOOT"
7. The Phone reboot, first Initialisation after Update
<br />

## Safe rooting the updated Phone:
1. Reboot to Bootloader
2. Boot a Magisk Patched Boot Image by using the Command:
```
fastboot boot <kernel file name>.img
```
3. Phone reboots to System
4. Open Magisk
5. Tap the "Install" Button
6. Choose "Direct Install (Recommanded)"
7. Reboot (If the Magisk patched Boot File don't boot, just do a hard Shutdown by pressing ON/OFF Button for 5 Seconds, the Device reboots with your Stock Boot)
