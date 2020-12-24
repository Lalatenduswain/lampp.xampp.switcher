# lampp_switcher
# lampp.xampp.switcher

Simple lampp switcher 

Welcome to the lampp switcher!

Before you run it, Please MAKE A BACKUP from your lampp directory, you can do it using:

`~$ sudo tar czvf /home/$USER/lamp.tgz /opt/lampp/`

This script do not install xampp on your machine, just switch between installations

Before you run it, make sure you have property install xampp in /opt folder(default for xampp ) in my case I do:

Install lampp with php5 on /opt/lampp

Rename folder lampp to lampp5 after lampp installation (your version choise)

`~$ sudo mv /opt/lampp /opt/lampp5`

install lampp with php8 on /opt/lampp

rename folder lampp to lampp8 after lampp installation with php8 (Your Version Choice)

`~$ sudo mv /opt/lampp /opt/lampp8`

    $ ls -l /opt
    drwxr-xr-x 30   4096 jul 15 00:30 lampp5
    drwxr-xr-x 29   4096 jul 14 20:16 lampp8

!!!!! BACKUP dont forget it, MAKE it an EXECUTABLE !!!!

`~$ sudo chmod +x lampp_switcher.sh`

Run

`~$ ./lampp_switcher.sh`


Credit Goes to Rafaelphp
