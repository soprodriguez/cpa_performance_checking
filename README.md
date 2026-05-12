# System Performance Monitor (Python)

## Description

This project is a simple Python script that monitors system performance by displaying CPU and memory (RAM) usage. It uses the `psutil` library to retrieve real-time system data and prints the results in the console.

This project is useful for understanding how to access system-level information using Python.

## Features

* Display CPU usage percentage
* Display memory (RAM) usage percentage
* Real-time system monitoring
* Lightweight and easy-to-run script

## Technologies Used

* **Python**
* **psutil** (for accessing system performance data)

## Requirements

* Python installed on your system
* psutil

## Installation

Install the required library using pip:

```id="sys123"
pip install psutil
```

## How to Run the Program

1. Save the code in a Python file (e.g., `system_monitor.py`).
2. Open your terminal or IDE.
3. Run the program:

   ```
   python system_monitor.py
   ```
4. The system’s CPU and memory usage will be displayed in the console.

## Example Output

```
CPU Usage: 25%
Memory Usage: 60%
```

## Notes

* The program uses `psutil.cpu_percent()` to measure CPU usage.
* `psutil.virtual_memory()` is used to retrieve memory usage details.
* This project is useful for beginners learning system monitoring and working with external libraries in Python.

## Future Improvements

* Add disk usage monitoring
* Create a GUI version
* Display real-time updating graphs
* Log system performance over time
