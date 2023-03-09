This directory a Bash projects task containing various shell scripts described below.

script 0: 0-iam_betty -> switches current user to betty
script 1: 1-who_am_i ->	prints the effective username of the current user
script 2: 2-groups -> prints all groups the current user is part of. Depending on the user the output will be different.
script 3: 3-new_owner -> changes the owner of the file hello to betty
script 4: 4-empty -> Creates an empty file called hello.
script 5: 5-execute -> Adds execute permission to owner of the file hello.
script 6: 6-multiple_permissions -> Adds execute permission to the owner and the group owner, and read permission to other users, to file hello.
script 7: 7-everybody -> Adds execution permission to the owner, the group owner and ther other users, to the file hello.
script 8: 8-James_Bond -> sets the permission to the file hello ------rwx.
script 9: 9-John_Doe -> Sets the mode of the file hello to -rwxr-x-wx.
script 10: 10-mirror_permissions -> Sets the mode of the file hello the same as olleh's mode. Both files will be in the working directory
script 11: 11-directories_permissions -> Adds execute permission to all subdirectories of the current directory for the owner, group owner and all other users.
script 12: 12-directory_permissions -> Creates a directory called my_dir with permissions 751 in the working directory
script 13: 13-change_group -> Changes the group owner to school for the file hello