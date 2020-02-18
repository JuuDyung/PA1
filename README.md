# PA1

3) Description and discussion on the behavior of the whatIf program

The whatIf program which takes input from what the user types into the keyboard until the user hits a “ctl+d”. After whatIf ends, the child.txt and parent.txt are made that the output of the whatIf program gets into each file. That means that the parent will output what it gets into a file called parent.txt one line at a time and the child’s output goes to a file called child.txt. In this program, first it checks whether the argument is only one or not. Then, if the argument is more than one, it checks the input file exist or not. After that, it forks and then checks whether the fork gets error or not. Finally, the output goes to each process; child and parent.
