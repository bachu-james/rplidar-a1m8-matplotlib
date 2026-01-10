# RPLIDAR A1M8 Polar Visualization (Raspberry Pi + Ubuntu)

This project visualizes **RPLIDAR A1M8** scan data in real time using **Python and matplotlib**
on a **Raspberry Pi running Ubuntu**, without using ROS.

## 🔧 Hardware
- RPLIDAR A1M8
- Raspberry Pi
- USB connection

## 💻 Software
- Ubuntu (ARM)
- Python 3
- matplotlib, pyserial, rplidar

## ✨ Features
- Reads raw LiDAR angle and distance data
- Polar plot visualization
- Live scan refresh per revolution
- Clean shutdown handling

## ▶️ Demo
![LiDAR Running](demo/lidar_running.jpg)

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/rplidar-a1m8-matplotlib.git
cd rplidar-a1m8-matplotlib
pip3 install -r requirements.txt
python3 src/lidar_polar_plot.py
