# Introduction
The algorithm that we had choose is Pre-emptive Shortest Job First(SJF) Scheduling and ALGO 3. 

# Consideration

The main factor that we had considered when choosing the algorithm is the arrival time. As not all process has the same arrival time, some process who have shorter burst time will have to wait for current process to finish which lead to resource starvation. this is the same as class scheduling. as not all student may access the portal in the same time, there may be some student who need to wait for current user to finish registering assuming non pr-emptive SJF is used. by using pre-emptive SJF, this problem is solved by using the concepy of aging, moving the current process that have longer burst time into queue while program with shorter burst time executed first. ALGO 3

# Analysis

## FCFS

The FCFS algorithm use a concept where the process that arrive first are executed first. as it is a non pre-emptive algorithm, the burst time of the process are not taken into consideration. this may lead to resource starvation and increased computing time. if this algorithm is implemented into the class scheduling process, not only will there be some sort of congestion in fulfilling the request but also an increase in overall registration process. FCFS also has a very high waiting time and turn around time. 

##  Pre-emptive Shortest Job First(SJF)

 Pre-emptive SJF work according to the process burst time, with one with the fastest are executed first. as it take the burst time into consideration the waiting time and turn around time are significantly lower. The concept of 'aging' not only solve the resource starvation problem but also reduce the total  computing time. However another problem also arise as the pre-emptive SJF need the burst time of the processes to be known in advance. this may be viable in real life as we cannot determine a student's registration time in advance.

## Priority Scheduling

Priority scheduling is a non-preemptive algorithm and one of the most common scheduling algorithms in batch systems.
Each process is assigned a priority. Process with highest priority is to be executed first and so on.
Processes with same priority are executed on first come first served basis. Therefore, as an example, the senior undergraduate level will be priority to register in the student's registration system first until the junior undergraduate level.
However, a second scheduling algorithm is required to schedule the processes which have same priority.
In preemptive priority scheduling, a higher priority process can execute ahead of an already executing lower priority process. If lower priority process keeps waiting for higher priority processes, starvation occurs.
