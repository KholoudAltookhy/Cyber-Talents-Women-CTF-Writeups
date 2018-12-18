Help Ann is a Digital Forensics Challenge.
The hint stated that Ann used QR code to scan an image but it finds out that the image was corrupted.

Using command file on "help_ann_please" was useless.
Renaming the image "help_ann_please.PNG" was useless also.
So I tried to open the image using Hex Editor "010 Editor". 
Checking the magic byte of the given image and it was "00 50 4E 47" which happens to be incorrect form for the PNG images.

![1](https://user-images.githubusercontent.com/32056749/50157756-f18a2780-02da-11e9-8f75-b82d86176a46.png)

Searching for the correct magic byte

![2](https://user-images.githubusercontent.com/32056749/50157758-f18a2780-02da-11e9-9661-28b7c9e3da9e.png)

We found that all is needed is to change "00" to "89" in the hex editor and save the image with it's correct extension ".PNG".

AND HERE IS THE IMAGE!

![3](https://user-images.githubusercontent.com/32056749/50157759-f18a2780-02da-11e9-9980-7046bdb81d0e.png)

All you need to do is to scan it using any QR Code Scanner I used "QRobot".
The flag is "Flag{Aw3s0m3-Y0u-G0t-th1s}".
