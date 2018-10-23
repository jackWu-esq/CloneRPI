CloneRPI
========

Clone the raspberry pi image to another SD card  
For the same size of SD card, "Backup & Restore" method are suggrested, it would be more effective.  
For the different size of SD card "Clone" method are suggested, this method would much slower than "B&R" but it can resize for different size of SD card.

* * * * *

Clone the RPI to the another SD card(For different size)
--------------------------------------------------------

1.  Download the
    [clone/rpi-clone-master.zip](https://github.com/jackWu-esq/CloneRPI/tree/master/clone)
    to RPI \
    \
     Or use the command

    `         git clone https://github.com/billw2/rpi-clone.git`<br />
    `         cd rpi-clone`<br />
    `         sudo cp rpi-clone rpi-clone-setup /usr/local/sbin`
2.  Insert the **target** sd card in to the card reader and put it on
    **RPI** usb port.
3.  `sudo ./rpi-clone-setup -t testhostname`
4.  `sudo ./rpi-clone sda`
5.  Follow the guideline on screen
6.  Unmount the sd card reader
7.  The target sd card are ready to use in another RPI

Reference link https://github.com/billw2/rpi-clone

* * * * *

Backup the SD image
-------------------

This method is for the mass deploy to same size of sd card\
 This method is much faster then "Clone", but this backup image are not
guarantee can be used in different size of SD card.\

1.  Insert the **source** sd card in to the card reader and put it on
    **PC** usb port.
2.  use the
    [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/)
    to backup it to .img file \
     *Please node that the file name must like "xxx.img"*

Restore the image to SD card
----------------------------

1.  Insert the **target** sd card in to the card reader and put it on
    **PC** usb port.
2.  use the
    [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/)
    to restore the .img file \
     *Please node that the file name must like "xxx.img"*

