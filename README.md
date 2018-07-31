# FileEncDec
Encryption and Decryption of files using AES 256 and base 64 encoding on the file name.

#### C files : ####
1. enc.c
2. dec.c

#### Compiling : ####
$ gcc enc.c -o enc -lcrypto
$ gcc dec.c -o dec -lcrypto

#### How to run ####
Make a folder "test" in the same directory as the executable files. All files in the "test" folder and its subdirectories will be encrypted on running ./enc.
The files will be decrypted on running ./dec.
