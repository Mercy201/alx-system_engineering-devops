Shell permismission
"su betty" Command that switches the current user to the user betty
"whoami" Command that prints the effective username of the current user
"groups" command that prints all the groups the current user is part of
"chown betty hello" command that changes the owner of the file hello to the user betty
"touch hello" command that creates an empty file called hello
"chmod u+x hello" command that adds execute permission to the owner of the file hello
"chmod ug+x,o+r hello" Command that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
"chmod ugo+x hello" Command that adds execution permission to the owner, the group owner and the other users, to the file hello
"chmod 007 hello" Command that sets the permission to the file hello as follow:  Owner: no permission at al1,Group: no permission at all, and Other users: all the permissions
"chmod 753" Command that sets the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
"chmod --reference=olleh hello" command that sets the mode of the file hello the same as olleh’s mode
"chmod -R +X" Command that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
"mkdir -m 751 my_dir" Command that creates a directory called my_dir with permissions 751 in the working directory
