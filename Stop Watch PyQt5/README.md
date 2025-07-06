# PyQt5 Stopwatch Application

![Stop Watch](image.png)

A modern, customizable stopwatch application built with **Python** and **PyQt5**, featuring millisecond precision and a clean UI.  

---

## Features  
- **Start/Stop** functionality with **millisecond accuracy** (10ms precision)  
- **Reset** button to clear the timer  
- **Stylish UI** with custom styling:  
  - Large, easy-to-read display  
  - Responsive buttons  
  - Custom color scheme  
- **Time format**: `HH:MM:SS.MS` (e.g., `00:01:23.45`)  

---

## Installation  
1. Ensure you have **Python 3.6+** installed.  
2. Install the required package:  
   ```bash
   pip install PyQt5

## Usage
Run the application:
     python stopwatch.py

Controls
-Start: Begins the timer
-Stop: Pauses the timer
-Reset: Resets to 00:00:00.00

## How it workes
Uses PyQt5’s QTimer for precise timing.

Updates the display every 10 milliseconds for smooth rendering.