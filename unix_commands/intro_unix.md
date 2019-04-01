# Basic Unix Commands
Note: Directory or folder are referring to the same thing.


## Changing Permissions
To change permissions type the command `chmod options file_names`  where `options` are the read, write, and execute options for the file's owner and other users. The different options are represented as follows: rwx (they must be in that order). Thus, if you only wanted to give a person write permissions, you would have to type `-w-` for the `options`.

**Example** 
`chmod ug=rw,o=r` 

* This means that a user who is not the owner has read and write permissions set to 1 (which means they can read and write), and the owner can only read the file. 

## Viewing the Directory

* To see what is in the current directory/folder type `ls`.

* To see what is in a folder or directory in the current directory, type `ls child_directory` where `child_directory` is where you are looking for files and other directories.


## Changing Directories
Typically, changing directories is used with the command `ls`. This is because unless you know the exact path to a file, you typically will need to look through different directories to find the file you were looking for. 

* To switch into a directory, type the command `cd child_directory`, where `child_directory` is another directory in the current directory. If you know the path to a directory, you can directly switch into the directory by typing `cd path_to_directory` where the `path_to_directory` is the actual path to the directory. For a walk through examples, do the unix tutorial. 

* To switch to a parent or previous directory, type the command `cd ..`. 

* To return to the home directory, type the command `cd`.