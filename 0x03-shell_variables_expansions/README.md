Read me file for Shell, init files, variables and expansions

Task 0: alias ls="rm *" > This create a script that creates an alias.
Task 1: echo "hello $USER" > This create a script that prints hello user, where user is the current Linux user.
Task 2: export PATH=$PATH:/action > This Add /action to the PATH. /action
Task 3: echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) > This create a script that counts the number of directories in the PATH.
Task 4: env >  This create a script that lists environment variables.
Task 5: set > This create a script that lists all local variables and environment variables, and functions
Task 6: BEST="SCHOOL" > This create a script that creates a new local variable
Task 7: export BEST="School" > This create a script that creates a new global variable
Task 8: echo "$((128 + $TRUEKNOWLEDGE))" > This script prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
Task 9: echo $(($POWER / $DIVIDE)) > This script prints the result of POWER divided by DIVIDE, followed by a new line.
Task 10: echo $(($BREATH**$LOVE)) > This script displays the result of BREATH to the power LOVE
Task 11: echo $((2#$BINARY)) > This script converts a number from base 2 to base 10
Task 12: echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" > This script prints all possible combinations of two letters, except oo.
Task 13: printf "%.2f\n" $NUM > This script prints a number with two decimal places, followed by a new line
Task 14: printf "%x\n" $DECIMAL > This script converts a number from base 10 to base 16.
Task 15: tr 'a-zA-Z' 'n-za-mN-ZA-M' > This script encodes and decodes text using the rot13 encryption. Assume ASCII.
Task 16: cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2 >    This script prints every other line from the input, starting with the first line.
Task 17: printf "%o\n" $((5#`echo $WATER | tr 'water' '01234'` + 5#`echo $STIR | tr 'stir.' '01234'`)) | tr '01234567' 'bestchol' >   This script adds the two numbers stored in the environment variables WATER and STIR and prints the result





