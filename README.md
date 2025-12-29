### Scheduler

This repository contains a small task scheduler that I built iteratively to explore how different algorithmic strategies affect scheduling quality, flexibility, and performance.

The project is implemented in Python and uses custom data structures to manage task priorities, dependencies, and time constraints. The code evolved across two versions, with the second addressing limitations discovered in the first.

### Project Overview

The scheduler takes a set of tasks, where each task may have:
- a duration
- dependencies on other tasks
- an optional fixed start time

The goal is to produce a feasible schedule that:
- respects all dependencies
- executes fixed-time tasks at their exact times
- uses remaining time efficiently by prioritizing flexible tasks

### Files

- scheduler_v1.ipynb - heap-based scheduler
- scheduler_v2.ipynb - dynamic programming scheduler
The implementation emphasizes clarity and correctness over UI or external integration.
