# PAMAP2 Dataset Visualization
This repository provides Python-based visualization of the PAMAP2 (Physical Activity Monitoring) dataset used for Human Activity Recognition (HAR).
The visualization scripts were developed as part of the research presented in:
**A Unified CNN-Based Compression Framework Using Pruning and Quantization for Efficient Human Activity Recognition in Edge Environments**
---
## Dataset Access
The dataset used in this work is publicly available at:
https://archive.ics.uci.edu/dataset/231/pamap2+physical+activity+monitoring
---
## Dataset Description
The PAMAP2 dataset contains wearable sensor recordings collected from 9 participants performing several physical activities.
Each record includes:
- Timestamp
- Heart Rate
- Hand IMU Sensor
- Chest IMU Sensor
- Ankle IMU Sensor
- Activity Label
Activities include:
- Lying
- Sitting
- Standing
- Walking
- Running
- Cycling
- Nordic Walking
- Ascending Stairs
- Descending Stairs
- Vacuum Cleaning
- Ironing
- Rope Jumping
---
## Repository Contents
```
README.md
LICENSE
.gitignore
pamap2_visualization.ipynb
```
---
## Features
This repository includes visualization of:
- Activity distribution
- Missing values
- Sensor signal plots
- Correlation heatmaps
- Activity-wise comparison
- Statistical summaries
---
## How to Run
Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scipy
```
Open the notebook:
```bash
jupyter notebook pamap2_visualization.ipynb
```
## License

This project is licensed under the MIT License.
