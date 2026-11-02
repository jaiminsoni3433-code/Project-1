# Project-1
# Priority Task Scheduler (Binary Heap)

A lightweight, browser-based priority task scheduler built with HTML, CSS, and vanilla JavaScript. Tasks are managed using a **binary min-heap**, so the most urgent task is always executed first.

## Features
- Add tasks with a name, priority (higher = more urgent), and burst duration
- Heap-based scheduling with O(log n) insert and extract operations
- Stable ordering: tasks with equal priority run in the order they were added (FIFO)
- Execution console that shows the order in which tasks run
