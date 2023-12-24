# Airport Counter Simulation 🛫

## A Two-server Single Queue Simulation

Completed as part of Simulation Lab assignment on 29 Sept '23 during the Autumn Semester 23-24.

### Problem Statement

As an analyst, the task was to construct a simulation model of an airline check-in counter featuring two staff members capable of processing check-in requests. The counter operates with a common queue for customers awaiting service. If both servers are busy, customers must wait in line until one server becomes available. The queue follows a First In First Out (FIFO) discipline, but with a twist: occasionally, priority passengers join the queue, and the airline policy mandates processing them before others. If multiple priority customers are present, they are processed ahead of regular customers but in FIFO order among themselves. At any given moment, there's a 10% chance that the next arriving customer is a priority customer.

### Simulation Details

The simulation involves running 100 customers by utilizing the Linear Congruential Generator (LCG) to generate random numbers as required. The distribution and characteristics mentioned earlier, including the decision on whether a customer is a priority customer, are determined using the LCG.

### Instructions

To run the simulation:

1. Implement the simulation using the provided guidelines.
2. Ensure the LCG generates random numbers appropriately.
3. Run the simulation for 100 customers, adhering to the distribution and data criteria specified.
