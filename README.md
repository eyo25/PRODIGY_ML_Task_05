# Food Image Classification and Calorie Prediction

This project is a food classification model designed to predict both the class and estimated calorie count of various food images. The model is built using TensorFlow and Keras and trained on a subset of the Food-101 dataset, with calorie data mapped to each class. 

## Project Overview

- **Model**: ResNet50 with custom top layers
- **Classes**: 5 classes from the Food-101 dataset
- **Goal**: Classify food images and estimate calories based on class predictions

## Data

- **Image Dataset**: A subset of the Food-101 dataset with 5 food classes.
- **Calorie Dictionary**: A custom dictionary with calorie data mapped to each food class, used to estimate calorie counts after classification.

## Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/food-calorie-predictor.git
   cd food-calorie-predictor
   ```
2.**Install Requirements**
```bash
pip install -r requirements.txt
```
3.**Prepare the Data**

Download the Food-101 dataset or a subset with only the classes you want.
Organize the data in the following structure:
```bash
/path/to/dataset/
├── train/
│   ├── class_1/
│   ├── class_2/
│   └── ...
└── test/
    ├── class_1/
    ├── class_2/
    └── ...
```
