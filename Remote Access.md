# Part 1: Your CSE15L Account
Look up your course-specific account for CSE15L here:
[https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

Follow this guide to help reset your password: [[Tutorial]How to Reset your Password](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit)

It may take a while (usually 15 mins) before you can start using your password on the remote server.

# Part 2: Visual Studio Code
Follow the instructions on the website [https://code.visualstudio.com/](https://code.visualstudio.com/) on how to install Visual Studio Code on your computer.

It should look something like this: 
![Screenshot 2023-01-16 204946](https://user-images.githubusercontent.com/122580027/212812549-8485a64a-4f39-4904-bd66-b9fae9eafcab.png)


# Part 3: Remotely Connecting
For Windows, you would have to install `git` whoch comes with useful tools that we need: [Git for Windows](https://gitforwindows.org/)

Once installed, follow the instructions on the link below to set your default terminal to use `git bash` in Visual Studio Code:

[Using Bash on Windows in VS Code](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)

Then, open a terminal in VSCode (Ctrl/Command + `). Your command should look similar to this, but with your course-specific account.

`$ ssh cs15lwi23ava@ieng6.ucsd.edu` 

It should look like this if this was your first time logging in:

![Screenshot 2023-01-16 211537](https://user-images.githubusercontent.com/122580027/212815693-9dbac5fb-9ba4-4375-9dcc-f22ed7491063.png)

Type yes on the following questions and it should finally ask for you password. Use the password you created during the first step.

Then you should get a message like this:

![Screenshot 2023-01-16 211911](https://user-images.githubusercontent.com/122580027/212816154-d241be74-79a1-41a0-b68a-93a00265ae77.png)

You are finally connected to the remote terminal in the CSE basement, and any command you run will also run on that computer.

#Part 4: Run Some Commands

Try running some commands such as: `cd`, `ls`, `pwd`, `mkdir`, and `cp` in different ways.

Here are some useful commands you should try: 

* `cd ~` changes your current directory to your home directory.
* `cd <directory>` where `<directory>` is a folder within the current directory. This changes it to that specific directory.
* `cd ..` helps you go back to the previous directory.
* `ls -a` lists files and folders in the current directory.
* `ls -lat` lists all files and folders in the current directory with more details. 
* `ls <directory>` where `<directory>` is `/home/linux/ieng6/cs15lwi23/cs15lwi23abc`, where `abc` is one of the other group member's username.  
* `pwd` shows current directory.

To log out of the remote server, you can use:

* Ctrl + D
* Or type the command `exit`
