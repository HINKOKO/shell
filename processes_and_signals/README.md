Script 0 display current PID running
Script 1 display all running processes, option a for all users, u for user-oriented format and x for TTY included,f option for displaying from parent to child processes
Script 2 display all currenttly running bash processes
Script 3 display PID, along with process name, those who contain the word "bash" 
Script 4 displays a message in tribute to Buzz Lightning, each iteration is separated by a time-sleeper of 2 seconds
Script 5 kills the process of infinite loop of script 4, using the kill command
Script 6 kill the infinite process of script 4 in an easier way than script 5 using pkill command
script 67 is used to kill and test the message from script 7
Script 7 is the infinite loop of script 4 but use the trap command to ignore the kill command and print a message instead
Script 8 kills the highlander script, using the kill command and -9 (kill a process)
Script 9 creates and > redirect the ouput of echo $$ (PID) in the file. trap SIGINT (^C) signal and display Y U no love me?! trap SIGTERM signal and display I hate the kill command, deletes the file when it traps SIGTERM and SIGQUIT signal
Script *"manage my process" creates an infinite loop who writes 'I am alive!' to the file /tmp:my_process* as to be used with init.script 11
Script 10 (init script) manages 'manage_my_process' (previous one in this README.md) with usage {start|stop|restart} 
