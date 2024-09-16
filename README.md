# Garbage Classification Using CNN and Data Augmentation

## Project Overview

This project aims to classify images of garbage into different categories using a Convolutional Neural Network (CNN). The dataset used in this project contains images of various garbage classes, and we apply data augmentation techniques to improve the robustness of the model. The classification process is implemented using TensorFlow and Keras.

## Dataset

The dataset consists of images classified into 12 different classes. The dataset is first unzipped, and the images are resized and augmented to generate more training samples.

### Dataset Structure

- `dataset.zip`: The compressed dataset that contains images organized into directories based on their class.
- The images are stored under the directory `garbage_classification/` after extraction.

### Classes:
The dataset contains 12 classes of garbage (such as plastic, paper, metal, etc.), and the model aims to classify them correctly.

## Project Structure

- `garbage_classification/`: Directory containing the images for classification (after extraction).
- `train_test_split`: We split the dataset into training and testing sets to evaluate the model performance.
- `data_augmentation`: Data augmentation is applied to enhance the training process.
- `CNN Model`: A CNN is built using TensorFlow and Keras to classify the images.

## Prerequisites

Before running this project, ensure you have installed the following dependencies:

- Python 3.x
- TensorFlow
- Keras
- Scikit-learn
- Matplotlib
- Seaborn
- Pandas

### Installation

To install the required libraries, you can use the following command:

```bash
pip install tensorflow keras scikit-learn pandas matplotlib seaborn
