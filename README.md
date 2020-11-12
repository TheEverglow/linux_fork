# linux_fork
This task simply shows how many processes on Linux are created by the fork() method depending on the number of calls to it. 
The default is set to 3 times the fork method is called in a loop.

If you want to see the result of the work, you need to do the following on your Linux (or Linux remote console):
 1) Create a file using Nano GUI by 'nano test.c' (or any name you like)
 2) Paste the code from this repository contained in the file "ex1_fork.c" into your created file.
 3) Save the file using Linux tools and hotkeys (I'm sure you know how to do this)
 4) Compile your file by 'gcc test.c -o test' command
 5) Run the compiled file 'test' by using './test'

Try to catch the time to call the 'pstree' command to see how many processes have been created.

For example, experiment with a call number from 1 to 6, and you will find that the number of processes (including the parent process) will be a power of 2.
