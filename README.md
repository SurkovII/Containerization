Создадим папку testfolder в и скопируем необходимые исполняемые файлы и библиотеки в эту папку:

mkdir ~/testfolder

mkdir ~/testfolder/bin

cp /bin/bash ~/testfolder/bin

mkdir ~/testfolder/lib ~/testfolder/lib64

cp /lib/x86_64-linux-gnu/libtinfo.so.6 ~/testfolder/lib

cp /lib/x86_64-linux-gnu/libc.so.6 ~/testfolder/lib

cp /lib64/ld-linux-x86-64.so.2 ~/testfolder/lib64/

Запустим команду chroot

sudo chroot ~/testfolder

![pic1](Cont/Pic1.PNG)

Запустим команду ls
