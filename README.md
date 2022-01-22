# ESSENTIAL OF LINUX/UNIX COMMANDS
## Welcome to my GitHub Pages
##### This is my first Github Webpage. I am using this first time in my training duration. My first task is to present essential of Linux/Unix commands using GitHub Pages. Let's have a look!
The Unix shell has been around longer than most of its users have been alive. It has survived because it’s a powerful tool that allows users to perform complex and powerful tasks, often with just a few keystrokes or lines of code. It helps users automate repetitive tasks and easily combine smaller tasks into larger, more powerful workflows.

Use of the shell is fundamental to a wide range of advanced computing tasks, including high-performance computing. These lessons will introduce you to this powerful tool.

## Navigating Files and Directories
**1. pwd**

*pwd* stands for "print the working directory". Commands mostly read and write files in the current working directory, i.e. ‘here’, so knowing where you are before running a command is important. *pwd* shows you where you are:

![home directory as output](https://user-images.githubusercontent.com/52249880/150629417-06bcde30-a80e-47a8-8cbd-76ab3ad1c190.png)

**2. ls**

*ls* prints the names of the files and directories in the current directory. We can make its output more comprehensible by using the *-F* option which tells ls to classify the output by adding a marker to file and directory names to indicate what they are:

-a trailing / indicates that this is a directory

-@ indicates a link

-indicates an executable

![ls and ls-F command output](https://user-images.githubusercontent.com/52249880/150629451-17da43cc-8031-4843-ae02-78679128e1c9.png)
Depending on your shell’s default settings, the shell might also use colors to indicate whether each entry is a file or directory.

**--help option**

This option displays information on how to use commands or program.

![ls command with help option](https://user-images.githubusercontent.com/52249880/150629490-a0c14de4-3d54-4e69-a6b4-715db9af0d28.png)

## Exploring other Directories
We can also use ls command to list the contents of other directory. Let’s take a look at our Desktop directory by running *ls -F Desktop*, i.e., the command *ls* with the *-F* option and the argument *Desktop*. The argument Desktop tells ls that we want a listing of something other than our current working directory:

![listing desktop components using ls command](https://user-images.githubusercontent.com/52249880/150629829-42fdf91f-49b9-4d50-8f1c-429f447983b9.png)

**3. cd**

*cd* refers to as 'change directory'. This command helps to change locations followed by a directory name.
![changing directory to Desktop](https://user-images.githubusercontent.com/52249880/150629928-8cfc9e8a-489b-4958-b144-a8e90bb87a2d.png)

## Creating a Directory

**4. mkdir**

Let's create a new directory called *animals* using *mkdir* which has no output.

![creating animals directory](https://user-images.githubusercontent.com/52249880/150630082-b50bff6f-9a9c-4b57-a87d-4c904aaddcf0.png)

Note that *mkdir* is not limited to creating single directories one at a time. The *-p* option allows *mkdir* to create a directory with nested subdirectories in a single operation.

The *-R* option allows to list all the nestes subdirectories within a directory. Let's use *ls -FR* to recursively list the new directory hierarchy we just created in the project directory.

![image](https://user-images.githubusercontent.com/52249880/150630163-1cb00453-fe87-4df6-ac1b-19bfd77c316a.png)

## Creating a text file

**5. nano**

Let’s change our working directory to *animas* using cd, then run a text editor called Nano to create a file called habitat.txt:
![nano command](https://user-images.githubusercontent.com/52249880/150630427-10b96041-d8aa-4556-9ce8-f1bf8da00aaa.png)

![habitat file](https://user-images.githubusercontent.com/52249880/150630375-cbae28d8-8024-4658-9e0c-f758e0e99bb7.png)

**6. touch**

Another way to create a text file is using *touch* command.To inspect the directory use the *ls* command.

![names file created using touch command](https://user-images.githubusercontent.com/52249880/150630525-c8944ae8-6fbb-4ed3-a147-37eb8baae765.png)

## Moving Files and Directories

**7. mv**
Let's change the name of *names.txt* file to *carnivoros.txt* using *mv* command. The *mv* referes to as move, i.e. moving the *names.txt* to *carnivoros.txt* which has same effect as renaming the file.

![renaming a file](https://user-images.githubusercontent.com/52249880/150630715-7f832a84-a792-4a53-aec1-d5310eeef8ac.png)

**8. /raw**
To move the file from one directory to another, we use */raw* command.

![image](https://user-images.githubusercontent.com/52249880/150630978-6b2b922d-8c69-4891-8d5a-95e1ccbd7de4.png)

## Removing Files and Directories
**9. rm**

The *rm* command refers to as remove. It is uses to remove or tidy up a directory or file.

![removing a file](https://user-images.githubusercontent.com/52249880/150631341-ead147f2-383d-4685-9062-fee2109b7d83.png)


























