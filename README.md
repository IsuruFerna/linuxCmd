# linuxCmd
some linux commands for Ubuntu 

How to type some symbols that arn't available in italian Keyboard 

ALT code 96 corresponds to `
ALT code 123 corresponds to { (shift + alt gr + è)
ALT code 125 corresponds to } (shift + alt gr + +)
ALT code 126 corresponds to ~

If you're not familiar with the "~" symbol, it's a shortcut that represents the current user's home directory (for example, /home/username/)

remove folder 
rm -rf <name of the folder>

giving permission to delete folder 
sudo chmod -R 777 /home/user/BLAH

If you want to give a user permission to edit the contents of a directory in Ubuntu, you can use the chmod command to change the permissions of the directory and its contents. The chmod command stands for “change mode” and is used to modify the read, write, and execute permissions of files and directories.

To give a user permission to edit the contents of a directory, you need to grant them write access to the directory. This can be done using the chmod command followed by the u+w option, which adds write permission for the owner of the directory. For example, to give the owner of a directory named mydir write permission, you can use the following command:

`chmod u+w mydir`

This will allow the owner of the directory to create, delete, and modify files within the directory.

If you want to give write permission to other users as well, you can use the g+w option to add write permission for the group, or the o+w option to add write permission for others. For example, to give write permission to both the owner and the group, you can use the following command:

`chmod ug+w mydir`

Additionally, if you want to change the permissions of all files and subdirectories within a directory, you can use the -R option with the chmod command. This will apply the specified permissions recursively to all files and subdirectories within the specified directory. For example, to give write permission to both the owner and group for all files and subdirectories within a directory named mydir, you can use the following command:

`chmod -R ug+w mydir`
