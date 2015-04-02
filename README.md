# Nokia N900 Maemo Flasher 3.5

Maemo Flasher 3.5 for Nokia N900

For getting it work under Ubuntu 14.04 x64. 

----------------------------------------------------------------------------------
METHOD -1:
----------------------------------------------------------------------------------

Directly extract the .zip package and install the flasher...deb.

$ sudo unzip ./maemo_flasher-3.5_2.5.2.2_i386.zip

$ sudo dpkg -i ./maemo_flasher-3.5_2.5.2.2_i386.deb

When the dpkg throws dependency error, execute the following command.

$ sudo apt-get -f install

Now missing dependencies will be installed.

Next install the 'maemo_flasher-3.5_2.5.2.2_i386.deb' file again.

$ sudo dpkg -i ./maemo_flasher-3.5_2.5.2.2_i386.deb

Now the flasher should be installed successfully.

------------------------------------------------------------------------------------
METHOD -2:
-------------------------------------------------------------------------------------

First install 'gcc-4.9-base:i386', 'libc6:i386', 'libgcc1:i386' and 'libusb-0.1-4:i386' using 'apt-get'.

Execute the following commands before installing flasher.

$ sudo apt-get update
$ sudo apt-get install gcc-4.9-base:i386 libc6:i386 libgcc1:i386 libusb-0.1-4:i386

Then extract the 'maemo_flasher-3.5_2.5.2.2_i386.zip'.

$ unzip ./maemo_flasher-3.5_2.5.2.2_i386.zip

Then install flasher......deb.

$ sudo dpkg -i ./maemo_flasher-3.5_2.5.2.2_i386.deb

done.
