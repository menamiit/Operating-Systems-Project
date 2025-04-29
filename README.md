# CPU Scheduling Simulator

This is a Python-based GUI application that simulates several CPU scheduling algorithms. It allows users to input processes, select a scheduling algorithm, and visualize the scheduling with a Gantt chart and performance metrics.

## Features

- **Supported Scheduling Algorithms**:
  - First-Come First-Served (FCFS)
  - Shortest Job First (SJF) - Non-preemptive
  - Priority Scheduling
  - Round Robin (with configurable quantum)

- **User Interface**:
  - Add multiple processes with custom Arrival Time, Burst Time, and Priority.
  - Dynamically shows/hides priority and quantum fields based on the selected algorithm.
  - Displays a Gantt Chart of the execution timeline using `matplotlib`.
  - Shows individual Waiting Time and Turnaround Time per process.
  - Computes and displays Average Waiting Time and Average Turnaround Time.

## Prerequisites

- Python 3.x
- `matplotlib`
- `tkinter` (usually included with Python)

You can install `matplotlib` using pip:

```bash
pip install matplotlib
