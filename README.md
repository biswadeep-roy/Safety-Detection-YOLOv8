# Safety Detection with YOLOv8

![Safety Detection YOLOv8] ![image](https://github.com/biswadeep-roy/Safety-Detection-YOLOv8/assets/74821633/e08d378f-9260-450b-8942-845651853d7d)


## Overview

Welcome to the Safety Detection YOLOv8 project! This initiative leverages YOLOv8, a cutting-edge object detection model, to enhance safety measures by identifying and classifying objects related to personal protective equipment (PPE). The primary objective is to ensure compliance with safety standards in various environments.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

Safety Detection YOLOv8 is an advanced computer vision project designed for real-time object detection. By employing YOLOv8, the model identifies various safety-related objects such as hardhats, masks, safety vests, and more..

## Features

- **Real-time Object Detection:** Leverage the power of YOLOv8 for rapid and accurate identification of safety-related objects.
- **Classified Compliance:** Categorize detected objects as compliant or non-compliant based on safety standards.
- **Customizable:** Easily adapt the model for different safety scenarios or extend the list of detectable objects.

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Python](https://www.python.org/) (version 3.6 or later)
- [Ultralytics YOLO](https://github.com/ultralytics/yolov8)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/biswadeep-roy/Safety-Detection-YOLOv8.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the pre-trained model file (`ppe.pt`) from the following link:

    [Download ppe.pt](https://drive.google.com/drive/folders/11tfTBkp4JdlJ8QXoAMZxgVMf8xpLBXi_?usp=sharing)

4. Place the downloaded `ppe.pt` file in the project's root directory.
   
## Usage

1. Confirm that your webcam or video source is accessible.
2. Run the main script:

    ```bash
    python safety_detection.py
    ```

3. Observe real-time safety detection results on the displayed video stream.

## Customization

To tailor the project to specific use cases or add new objects for detection, follow these steps:

1. Update the `classNames` list in the script with the desired object classes.
2. Fine-tune the YOLOv8 model on a dataset that includes the new classes.
3. Adjust confidence thresholds or color codes in the script according to your requirements.

## Results

![Demo Image](![image] ![image](https://github.com/biswadeep-roy/Safety-Detection-YOLOv8/assets/74821633/88d9b1a6-8dd8-4662-a2d9-2bfa0275c4fc)
)


_(Include images or GIFs showcasing the model's performance and compliance detection.)_

## Contributing

Contributions are welcomed! Please adhere to our [contribution guidelines](CONTRIBUTING.md) for a smooth collaboration.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the contributors of the Ultralytics YOLOv5 repository.
- Inspired by the necessity for improved safety measures in various environments.

