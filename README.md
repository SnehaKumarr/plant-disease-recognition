

# Plant Disease Recognition Using Deep Learning

This project uses a Convolutional Neural Network (CNN) built with TensorFlow in Google Colab to classify plant leaf images as healthy or diseased.

## Dataset
- PlantVillage dataset from Kaggle: [Link](https://www.kaggle.com/datasets/emmarex/plantdisease)

## Dataset Overview

| **Feature**         | **Description**                                                             |
|---------------------|-----------------------------------------------------------------------------|
| image             | RGB image of a plant leaf                                                   |
| label            | Name of the plant and the specific disease (e.g., Tomato___Late_blight)     |
| plant_species     | Type of plant (e.g., Tomato, Potato, Corn)                                  |
| disease_type      | Type of disease or "healthy" if no disease present                          |
| image_dimensions  | Dimensions of the image (commonly 256x256 or resized during preprocessing)  |
| color_mode        | Image color format (RGB)                                                    |
| total_classes     | Number of distinct classes (38 in full dataset)                             |
| dataset_split     | Train/Test/Validation split for model training                              |


## Tech Stack

### Technologies Used:

1. **Deep Learning Framework**
   - TensorFlow / Keras – Used to build and train a Convolutional Neural Network (CNN) for classifying plant leaf images into healthy or diseased categories.

2. **Development Environment**
   - Google Colab – Utilized for model development and training, taking advantage of free cloud GPUs.

3. **Data Visualization**
   - Matplotlib – Used to visualize training curves, prediction outputs, and model evaluation metrics.

4. **Programming Language**
   - Python – Used for writing the entire pipeline including data loading, preprocessing, model training, and evaluation.

## Features
- Data preprocessing: resizing, normalization, augmentation
- CNN architecture with high validation accuracy
- Visualization of results and confusion matrix



## Success Metrics

- **Test Accuracy:** `94.89%`  
  The trained CNN model achieved a test accuracy of **94.89%**, demonstrating high performance in correctly identifying plant diseases from unseen leaf images.


## Author
- Sneha Kumar (NITRR)



