# Minimum Landing Pads Scheduler

This project solves a scheduling problem inspired by a spaceport scenario: determining the minimum number of landing pads required so no spaceship has to wait. Given a list of landing and departure times, the goal is to calculate peak pad usage using three algorithmic approaches — Brute Force, Greedy, and Divide & Conquer.

Each solution includes:
- Pseudocode and Python implementation
- Test drivers with sample inputs
- Execution time benchmarking and complexity analysis

**Approaches Implemented:**
- **Brute Force**: Iterates minute-by-minute and checks overlaps; O(n × 2401)
- **Greedy**: Sorts landing/departure times and sweeps through them efficiently; O(n log n)
- **Divide and Conquer**: Recursively splits event windows to track peak pad usage; O(n log n)

To run the project, open the Jupyter notebook and execute each cell in sequence. All dependencies are standard and included in Google Colab.

This repository is ideal for comparing algorithm efficiency and correctness in interval scheduling problems. Insights into performance scaling across input sizes are included at the end of the notebook.
