# The TensorFlow Partitioning and Scheduling Problem: It’s the Critical Path!

## Problem Identified
- No formal description of the TensorFlow partitioning and scheduling problem (no proof of the NP completeness)
- Current work focus on minimizing communication rather than reducing execution time (**what does it mean**: _existing scheduling approaches assume global scheduling decisions only rather than pushing scheduling logic to the devices_)

## Goal
- Minimizing execution time

## Contribution
- Proof of NP completeness
- Several partitioning and scheduling heuristics 
- Performance evaluations

- Identified the best partitioning scheduling are based on minimizing the **execution time** of the crtical path

## Good

## Bad

## Questions
- It's a design for distributed system. How do we shink this down to a single machine?
- No details about their implementation (source code)