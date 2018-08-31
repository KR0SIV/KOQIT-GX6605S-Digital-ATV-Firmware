# KOQIT-GX6605S-Digital-ATV-Firmware
Modified firmware for the KOQIT K1Mini GX6605S for use as a digital amateur television receiver.
This firmware currently removes all satellites listed in these recievers and replaces it with six DATV channels for amateur television use.

In the future I plan to futher modify the firmware to remove features unused by amateur operation.

## Frequency Explaination

By default the reciever will use a 50hz refresh rate, if you live in the USA You'll want to use the composite output to perform this update as HDMI will not fucntion at that refresh rate in this region. Depending on the flash you use you can keep the 50hz rate or switch to 60hz and change the settings needed to allow you to easily pull up your Digital ATV signal.

These channels are as follows. 

    Channel	    TP Freq	    Polor   Symbol	True/Amateur Freq
    
    1           10992           H       2000        1242
    2           10994           V       2000        1244
    3           11004           H       2000        1254
    4           11006           V       2000        1256
    5           11028           H       2000        1278
    6           11030           V       2000        1280


The above are the channel corresponding channel/frequncy and transponder details.
This assumes configuration for a 9750 LNB, ie the rx looks for your freq shifted 9750 up in
the ui.

The H/V polarization is there purely so that the rx allows you to have frequncies so close
together. DVB-S and DVB-S2 should work without reconfiguring assuming you use a 2000ks rate.

# Installation

Simply add the .bin file to the root of a flash drive and flash it via your SYSTEM UPDATE menu.

## NOTICE
  
    I will not be responsible for any damnage to your reciever. This has only been tested on the K1 mini KOQIT.
  
