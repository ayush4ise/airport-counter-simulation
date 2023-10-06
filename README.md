## Airport Counter Simulation-  
### A Two-server Single Queue Simulation  

_(Done as part of Simulation Lab assignment [29 Sept' 23], Autumn Semester 23-24)_

*Problem Statement*-  
You are an analyst tasked with constructing a simulation model of an airline check-in counter. The check-in counter has two staff, each of whom can process a check-in request. There is a common queue of customers leading upto the servers. If both servers are busy, the customer has to wait in queue until one of the servers become free. The queue is processed with First In First Out (FIFO) discipline usually. However sometimes if priority passengers enter the queue the airline has a policy of processing them first. In case there are multiple priority customers in the queue, they shall be processed ahead of normal customers but in FIFO order among themselves. At any given instant of time, there is 10% chance the next arriving customer is a priority customer.  

Run the simulation for 100 customers by using the LCG to generate rando numbers whenever required and following the distribution and data mentioned earlier. The decision whether customer is a priority customer can also be generated using the LCG.