C Programming! Hello, World.


Task 0: echo Hello, World >  This write and prints “Hello, World”, followed by a new line to the standard output.
Task 1: echo "\"(Ôo)'" > This write a script that displays a confused smiley "(Ôo)'.
Task 2: cat /etc/passwd > This display the content of the /etc/passwd file.
Task 3: cat /etc/passwd /etc/hosts > This display the content of /etc/passwd and /etc/hosts
Task 4: tail /etc/passwd > This display the last 10 lines of /etc/passwd
Task 5: head /etc/passwd > This display the first 10 lines of /etc/passwd
Task 6: head --lines=3 iacta | tail --lines=1 > This write a script that displays the third line of the file iacta
Task 7:echo "Holberton School" > "\*\\\'\"Holberton School\"\'\\\*$\?\*\*\*\*\*:)" >  This write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
Task 8: ls -la > ls_cwd_content > This write a script that writes into the file ls_cwd_content the result of the command ls -la.
Task 9: echo -en "" | tail --lines=1 iacta >> iacta > This write a script that duplicates the last line of the file iacta
Task 10: find . -name '*.js' -type f -delete > This write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
Task 11: find -mindepth 1 -type d | wc -l > This write a script that counts the number of directories and sub-directories in the current directory.
Task 12: ls -t | head > This create a script that displays the 10 newest files in the current directory.
Task 13:  sort | uniq -u > This create a script that takes a list of words as input and prints only words that appear exactly once.
Task 14: grep -i root /etc/passwd > This display lines containing the pattern “root” from the file /etc/passwd
Task 15: grep -i bin /etc/passwd | wc -l > This display the number of lines that contain the pattern “bin” in the file /etc/passwd
Task 16: grep -iA 3 root /etc/passwd > This display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
Task 17: grep -iv bin /etc/passwd > This display  all the lines in the file /etc/passwd that do not contain the pattern “bin”.
Task 18: grep -i "^[a-z]" /etc/ssh/sshd_config > This display all lines of the file /etc/ssh/sshd_config starting with a letter.
Task 19: tr Ac Ze > This replace all characters A and c from input to Z and e respectively.
Task 20: tr -d cC > This create a script that removes all letters c and C from input.
Task 21: rev > This write a script that reverse its input.
Task 22: cut -d':' -f1,6 /etc/passwd | sort >  This write a script that displays all users and their home directories, sorted by users.
Task 23: find . -empty -printf "%f\n" > This write a command that finds all empty files and directories in the current directory and all sub-directories.
Task 24: find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f > This write a script that lists all the files with a .gif extension in the current directory and all its sub-directories
Task 25: cut -c 1 | paste -s -d '' >  This create a script that decodes acrostics that use the first letter of each line
Task 26: tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev >  This write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
