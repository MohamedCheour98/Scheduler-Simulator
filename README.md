# Scheduler-Simulator
A scheduler simulator that supports multiple scheduling algorithms, and computes the turnaround and wait times for each job submitted to the simulator.


The usage of the simulator is this:

schedSim <job-file.txt> -p <ALGORITHM> -q <QUANTUM>

  
- job-file.txt contains a list of job run and arrival times, given as a pair of integers, each on their own line.
- ALGORITHM is a string that defines the scheduling algorithm the simulator will use. Algorithms suported are: shortest-remaining job next, first-in first-out, and round-robin, selected by the arguments: SRTN, FIFO, and RR, respectively.
- QUANTUM is the length of time, given as an integer, when round-robin is used.
