# AndroidRootUpgrade
HOWTO: <br/>
1. Install HTC_Treiber_v4.0.1.001.exe <br/>
2. unpack HTC_Desire_Android_2.3_Upgrade.rar and run it.<br/>
3. After it is done go into settings -> application -> disable fastboot, then goto -> development -> enable usb debugging.<br/>
4. Boot into Hboot.
  - power off;
  - hold press the volume down button and press the power button;
  - look for the hboot version it should be written in the second line it will ether be 0.93 or 1.02;
  - press the power button again to go into fastboot, use the volume buttons and select reboot and then press the power button; <br/>
  - 
5. unpack revolutionary-0.4pre4.zip and run it(if it says that it's already s-off then go to 6)
  - goto http://revolutionary.io/
  - click download(you don't need to download it) a window should appear saying Beta key.
		- select your operating system
		- under select device select HTC desire
		- under HBOOT select the version.
  - the serial number should be written in revolutionary window
  - when done press get beta key.
  - type in the betakey in revolutionary and press enter;
6. It will start up in fastboot, if the revolutionary says download fail<br/>
  - then unpack adb-fastboot-win.zip, go into the folder hold right shift down and right click, go down and select open command window here or start cmd and then navigate to the folder or click on start.cmd.
  - type or copy or type -> fastboot flash recovery recovery-clockwork-touch-5.8.0.2-bravo.img
  - press the power button to navigate to hboot, go down and select recovery.
7. it should now be restarted in clockworkmod<br/>
	Note: you can use the screen touch now, and the power button does not work in clockworkmod
  - select mounts and storage
  - go down to the bottom and select mount usb storage
  - make a folder or place in root on the sd card ev_bravo-4.0.0p2-turba.zip and gapps-core-kk-2013-11-25.zip.
  - when done click on unmount
  - go back and Select Wipe data/Factory reset, then select Yes on the next screen to confirm factory reset
  - Select Wipe Cache Partition, then select Yes on the next screen to confirm wiping cache.
  - Now, format the system. Go to mounts and storage and select format/system, and then select Yes on next screen.
  - Select Install zip -> Choose zip from sd card (or external sd card, you know where your files are)
  - Select ev_bravo-4 and yes
  - Select Install zip -> Choose zip from sd card
  - Select gapps-core-kk-2013-11-25 and yes
8. go back and select reboot system<br/>
  - done 
