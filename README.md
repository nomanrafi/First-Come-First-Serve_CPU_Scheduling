# FSFC_CPU_Scheduling
FCFS CPU Scheduling Algorithm: This repository implements the First-Come, First-Served (FCFS) CPU Scheduling algorithm, which allocates CPU to processes based on arrival order, executing each sequentially without preemption. Simple yet prone to the "convoy effect," where shorter tasks wait behind longer ones.

Features:
- Process Queue Simulation: Simulate processes arriving at different times with various burst times.
- Gantt Chart Visualization: Visualize the scheduling order and time allocation for each process.
- Performance Metrics: Calculate and display key metrics like average waiting time and turnaround time.
- Python Implementation: A clean and modular Python codebase that can be easily understood and expanded.

Getting Started:
To use the FCFS scheduler:
- Clone this repository
- Add your own list of processes with arrival and burst times
- Run the scheduler and view the Gantt chart along with performance metrics.

Future Improvements
- Adding support for other scheduling algorithms (e.g., SJF, Round Robin).
- Interactive CLI/GUI for process input and scheduling visualization. 
