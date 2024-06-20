# Marine-Growth-Detection

This repository contains code and instructions for detecting marine growth using YOLOv5 and YOLOv8 models. Additionally, it includes depth detection based on the results from these models.

## Table of Contents
- [Marine Growth Detection](#marine-growth-detection)
  - [Project Structure](#project-structure)
  - [Usage](#usage)
    - [YOLOv5](#yolov5)
      - [Training and Inference](#training-and-inference)
      - [Depth Detection](#depth-detection)
    - [YOLOv8](#yolov8)
      - [Training and Inference](#training-and-inference-1)
      - [Depth Detection](#depth-detection-1)

## Project Structure

- `Final_code_yolov8.ipynb`: Executed code of the YOLOv8 models
- `yolov5_commands.txt`: List of commands executed in the command terminal to get the YOLOv5 results
- `marine_growth_depth_yolov5.ipynb`: Code for depth detection using the best results from YOLOv5
- `marine_growth_depth_yolov8.ipynb`: Code for depth detection using the best results from YOLOv8
- `README.md`: Project readme file

## Usage

### YOLOv5

#### Training and Inference
1. Follow the commands listed in `yolov5_commands.txt` to train and infer using YOLOv5. These commands can be run in the terminal.

#### Depth Detection
- Run `marine_growth_depth_yolov5.ipynb` to perform depth detection using the best results from YOLOv5.

### YOLOv8

#### Training and Inference
- Execute the code in `Final_code_yolov8.ipynb` to train and perform inference using YOLOv8.

#### Depth Detection
- Run `marine_growth_depth_yolov8.ipynb` to perform depth detection using the best results from YOLOv8.
