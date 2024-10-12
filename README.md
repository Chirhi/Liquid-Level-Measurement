# Liquid Fertilizer Lagoon Level Detection

This project uses YOLO11 to detect and measure liquid fertilizer levels in lagoons. It's designed to automate the process of monitoring fertilizer levels, improving efficiency in agricultural operations.

Currently project only has .ipynb files for demonstrating purposes:
- liquid_level_neural_polygon.ipynb uses object detection neural network for measurement
- liquid_level_neural.ipynb is unfinished example on how measurement can be done with image preprocessing without any machine or deep learning

## Features

- Detects fence and liquid levels in fertilizer tanks and measure free space between them
- Uses polygonal annotations for precise measurements
- Trained on a small bunch of self-annotated images of liquid fertilizer lagoon

## Prerequisites

- Python 3.10.*

## Setup Instructions on Windows

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/liquid-fertilizer-level-detection.git
   cd liquid-fertilizer-level-detection
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Place your YOLO11 format dataset in the `datasets/` directory

4. Run the liquid_level_neural_polygon.ipynb notebook cell per cell, except training cell

## Results

![image](https://github.com/user-attachments/assets/793e99ae-62f0-4416-85b5-fbedb2b84783)

