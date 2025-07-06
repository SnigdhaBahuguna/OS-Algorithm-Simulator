# OS Algorithm Simulator

A **Streamlit-based Operating System Algorithm Simulator** that helps users visualize and understand the inner workings of core OS algorithms including **CPU Scheduling**, **Memory Allocation**, and **Disk Scheduling** — with real-time **interactive UI and visualizations**.

---

##  Features

- **CPU Scheduling Algorithms**
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Shortest Remaining Time First (SRTF)
  - Priority Scheduling (Preemptive and Non-preemptive)
  - Round Robin

- **Memory Allocation Strategies**
  - First Fit
  - Best Fit
  - Worst Fit

- **Disk Scheduling Algorithms**
  - FCFS
  - SSTF
  - SCAN
  - C-SCAN
  - LOOK
  - C-LOOK

- Rich Visualizations:
  - Gantt Charts
  - Disk Movement Graphs
  - Memory Block Visualization
  - Dynamic process and block tables

-  Interactive UI with:
  - Real-time inputs
  - Auto-generated test cases
  - Metric cards (WT, TAT, RT, Fragmentation, Utilization)

---


##  Tech Stack

- **Frontend**: Streamlit
- **Backend Logic**: Python
- **Libraries**:  
  - `matplotlib` (charts)  
  - `pandas` (tables & data handling)  
  - `random` (auto test case generation)

---

##  How to Run

```bash


# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the app
streamlit run app.py
