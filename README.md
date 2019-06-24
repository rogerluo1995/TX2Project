# EECE 597 Supervised Projecrt


## Author
Samuel Kwok, Roger Luo

## Introduction
There is a partitioning and scheduling problem in TensorFlow. The situation is more relavant to the embedded heterogeneous platform as there is a tighter constraints in cost, power, size, and weight - all of which leads to the need of clever designs of scheduling and work partition to make efficient use of the shared-memory system. 

This project aim to examine how the scheduling and work partition is done under the existing TensorFlow. Then we identify the opportunity and new approaches that can improve the existing work. 

## References
[1] Mayer et al: *The TensorFlow Partitioning and Scheduling Problem:
It’s the Critical Path!*