# CPSC351Assignment2
Assignment 2 for CPSC 351

Section #2

Programming Language: C


Team Members & Contributions:

Tyler Groom tjgroom@csu.fullerton.edu

Anthony Berton acberton1@csu.fullerton.edu

Titus Sudarno sudarno08@csu.fullerton.edu

Thomas-James Le tjle@csu.fullerton.edu


How the program works:
First the main function prompts the user to enter the required inputs; the memory size, page size and the path of the file. It then sets
up the process queue and framelist, then calls the mainloop function. In mainloop, a while loop is created which increments the current
time by one then terminates when the time exceeds the maximum amount of time. During each loop, three actions occur; new processes are
added to the queue, completed processes are terminated, and available memory is assigned if necessary. Once the loop has finished, the
average turn around time is printed. The process file contains the following information; the process ID, the arrival time, memory 
requirements, the life time, the time added, whether or not the process is active, and the time the process finishes. The queue file
enables processes to be added or removed from a process queue. The memory file creates a memory map which is implemented as a frame 
list.
