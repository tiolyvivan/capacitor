# How to Install Driver for Roland Stika STX-7 Vinyl Cutter on Windows 8
 
If you have a Roland Stika STX-7 vinyl cutter and want to use it on Windows 8, you might encounter some difficulties finding and installing the right driver. The STX-7 is a legacy product that was designed for older versions of Windows, such as Windows 95/98/Me. Roland does not offer a supporting Windows 8 driver for this device[^1^]. However, there is a workaround that might help you get your STX-7 up and running on Windows 8. Here are the steps you need to follow:
 
1. Download the latest driver for the Stika SV-8 vinyl cutter from Roland's website[^2^]. The SV-8 is a newer model that is compatible with Windows 8. The driver file name is `sv_w832_130.zip`.
2. Extract the zip file to a folder on your computer. You should see a folder named `SV_W832_130` with several files inside.
3. Open the folder and locate the file named `SV_W832_130.inf`. This is the driver installation file.
4. Right-click on the file and select `Open with`. Choose `Notepad` or any other text editor.
5. In the text editor, find the line that says `[Roland.NTamd64]`. This is the section that lists the supported devices for 64-bit Windows.
6. Under this section, add a new line with the following text: `%RDID0053.DeviceDesc%=RDID0053Install, USB\VID_07CF&PID_1001`. This will add the STX-7 device ID to the driver file.
7. Save and close the file.
8. Connect your STX-7 to your computer via USB cable. Make sure it is turned on.
9. Open the `Device Manager` on your computer. You can do this by pressing `Windows + X` keys and selecting `Device Manager` from the menu.
10. You should see an unknown device with a yellow exclamation mark under `Other devices`. This is your STX-7.
11. Right-click on the unknown device and select `Update Driver Software`.
12. Select `Browse my computer for driver software`.
13. Select `Let me pick from a list of device drivers on my computer`.
14. Select `Have Disk`.
15. Browse to the folder where you extracted the SV-8 driver files and select the `SV_W832_130.inf` file. Click `Open`.
16. You should see a list of Roland devices. Select `Roland SV-8`. Click `Next`.
17. You might get a warning message saying that the driver is not digitally signed. Click `Install this driver software anyway`.
18. The driver installation should complete successfully. Click `Close`.
19. Your STX-7 should now appear as a Roland SV-8 under `Printers and devices`. You can rename it if you want.
20. You can now use your STX-7 with any software that supports Roland cutters, such as Dr. Stika[^1^] [^3^], CutStudio, or CorelDRAW.

Congratulations! You have successfully installed the driver for your Roland Stika STX-7 vinyl cutter on Windows 8. Enjoy your cutting!
 
**Download File ✵✵✵ [https://t.co/aWhXG5OuyF](https://t.co/aWhXG5OuyF)**


 8cf37b1e13
 
