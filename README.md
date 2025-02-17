# Uno-Premier-Pro-Boot-TWRP
Stock Boot.img, Stock Recovery.img &amp; Custom TwrpRecovery.img 

Build # Premier Pro_V1.0_06122023
Android 13

To Root (What I Used Anyway)

1. Boot into fastboot and use "fastboot flashing unlock" to unlock bootloader.
2. Patch Boot.img using Magisk and reboot to bootloader.
3. Use "fastboot flash boot patched_boot.img" (swap in your exact patched boot.img name)


To Flash TWRP Recovery Image

1. Download "Official TWRP App" (From Play Store or wherever as long as its official...)
2. Give TWRP "Root Access"
3. Select "TWRP FLASH"
4. No need to "Select Device", just select "Select a file to flash" and navigate to where you saved the TWRPRecovery.img
5. Select "Flash To Recovery" and "Okay" to confirm.
6. After Flash is completed go to "Reboot" option and "Reboot Recovery".
