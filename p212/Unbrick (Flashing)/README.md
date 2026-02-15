# Unbrick (Flashing)

this folder contains tutorial of how to unbrick your p212 Amlogic Box

sometimes when you flash and something gone wrong, you can't flash it again and it errors

# Requirements:
* SD Card (at least 8GB/ MAX 64GB)
* Card Reader
* a Windows Platform
* USB Male to Male

# Tutorial:
# making a bootcard
* Use the "SD Card Boot Maker" to create a Boot SD Card as "Recovery"
* Open "BootcardMaker.exe"
* on ChooseDisk, Select your SDCard Device
* Mark "To Partition and Format"
* select "Choose your Bin File" to "uboot.bin" on "SD Card Boot Maker"
* click "Make"
* after success, Click the "Format" button on a dialog box
* Format it
* eject the sd card safely

# AmlogicBox flashing
* Open UBL (Usb_Burning_Tool)
* Select the "ubl_flash.img" on "Unbrick (Flashing)" folder
* Unmark "Erase BootLoader"
* Press "Start"
* insert the Boot Card sdcard on the Amlogic Box
* Plug in the USB Male to Male to USB2 labeled on the box or the nearest USB Port within the Back Port (like ethernet, power, etc.)
* while Plugging in, Power the box with a Power brick at the same time
* Wait until Flashing is Complete
* After Completing, Unplug the box and eject the sdcard

# After All Steps
* Flash the box with Any firmware or the CheapAmlogicBox Firmware
