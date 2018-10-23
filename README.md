# CloneRPI
Clone the raspberry pi image to another SD card


## Clone the RPI to the another SD card
1. Download the [clone/rpi-clone-master.zip](https://github.com/jackWu-esq/CloneRPI/tree/master/clone) to RPI 
####
1. Or use the command     
     git clone https://github.com/billw2/rpi-clone.git 
     cd rpi-clone
     sudo cp rpi-clone rpi-clone-setup /usr/local/sbin
2. Insert the sd card in to the card reader and put it on usb port.
3.     sudo ./rpi-clone-setup -t testhostname
4.     rpi-clone sda
5. follow the guideline on screen
