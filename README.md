# Linuxcpu-freq-temp
Simple Python scripts to monitor your cpu frequency and temperature on linux.

Scripts that measure frequency requires sudo privileges

##MAKE THE SCRIPTS GLOBAL##

***Making the script global means that you can run it wherever the PATH you are, it would work like typing 'ls', 'cd', etc..***

1-The path to the python interpreter may vary so in the first line of the python scripts change it to your path o python interpreter
        
        In my case it is #!/usr/bin/python3

2-Make the file executable(type in the terminal):
      
      sudo chmod +x file.py 
 
 Where file is the actual python script

3-Give permissions to execute to the rest of the users if you wish so.

4-Copy the python script to /usr/local/bin
      
      sudo cp file.py /usr/local/bin
      
5-DONE! Now you can just type in the terminal the name of the python script and it will run.

***I recommend making an alias in ~/.bashrc so you can just type the word frequency and it will run the python script, it looks more natural.***
