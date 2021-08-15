# BLS-BashLikeShell
A C++ implementation of a CLI shell for Linux

1.	 bls.cpp: This contains the main method through which the shell program begins execution. The main method contains an infinite loop that infinitely prompts the user to enter a command in the shell interface. After the command is entered, the code in bls.cpp calls other functions in the same file and in other cpp program files as included in the form of headers to process the commands.
2.	tokeniser.cpp: This file contains the code for taking the input of the line of commands which is sent as a string of characters to a method present in the code, which in turn does the job of converting the string into an array of tokens that were separated by tabs, carriage-returns or blank spaces in the original string.
3.	NBC_handler.cpp: This file contains the code for handling commands that were defined by me in this project, along with some other helpful functions that handle some functionalities such as handling multiline commands.
4.	execMaster.cpp: This file contains the code for executing commands of the Linux shell. In the process of executing such commands, as received in the form of an array of tokens from a function call from inside bls.cpp or NBC_handler.cpp, the code processes the tokens for the presence of pipes or instructions to redirect the output to files as specified by the user in the command.
![image](https://user-images.githubusercontent.com/71808978/129468990-d2ed6822-6ab5-4b0c-a954-a61753be354b.png)

The exef command:
![image](https://user-images.githubusercontent.com/71808978/129469004-d574dbae-a6ec-4723-84f3-65e522e47e77.png)

The lpc command:
![image](https://user-images.githubusercontent.com/71808978/129469014-d1201ff1-cb94-4b9c-81e9-51e1def0d61f.png)
![image](https://user-images.githubusercontent.com/71808978/129469022-47b7db99-2b5e-4e17-acdf-127fe389fd45.png)
