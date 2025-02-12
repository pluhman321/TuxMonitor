# TuxMonitor

TuxMonitor is a lightweight, real-time system resource monitoring tool built in Python. It provides a modern, clean interface for tracking CPU, memory, and network usage, and logs the usage data to a CSV file for further analysis. The tool features a live-updating network usage graph with an Apple-inspired aesthetic, making it ideal for users who want an attractive yet functional resource monitor.

## Features

- **Real-Time Monitoring:**  
  Continuously tracks and displays CPU usage, memory consumption, and network data transfer in real time.

- **Modern User Interface:**  
  Built using Tkinter with a sleek dark theme and modern typography (e.g., San Francisco font), the interface provides both textual readouts and visual progress bars.

- **Live Network Graph:**  
  Integrates a live-updating network usage chart using matplotlib, which shows network activity over the last 60 seconds.
## Requirements

- Python 3.x
- [psutil](https://pypi.org/project/psutil/)
- Tkinter (typically included with Python)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [numpy](https://pypi.org/project/numpy/)
