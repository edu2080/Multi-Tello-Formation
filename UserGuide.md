User Guide：

1、There are two folders under tello-swarm,'multi_tello_test' and 'ap_setup'.

2、The multi_tello_test folder contains the main program for executing muliti-tello-swarm program. 
   Before double-clicking multi_tello.exe to run, you must ensure that there is a text file named 'Tello_EDU_CMD.txt' 
   in the same path of 'multi_tello.exe'. This file is a script for muliti-tello-swarm. 
   For more details on how to write muliti-tello-swarm scripts, please refer to README.md in the python folder.
   Attention:1. The file name of the txt file (Tello_EDU_CMD.txt) cannot be modified!
			 2. Other files in the folder must not be arbitrarily changed or deleted!
			 
3、The ap_setup folder contains a helper program for setting the tello EDU to enter the station mode.
   Before double-clicking multi_tello.exe to run, you must ensure that there is a text file named 'ap_setup.txt' 
   in the same path of 'ap_setup.exe'. There is only one line in the file, the format is:
   wifi'ssid,wifi's password。Like: tello_nest,tellotello。
   Edit the txt file according to your own ap name and password.
   Attention:1. The txt text file (ap_setup.txt) file name cannot be modified!
			 2. In ap_setup.txt, the middle ',' is indispensable!

   
