# cmsc-125-lab2-CPU-scheduling

#   CPU Scheduler Simulator

An CPU scheduler simulator developed for lab2 requirement of the course, CMSC 125 - Operating Systems. 

# Group Members
  * Eleah Joy Melchor
  * Jasmine Magadan

## PR1
* **Problem Analysis:** 
  * 

* **Timeline:**
  * Week 1 (Feb 26 - Mar 5): 
      * finalize architecture
      * finalize program flow
      * decide and justify MLFQ design

  * Week 2 (Mar 6 - Mar 12): 
      * initial algorithm
      * tests  for algorithm 

  * Week 3 (Mar 13 - Mar 19):
      * polished prototype
      * documentation of issues

  * Week 4 (Mar 23): 
      * program defense
      * finalize readme file
      * submit lab2 deliverables  

## PROJECT STRUCTURE
```bash
schedsim/
|-- Makefile
|-- README.md
|-- include/
|   |-- process.h           # Process data structures
|   |-- scheduler.h         # Scheduler interfaces
|   |-- metrics.h           # Metrics calculation
|   +-- gantt.h             # Gantt chart generation
|-- src/
|   |-- main.c              # CLI and main loop
|   |-- process.c           # Process management
|   |-- fcfs.c              # FCFS implementation
|   |-- sjf.c               # SJF implementation
|   |-- stcf.c              # STCF implementation
|   |-- rr.c                # Round Robin implementation
|   |-- mlfq.c              # MLFQ implementation
|   |-- metrics.c           # Metrics calculation
|   |-- gantt.c             # Gantt chart rendering
|   +-- utils.c             # Utility functions
|-- tests/
|   |-- workload1.txt       # Test workloads
|   |-- workload2.txt
|   +-- test_suite.sh       # Automated test script
+-- docs/
    +-- mlfq_design.md      # Your MLFQ design justification
```


## Features 


### Prerequisites



## Known Bugs & Limitations


## Development
Development Period : March 3 - 

This lab is written in C and interfaces directly with UNIX syscalls.



