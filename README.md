# 🖥️ CPU Scheduler Simulator

A powerful, interactive CPU scheduling algorithm simulator built with Python and Tkinter.

![Python](https://img.shields.io/badge/python-3.6+-blue.svg) ![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg) ![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)

## 📋 Overview

This application provides an intuitive and interactive way to visualize and analyze different CPU scheduling algorithms. It features real-time process execution visualization, performance metrics, and a user-friendly GUI to enhance learning and experimentation.

## ✨ Features

- **Supports Multiple Scheduling Algorithms**:
  - 🏁 First-Come-First-Serve (FCFS)
  - ⏳ Shortest Job First (SJF)
  - 🔄 Shortest Remaining Time First (SRTF)
  - 🔄 Round Robin (Configurable time quantum)
  - 🏆 Priority Scheduling

- **Interactive Process Management**:
  - Add custom processes with unique parameters (PID, Arrival Time, Burst Time, Priority)
  - Modify, delete, or reset processes dynamically
  - Real-time process table updates

- **Visual Process Execution**:
  - Color-coded Gantt chart for clear process execution visualization
  - Live updates for a smooth experience

- **Comprehensive Performance Metrics**:
  - 🕒 Average Waiting Time
  - ⏳ Average Turnaround Time
  - ⚡ CPU Utilization Percentage
  - 📈 Process Throughput
  - 📊 Detailed per-process statistics

## 🚀 Installation & Setup

### Prerequisites
- Python 3.6+
- Required Libraries: `tkinter`, `ttkbootstrap`, `matplotlib`

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/tabishfarhan7/cpuScheduler.git
   cd cpuScheduler
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python cpuscheduler.py
   ```

## 🛠️ How to Use

1. **Adding Processes**:
   - Enter the Process ID, Arrival Time, Burst Time, and Priority.
   - Click "Add Process" to include it in the process table.

2. **Choosing a Scheduling Algorithm**:
   - Select from the dropdown menu (FCFS, SJF, SRTF, Round Robin, Priority).
   - If Round Robin is selected, specify the Time Quantum.

3. **Executing the Scheduler**:
   - Click "Run Scheduler" to start the process execution.
   - View the real-time Gantt chart and detailed performance metrics.

4. **Managing Processes**:
   - Select a process and click "Delete" to remove it.
   - Click "Reset" to clear all process entries.

## 🧠 Understanding the Algorithms

| Algorithm | Type | Preemptive | Description |
|-----------|------|------------|-------------|
| **FCFS** | Non-Preemptive | ❌ | Executes processes in order of arrival. |
| **SJF** | Non-Preemptive | ❌ | Prioritizes the shortest job first. |
| **SRTF** | Preemptive | ✅ | Shortest remaining time first (preemptive SJF). |
| **Round Robin** | Preemptive | ✅ | Allocates CPU time in equal time slices (time quantum). |
| **Priority Scheduling** | Non-Preemptive | ❌ | Processes are scheduled based on priority values. |

## 📊 Performance Metrics

- **Average Waiting Time**: Time a process spends waiting before execution.
- **Average Turnaround Time**: Total time taken for a process from arrival to completion.
- **CPU Utilization**: Percentage of time the CPU is actively processing.
- **Throughput**: Number of processes completed per unit time.

## 📸 Screenshots

_A simple Round-Robin Scheduling algorithm-based Gantt chart along with performance metrics._

![Gantt Chart Placeholder](https://github.com/tabishfarhan7/CPU-Scheduler-Simulator/blob/main/assets/scheduler.png)

## 🔜 Future Enhancements

- 🏗️ Improved modular code structure
- 🏆 Additional scheduling algorithms (MFQ, Lottery Scheduling)
- 📤 Export feature for results and performance metrics
- 🎥 Animated process execution
- 📂 Batch process import/generation

## 🤝 Contributions

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/NewFeature`).
3. Commit changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/NewFeature`).
5. Open a Pull Request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 📞 Contact

📌 **Author**: Tabish Farhan - [@tabishfarhan7](https://github.com/tabishfarhan7)

🔗 **Project Link**: [CPU Scheduler Simulator](https://github.com/tabishfarhan7/cpuScheduler)

