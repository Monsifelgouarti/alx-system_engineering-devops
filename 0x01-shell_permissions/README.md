0x01. Shell, permissions
0- Script 0-aim_bettythat switches the current user to the user betty.
1- Script 1-who_am_i that prints the effective username of the current user.
2- Script 2-groups that prints all the groups the current user is part of.
3- Script 3-new_owner that changes the owner of the file hello to the user betty.
4- Script 4-empty that creates an empty file called hello.
5- Script 5-execute that adds execute permission to the owner of the file hello.
6- Script 6-multiple_permissions that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7- Script 7-everybody that adds execution permission to the owner, the group owner and the other users, to the file hello.
8- Script 8-James_Bond  that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
9- Script 9-John_Doe that sets the mode of the file hello to this:-rwxr-x-wx.
10- Script 10-mirror_permissions that sets the mode of the file hello the same as olleh’s mode.
11- Script 11-directories_permissions that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12- Script 12-directory_permissions Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13- Script 13-change_group that changes the group owner to school for the file hello.
14- Script 100-change_owner_and_group that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15- Script 101-symbolic_link_permissions that changes the owner and the group owner of _hello to vincent and staff respectively.
16 - Script 102-if_only that changes the owner of the file hello to betty only if it is owned by the user guillaume.
17- Script 103-Star_Wars that will play the StarWars IV episode in the terminal.
