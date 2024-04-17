# FCFS
<ins>_**Experiment name:**_</ins> Implementation of the First Come First Serve (FCFS)  Algorithm.

<ins>_**Description:**_</ins> The code implements the First Come, First Serve (FCFS) scheduling algorithm for process scheduling. This algorithm schedules processes according to their arrival time and executes them in the order they arrive. Initially, the code creates arrays to store process IDs, burst times, and wait times for up to 15 processes. The user is prompted to enter the number of processes, along with their process IDs and burst times.Next, the waiting time for each process is computed. The waiting time for the first process is set to 0, while for subsequent processes, the formula is used: waiting_time[i] = burst_time[i-1] + waiting_time[i-1]. After calculating the waiting times, the code displays a table with the process ID, burst time, waiting time, and turnaround time (the sum of burst and waiting time) for each process.To calculate the average waiting time and turnaround time, the code adds the waiting and turnaround times for all processes. The averages are then determined by dividing the totals by the number of processes. Finally, the program outputs the average waiting time and average turnaround.

:**_</ins>Input:**_</ins>
The required input for this code includes the following steps: 
-The number of processes:The user must specify the total number of processes they want to schedule. This value must be an integer between 1 and 15, inclusive.

-process Id’s: After entering the number of processes, the user is asked to enter process IDs for each one. Process Id’s are integers that are unique to each process. 

-Burst times: Finally, the user is prompted to enter burst times for each process. Burst time is the amount of time required for a process to complete its execution.


:**_</ins>Output:**_</ins>
The output of the provided the First Come First Serve (FCFS) algorithm will display the turnaround time and waiting time for each process  and the final result:

