# os-project
started at 1/04/2020 

***Multilevel queue scheduling :- ***

 In this algorithm processes are divided set into
multiple queues based on their priority.Each queue has absolute priority over
lower-priority queues.

For example -There are three queues generated having a specific range of priority to
every queue.User enter number of processes along with their priority and burst
time.Each processes occupy the respective queue with specific priorioty range
according to its priority.Now high priority queue should use the Round Robin
algorithm with time quantum 4 seconds, medium priority queue should use priority
sheduling,low priority queue should use FCFS algorithm.Each and every queue
should get a time quantum of 10 seconds.CPU will keep shifting between queues
after every 10 seconds. Then calculate waiting time and turn around time for every process.
