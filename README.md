# scheduling-algorithm-with-dynamic-quantum-time
Optimization of the Existing Round robin approach
Proposed Algorithm:
1. Take the burst time and priority of the processes and calculate the new priority rank by using 50% of
priority and 50% of rank according to burst time.
2. Arrange the processes according to the calculated rank.
3. Now we calculate the smart time quanta(STQ) by the formula:
4. Mean of all burst time + 0.5*SD of burst time
5. Now start executing the processes by round robin algorithm with STQ time quanta.
6. If a process is not finished in one go, we add the process to the other wait queue.
7. Now after all the processes are over in our executing queue, we execute all the processes in the waiting
queue.
