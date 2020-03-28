# OSProject
Design a scheduling program to implement a queue with two levels:
Level 1: Fixed priority preemptive scheduling
Level 2: Round Robin Scheduling
For a fixed priority preemptive scheduling(Queue 1), the priority 0 is the highest priority. If
one process P1 is scheduled and running, another process P2 with higher priority comes.The new process 
(Higher priority) process P2 preempts currently running process P1 and Process P1 will go to second level
queue. Time for which process will strictly execute must be considered in multiples of 2.

All the processes in second level queueill complete their execution according to round robin scheduling.

Consider:
1. Queue 2 will be processed after Queue 1 becomes empty.
2. Priority of Queue 2 has lower priority than in Queue 1.
