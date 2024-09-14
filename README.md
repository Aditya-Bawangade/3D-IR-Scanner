# 3D IR Scanner using Arduino

## Overview

This project focuses on building a **3D IR Scanner** using **Arduino Uno** and **Optical Infrared Sensors**. The scanner efficiently acquires precise **3D point clouds** for small objects, generating over **2500 points** per scan. This low-cost, scalable solution integrates hardware and software for 3D scanning and visualization.

<div align="center">
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c5c9a226-0ecc-4ea5-ab6c-1ccd801cba98" alt="Experiment setup" width="300px" height="auto"/>
      <br>
      <b>Experiment setup</b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/25e00033-6e1c-44b3-a231-23e1f3022a43" alt="PointCloud of the dental imprint" width="300px" height="auto"/>
      <br>
      <b>PointCloud of the dental imprint</b>
    </td>
  </tr>
</table>
</div>
## Features

- **High-Precision Scanning**: The scanner collects **2500+ 3D points** per scan, enabling detailed 3D point clouds of small objects.
- **Custom Hardware Design**: Built using **10+ components**, including **Optical IR Sensors**, **Stepper Motors**, and **Arduino Uno**.
- **Motor Control**: The stepper motors are fine-tuned for optimized object positioning based on predefined geometries, ensuring accurate and repeatable scans.
- **Portable & Cost-Effective**: The scanner is designed to be easily replicable and cost-effective, making it accessible for hobbyists, researchers, and makers.

## Components

- **Arduino Uno**
- **Optical Infrared Sensors**
- **Stepper Motors** (for precise movement)
- **Power Supply**
- Various resistors, capacitors, and wiring (total of 10+ components)

## How It Works

1. **Setup**: The object is placed on the platform of the scanner.
2. **Motor Movement**: The **Stepper Motors** adjust the position of the object in small increments, based on a geometric scan path.
3. **Data Collection**: The **Optical Infrared Sensors** collect distance data from multiple angles as the object moves, creating a 3D map of its surface.
4. **Point Cloud Generation**: The distance data is processed into a **3D point cloud** with over 2500 points, accurately representing the object's shape.
5. **Data Export**: The collected data can be exported for further 3D processing or visualization, such as in 3D modeling software.
