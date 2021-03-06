### CSE 15L: Lab Report 1
*Week 2, 10 April 2022*

**Lab 1**

__Installing VScode__

Download the appropriate [vsCode](https://code.visualstudio.com/) version for your computer. See VScode starting window below:

![VScode Screenshot](./Images/Screen%20Shot%202022-04-10%20at%201.49.05%20PM.png)

__Remotely Connecting__

Open new vsCode terminal using conbtrol + shift + a backtick. Connect to the remote computer using the command $ ssh cs15lsp22zz@ieng6.ucsd.edu where zz is the letters in your account. Go to [Account Lookup](https://sdacs.ucsd.edu/~icc/index.php) to find it. 

If it is your first time connecting, it will ask a question. Type "yes" but feel free to find more details on [here](https://superuser.com/questions/421074/ssh-the-authenticity-of-host-host-cant-be-established/421084#421084). It will also ask for a password. 

Here's a screenshot of me remotely connecting:

![Remote Connection](./Images/Screen%20Shot%202022-04-10%20at%202.56.50%20PM.png)

Please note, I have connected before so some steps are missing in my screenshot.

__Trying some commands__

Here are some commands to try. cd "directory name", to change to specified folder. pwd, to state the current folder. ls, to list the files in the current directory. See screenshot below:

![Commands](./Images/Screen%20Shot%202022-04-10%20at%202.57.38%20PM.png)
  
__Moving files__

Run the scp command on your personal computer to move a file to the remote computer. ie. scp <file name> cs15lsp22zz@ieng6.ucsd.edu:~/. You can use the command "exit" to cut remote connection. See screenshot below: 
  
![Moving files](./Images/Screen%20Shot%202022-04-10%20at%203.01.45%20PM.png)
  
__Setting Up SSH Key__

Run "ssh-keygen" to generate encryption key pair on personal computer.  No passphrase required. Connect to remote computer to create .ssh file on remote computer. Disconnect and use scp to transfer __PUBLIC__ key only. 
  
![SSH Key Setup](./Images/Screen%20Shot%202022-04-10%20at%203.02.30%20PM.png)
  
__Optimiszating Remote Running__
  
Note, SSH key pair removes password requirement. Separate multiple lines with semi colons. Use up arrow to recall last entered line.
  
![Optimized](./Images/Screen%20Shot%202022-04-10%20at%204.19.38%20PM.png)
  
  




