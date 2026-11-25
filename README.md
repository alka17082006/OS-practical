# Operating Systems Lab (CEC301) - Practical File

B.Tech (CSE), Third Year. All programs are written in Python and are in `operating.ipynb`, one cell per program.

| # | Program |
|---|---------|
| 1 | Linux system calls, process creation using fork(), exec() and wait() |
| 2 | Thread creation and management (pthreads / threading) |
| 3 | CPU scheduling: FCFS, SJF, Priority, Round Robin |
| 4 | Producer-Consumer problem using semaphores |
| 5 | Readers-Writers problem using semaphores |
| 6 | Dining Philosophers problem using semaphores |
| 7 | Deadlock avoidance using Banker's Algorithm |
| 8 | Contiguous memory allocation: First Fit, Best Fit, Worst Fit |
| 9 | Page replacement: FIFO, LRU, Optimal |
| 10 | Disk scheduling: FCFS, SSTF, SCAN, C-SCAN |
| 11 | File allocation: Contiguous, Linked, Indexed |

## Contents
- `operating.ipynb` - all 11 programs with outputs
- `pdf/OS_Practical_File.pdf` - the formatted practical file
- `latex/` - LaTeX source and screenshots of the code and outputs

## Run
Program 1 uses `fork()`, so run the notebook on Linux, WSL or macOS.
```
pip install notebook
jupyter notebook operating.ipynb
```
