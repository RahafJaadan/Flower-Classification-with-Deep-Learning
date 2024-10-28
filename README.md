# Flower-Classification-with-Deep-Learning

This project focuses on classifying different flower types using deep learning. Our model takes an image as input and predicts the type and name of the flower depicted. 

## Problem and Solution 
During training, we encountered an issue of **overfitting**, where the model performed well on training data but poorly on test data. To address this, we applied **data augmentation** techniques and **Dropout** layers to improve model generalization and balance the accuracy between training and test datasets.

## Libraries Used
* **TensorFlow**: For building and training the deep learning model.
* **OpenCV**: For image processing and manipulation.
* **NumPy**: For numerical operations.
* **Matplotlib and plt**: For visualizing images and results. 
* **Pathlib**: For file and directory management. 
* **Scikit-learn (sklearn)**: For additional evaluation metrics and data processing.

## Usage 
1. Clone the repository.
2. Install required libraries.
3. Run the model training script.
4. Input flower images for model prediction and receive the type and name of the flower.
