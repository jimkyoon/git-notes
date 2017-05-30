# Terminal (Mac)
Terminal is similar to the Command Prompt on Windows, except this is on the Mac OS. Terminal is similar to UNIX, so Linux users will see a similarity.

To open and use the Terminal, press "CMD" and "space" on the keyboard. Once the search bar is open, type in "terminal" and open it up.

Other way is to just open up Launchpad, opening up "Others," and find Terminal.

Now that we have it opened, let's get started!

# Basic Commands
These are some of the commands you will use majority of the time!

### pwd - Present Working Directory
```
pwd
```
This command shows where you are in your file system.

### ls - List
```
ls
```
This command shows all the files and folders that are in the current directory.

### cd - Change Directory
```
cd
```
This command will change and relocate you to another directory, whether that be the parent or child folder, depending on the command used.

```
cd Desktop
```
Change current directory to the Desktop.

```
cd ..
```
Change current directory to the parent folder.

```
cd /
```
Change to the root directory.

### mkdir - Make Directory or Folder
This command will make a new folder in the current directory you are in. After you write the command, hit space and enter the name of the folder you want.
```
mkdir new_folder_name
```

### Deleting folders
To remove a folder, there are two ways:
1. First one is used if the folder you want to delete is empty
```
rmdir new_folder_name
```
2. The second one is delete a folder with content inside. To do so, you need to use the "-rf" command, which is "recursive force," which is saying to continuously remove all files inside until the folder is empty, then delete folder, without permission.
```
rm -rf new_folder_name
```

### touch - Create file and rm - Remove
To create a file, use the "touch" command and the file name after. Make sure to also type in the file type!
```
touch index.html
```
To remove a file, use:
```
rm index.html
```

### mv - Rename or Move File
The "mv" command has 2 functions. One is to rename a file. The other is to move it.
To move it, simply type rm, followed by the current file name, and then the location you wish to move it, along with a name (changed or not).
```
mv index.html ../index.html
```
To rename it, just simply after "mv" type in the current file name, then the new file name
```
mv first.html second.html
```
