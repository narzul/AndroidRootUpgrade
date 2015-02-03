# AndroidRootUpgrade A8181
## Android 2.x.x -> 4.4.2
HOWTO: <br>
1: Install HTC_Treiber_v4.0.1.001.exe <br>
2: unpack HTC_Desire_Android_2.3_Upgrade.rar and run it.<br>
3: After it is done go into settings -> application -> disable fastboot, then goto -> development -> enable usb debugging.<br>
4: Boot into Hboot.<br>
	- power off;<br>
	- hold press the volume down button and press the power button;<br>
	- look for the hboot version it should be written in the second line it will ether be 0.93 or 1.02;<br>
	- press the power button again to go into fastboot, use the volume buttons and select reboot and then press the power button;<br>
5: unpack revolutionary-0.4pre4.zip and run it(if it says that it's already s-off then go to 6)<br>
	- goto http://revolutionary.io/<br>
	- click download(you don't need to download it) a window should appear saying Beta key.<br>
		- - select your operating system<br>
		- - under select device select HTC desire<br>
		- - under HBOOT select the version.<br>
	- the serial number should be written in revolutionary window<br>
	- when done press get beta key.<br>
	- type in the betakey in revolutionary and press enter;<br>
6: It will start up in fastboot, if the revolutionary says download fail<br>
	- then unpack adb-fastboot-win.zip, go into the folder hold right shift down and right click, go down and select open command window here or start cmd and then navigate to the folder or click on start.cmd.<br>
	- type or copy or type -> fastboot flash recovery recovery-clockwork-touch-5.8.0.2-bravo.img<br>
	- press the power button to navigate to hboot, go down and select recovery.<br>
7: it should now be restarted in clockworkmod<br>
	Note: you can use the screen touch now, and the power button does not work in clockworkmod<br>
	- select mounts and storage<br>
	- go down to the bottom and select mount usb storage<br>
	- make a folder or place in root on the sd card ev_bravo-4.0.0p2-turba.zip and gapps-core-kk-2013-11-25.zip.<br>
	- when done click on unmount<br>
	- go back and Select Wipe data/Factory reset, then select Yes on the next screen to confirm factory reset<br>
	- Select Wipe Cache Partition, then select Yes on the next screen to confirm wiping cache.<br>
	- Now, format the system. Go to mounts and storage and select format/system, and then select Yes on next screen.<br>
	- Select Install zip -> Choose zip from sd card (or external sd card, you know where your files are)<br>
	- Select ev_bravo-4 and yes<br>
	- Select Install zip ->	Choose zip from sd card<br>
	- Select gapps-core-kk-2013-11-25 and yes<br>
8: go back and select reboot system<br>
	- done<br> 
