# YOLOv8 DeepSORT Tracking and Speed Estimation

This repository contains a project that integrates YOLOv8 with DeepSORT for object tracking and speed estimation. The aim is to perform object detection, tracking, and speed estimation of moving objects in videos.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites
- Python 3.10
- Jupyter Notebook or Google Colab
- NVIDIA GPU (recommended for faster processing)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/Sujana-Mollick/YOLOv8_DeepSORT_Tracking_SpeedEstimation.git
    cd YOLOv8_DeepSORT_Tracking_SpeedEstimation
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook YOLOv8_DeepSORT_Tracking_SpeedEstimation.ipynb
    ```

## Usage

### Google Colab
You can also run this project on Google Colab. Click the link below to open the notebook in Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sujana-Mollick/YOLOv8_DeepSORT_Tracking_SpeedEstimation/blob/main/YOLOv8_DeepSORT_Tracking_SpeedEstimation.ipynb)

### Running the Notebook
1. Open `YOLOv8_DeepSORT_Tracking_SpeedEstimation.ipynb` in Jupyter Notebook or Google Colab.
2. Follow the instructions and run the cells sequentially.

## Project Structure
- `YOLOv8_DeepSORT_Tracking_SpeedEstimation.ipynb`: Main Jupyter Notebook for training and inference.
- `datasets/`: Directory to store datasets.
- `runs/`: Directory to store training results including model weights and evaluation metrics.
- `requirements.txt`: List of required Python packages.

## Results
### Confusion Matrix
![Confusion Matrix](runs/detect/train3/confusion_matrix.png)

### Sample Predictions
![Sample Prediction](runs/detect/train3/val_batch0_pred.jpg)

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
