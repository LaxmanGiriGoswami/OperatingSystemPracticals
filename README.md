# OperatingSystemPracticals

Practical-1
ABOUT
/*  the SRTF algorithm involves more overheads than the Shortest job first (SJF)scheduling, because in SRTF OS is required frequently in order to monitor the CPU time of the jobs in the READY queue and to perform context switching.

In the SRTF scheduling algorithm, the execution of any process can be stopped after a certain amount of time. On arrival of every process, the short-term scheduler schedules those processes from the list of available processes & running processes that have the least remaining burst time.

After all the processes are available in the ready queue, then, No preemption will be done and then the algorithm will work the same as SJF scheduling. In the Process Control Block, the context of the process is saved, when the process is removed from the execution and when the next process is scheduled. The PCB is accessed on the next execution of this process.*/


Practical-2
ABOUT
/*  
	 variable pid will store the value returned from fork() system call .If fork() returns zero then it means it is child process.First child needs to be printed later hence this process is made to sleep for 3 seconds. This is first child process getpid() gives the process id and getppid() gives the parent id of that process. This is third child which is needed to be printed first. If value returned from fork() in not zero and >0 that means this is parent process. This is asked to be printed at last hence made to sleep for 3 seconds.
*/
