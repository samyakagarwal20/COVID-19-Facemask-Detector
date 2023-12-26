# COVID-19 Facemask Detector

## Overview

The COVID-19 Facemask Detector is an application developed using Python and the Keras API, employing deep learning techniques to determine whether a person in an image is wearing a facemask. The primary goal is to contribute to public health initiatives by providing a reliable tool for facemask detection, essential in the ongoing efforts to combat the spread of COVID-19.

## Features

- **Convolutional Neural Network (CNN):**
    - Utilizes a ConvNet architecture for image classification, leveraging convolution layers to efficiently extract and learn patterns from the dataset.

- **Optimization Techniques:**
    - Implements various optimization techniques, including regularization, different optimizers, and hyper-parameter tuning, to enhance the model's accuracy and prevent overfitting.

- **Image Augmentation:**
    - Applies image augmentation to diversify the dataset, ensuring the model's robustness and ability to generalize effectively to real-world scenarios.

- **Dataset Compilation:**
    - Gathers a comprehensive dataset from Kaggle and supplements it with self-captured images from real-world surroundings, enhancing the model's adaptability.

## Getting Started

### Prerequisites

- Python 3.x
- Keras
- OpenCV
- Matplotlib
- NumPy
- scikit-learn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/COVID-19-Facemask-Detector.git
   cd COVID-19-Facemask-Detector
   ```

2. **Install dependencies:**
    ```bash
   pip install -r requirements.txt
   ```

### Usage
To test out the model onto the real data, simply run the code in the following sections of Jupyter Notebook: 

- Importing the required libraries
- Building our Neural Network Model
- Loading the weights of the model
- Testing the model onto the real data

```
Once the script is running, the facemask status will be detected in real-time. 

The application will keep running until the Esc key is pressed.
```