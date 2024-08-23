# Object Detection with YOLOv10 on Rock 🪨, Paper 📃, Scissors ✂️ Dataset   

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains a Jupyter notebook. It demonstrates the process of training and evaluating a YOLOv10 model for object detection using the [Rock, Paper, Scissors dataset](https://universe.roboflow.com/roboflow-58fyf/rock-paper-scissors-sxsw/dataset/14) from Roboflow.

**Key Achievements**:
- Achieved **mAP50: 0.945** and **mAP50-95: 0.732** on the validation dataset, showcasing the model's high accuracy and robustness.

## Installation

To run this notebook, you need to have the following libraries installed:

- `supervision`
- `ultralytics`
- `roboflow`
- `yolov10`

You can install these libraries using the following commands:

```bash
pip install supervision
pip install ultralytics
pip install roboflow
pip install git+https://github.com/THU-MIG/yolov10.git
```


## Usage

1. **Mount Google Drive**: Access your files in Google Drive.
2. **Install Required Libraries**: Install necessary Python libraries (`supervision`, `ultralytics`, `roboflow`, `yolov10`).
3. **Import Libraries**: Import essential libraries for data handling, model training, and visualization.
4. **Set Up Environment**: Define the current working directory and prepare the environment.
5. **Download Model Weights**: Fetch the pre-trained YOLOv10 model weights.
6. **Download Dataset**: Download the Rock, Paper, Scissors dataset from Roboflow.
7. **Train the Model**: Train the YOLOv10 model on the dataset.
8. **Display Training Results**: Visualize the training results, including the confusion matrix and training metrics.
9. **Evaluate the Model**: Evaluate the trained model on the validation set.
10. **Make Predictions**: Use the trained model to predict test images and a single image.
11. **Process Video**: Apply the model to a video to detect objects frame by frame and save the results.

Please refer to the Jupyter Notebook in this repository for detailed code and step-by-step instructions.


## Results

The model achieved impressive results on the validation dataset:
- **mAP50: 0.945**
- **mAP50-95: 0.732**

Below is a visual representation of the model's performance on a sample video:

![Model Output](https://github.com/4prince8/Object_Detection_Yolov10/blob/main/RPS0_detected.gif)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

