helloworld-bootloader
=====================

A simple bootloader made in basic assembly language that prints a given string.


INSTRUCTIONS: 

1. *nasm bootloader.asm -f bin -o boot.bin*

2. *sudo dd if=boot.bin bs=512 of=path_toimg_file*

3. Emulate the .img file
