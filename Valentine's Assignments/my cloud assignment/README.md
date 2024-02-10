# Excercise:

  >Your login name: altschool i.e., home directory /home/altschool. The home directory contains the following sub-directories: code, tests, personal, misc Unless otherwise specified, you are running commands from the home directory 
  

  `vagrant@ubuntu-focal:~$ sudo useradd -m Altschool` // Create user Altschool(root user)

  `Altschool@ubuntu-focal:~$ mkdir code tests personal misc` // Create folders

 ## Instructions:
  > A. Change directory to the tests directory using absolute pathname

   . . .

  ![Absolute pathname](./img/A.PNG)

  . . .

 > B. Change directory to the tests directory using relative pathname

   . . .
  
  ![Relative pathname](./img/B.PNG)

   . . .

  > C. Use echo command to create a file named fileA with text content "Hello A' in the misc directory

  . . .

  ![Echo command](./img/C.PNG)

  . . .

  > D. Create an empty file named fileB in the misc directory. Populate the file with a dummy content afterwards

   . . .

  ![fileB in misc directory with written dummy](./img/D.PNG)

   . . .

  > E.Copy contents of fileA into fileC

   . . .

  ![Copying fileA into fileC](./img/E.PNG)

   . . .

  > F. Move content of fileB into fileD

  . . .

  ![Moving fileB into fileD](./img/F.PNG)

  . . .

  > G. Create a tar archive called misc.tar for the content of misc directory

   . . .

   ![Creating the tar archive for the content of misc directory](./img/G.PNG)

   . . .


   > H. Compress the tar archive to create a misc.tar.gz file

   . . .

   ![Compressing](./img/H.PNG)

   . . .

   >I. Create a user and force the user to change his/her password upon login

   . . .

   ![Forcing change of password](./img/I.PNG)

   . . .

   >J. Lock a users password

   . . . 

   ![Locking password](./img/J.PNG)

   . . .

   >K. Create a user with no login shell

   . . .

   ![Cresting user with no login](./img/K.PNG)

   . . .

   >L . Disable password based for ssh

   . . .
   
    Altschool@ubuntu-focal:~$ sudo vi /etc/ssh/sshd_config
   ![ Password based authentication](./img/L.PNG)

   . . .

   >M. Disable root login for ssh

   . . .

       Altschool@ubuntu-focal:~$ sudo vi /etc/ssh/sshd_config
   ![Password based authentication](./img/M.PNG)
    




