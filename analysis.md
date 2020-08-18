# Introduction
The algorithm that we had choose is Pre-emptive Shortest Job First(SJF) Scheduling and ALGO 3. 

# Consideration

The main factor that we had considered when choosing the algorithm is the arrival time. As not all process has the same arrival time, some process who have shorter burst time will have to wait for current process to finish which lead to resource starvation. this is the same as class scheduling. as not all student may access the portal in the same time, there may be some student who need to wait for current user to finish registering assuming non pr-emptive SJF is used. by using pre-emptive SJF, this problem is solved by using the concepy of aging, moving the current process that have longer burst time into queue while program with shorter burst time executed first. ALGO 3

# Analysis

Analysis
FCFS
Given n course processes with their burst times and arrival times, the task is to find average waiting time and average turn around time using FCFS scheduling algorithm. FIFO simply queues processes in the order they arrive in the ready queue. Here, the process that comes first will be executed first and next process will start only after the previous gets fully executed.

Algo2 (SJF)
Start scheduler selects the process from the waiting queue with the least completion time. Shortest course duration First is more desirable than FIFO algorithm because SJF is more optimal as it reduces average wait time which will increase the throughput. This algorithm will consider with the arrival time unlike FCFS and priority scheduling.

Stop

Algo3 (priority shceduling)
Priority scheduling is an unprotected algorithm and one of the most common scheduling algorithms in batch systems. Each process is scheduled for its first arrival. (Arrival steps less than before) If two processes have the same arrival time, compare with the priority. (Top Process First) Also, if two processes have the same priority, compare them with process numbers. (Less than previous process number)

This algorithm consider the importance of course unlike FCFS and SJF.
