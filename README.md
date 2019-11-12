# raidwatcher
This script checks if something is wrong with the RAID device and displays a simple information or a warning.


Syntax :

     raidwatcher [-d DIALOGAPP] [-n NAME]

     raidwatcher [-h]

     raidwatcher [-v]


Options :

       -d :        the dialog application to use. Kdialog or zenity can be used.
  
       -h :        display the help.
  
       -n :        name of the RAID device to watch.
  
       -v :        this script version.


Exit status :

     0 = success

     1 = failure due to wrong parameters

     2 = abnormal exit


To inform about the problems : https://github.com/ShaoLunix/raidwatcher/issues.
