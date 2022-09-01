Shell, permissions Tasks

Task 0: su betty = This switches the current user to the user betty 
Task 1: whoami =   This prints the effective username of the current user.
Task 2: groups =   This prints all the groups the current user is part of
Task 3: chown betty helo = This changes the owner of the file hello to the user betty
Task 4: touch hello = This creates an empty file called hello
Task 5: chmod u+x hello = This adds execute permission to the owner of the file hello.
Task 6: chmod ug+x,o+r hello = This adds execute permission to the owner and the group owner, and read permission
to other users, to the file hello.
Task 7: chmod a+x hello = This adds execution permission to the owner, the group owner and the other users, to the file hello
Task 8: chmod 007 hello = This sets the permission to the file hello and other permissions
Task 9: chmod 753 hello = This sets the mode of the file hello
Task 10:chmod --reference=olleh hello =  This sets the mode of the file hello the same as olleh’s mode.
Task 11: chmod a+X * = This adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Task 12: mkdir -m 751 = This creates a directory called my_dir with permissions 751 in the working directory.
Task 13: chgrp school hello = This changes the group owner to school for the file hello
Task 14: chown vincent:staff * = This changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
Task 15: chown -h vincent:staff _hello = This changes the owner and the group owner of _hello to vincent and staff
Task 16: chown --from=guillaume betty hello = This changes the owner of the file hello to betty only if it is owned by the user guillaume.
Task 17: telnet towel.blinkenlights.nl = This play the StarWars IV episode in the terminal, is an already made scrip.




