# Disk-Scheduling
Ai based Disk scheduling program where algos are compared for disk scheduling.

This python code helps in comparing different algorithms for disk scheduling like:

- FCFS (First Come First Serve)
- SSTF (Shortest Seek Time First)
- SCAN
- Genetic Algorithm

It tells how much head movement is required by each scheduling algorithms and at the end suggests the best out of them.

Working:

1. User enters a list of disk requests (like 98, 183, 37, etc.).
2. User enters the starting position of the disk head (like 53).
3. The program runs the following algorithms:
   - FCFS: Serves requests in the given order.
   - SSTF: Picks the nearest request to the current head position.
   - SCAN: Moves in one direction, serves all requests, then reverses.
   - Genetic Algorithm: Uses AI to find an optimized order.
4. It prints:
   - The order of requests served.
   - The total head movement for each algorithm.
   - The best algorithm (with the least total head movement).
5. A graph is displayed to show how each algorithm performs.

Requirements:

Make sure Python is installed on your system.

You also need:
- matplotlib
- numpy

You can install them by running:
pip install matplotlib numpy


How to Run:

Run the script by using the command:
python disk_scheduler.py

Then, enter:
Enter disk requests separated by spaces: 98 183 37 122 14 124 65 67  
Enter initial head position: 53


Example Output:

FCFS Sequence: 98 -> 183 -> 37 -> ...
Total Head Movement (FCFS): 640

SSTF Sequence: 65 -> 67 -> 37 -> ...
Total Head Movement (SSTF): 236

...

Recommended Algorithm: SSTF (Least Total Head Movement)

A graph will be shown comparing the performance of all algorithms.


Author Notes:

This project is helpful for understanding how disk scheduling works 
and how AI (Genetic Algorithm) can improve system performance.
