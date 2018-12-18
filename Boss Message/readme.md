Boss Message is a digital forensics challenge.


It is a password protected zip file.


We need to crack the password! I used fcrackzip.

![1](https://user-images.githubusercontent.com/32056749/50158943-17fd9200-02de-11e9-8dd3-7e8e78ecc9b1.png)

On viewing the directory content we found an image and a file.


The file contains the flag's cipher.

![2](https://user-images.githubusercontent.com/32056749/50158948-1a5fec00-02de-11e9-92a5-8c19eb6f6050.png)

WHOOOO IS THIIISSS !!!!

"Morgan Freeman".

![3](https://user-images.githubusercontent.com/32056749/50159090-79256580-02de-11e9-8ef3-73bd56813fdc.png)

The flag's cipher is "Vigenere Cipher". Trying to decode the cipher using many complex of the actor name to finally try the word "morgan" only which is the right key.
And here comes the FLAG!

![4](https://user-images.githubusercontent.com/32056749/50159210-d4efee80-02de-11e9-87e1-d867893cb873.png)
