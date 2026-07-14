# SCT_ML

# Machine Learning Projects

This repository contains a collection of machine learning projects that I worked on to better understand how different algorithms can be applied to real-world problems.

Instead of only focusing on model accuracy, I used these projects to understand the complete machine learning workflow—from exploring and preprocessing data to training models, evaluating their performance, and visualizing the results.

## Projects Included

### 1. House Price Prediction using Linear Regression

The first project focuses on predicting house prices using a Linear Regression model.

The model uses basic property information such as square footage, number of bedrooms, and number of bathrooms to estimate the price of a house.

Through this project, I explored data preprocessing, feature selection, train-test splitting, model training, and regression evaluation.

**Algorithm Used:** Linear Regression

**Key Concepts:**

* Data preprocessing
* Feature selection
* Regression
* Train-test split
* Model evaluation

---

### 2. Customer Segmentation using K-Means Clustering

In this project, I used K-Means Clustering to group retail customers based on their purchasing characteristics.

The goal was to identify customers with similar behaviour and understand how unsupervised learning can be used for customer segmentation.

The Elbow Method was used to help determine an appropriate number of clusters, and the final customer groups were visualized to better understand the segmentation.

**Algorithm Used:** K-Means Clustering

**Key Concepts:**

* Unsupervised learning
* Customer segmentation
* Clustering
* Elbow Method
* Data visualization

---

### 3. Cats vs Dogs Image Classification using SVM

This project explores image classification using a Support Vector Machine.

The objective was to classify images as either cats or dogs using the Dogs vs Cats dataset.

Images were resized and converted into numerical features before being passed to the SVM classifier. The model achieved an accuracy of approximately 54.7%.

While the accuracy was limited, this project helped me understand an important practical lesson: traditional machine learning algorithms may struggle when working directly with raw image pixels.

This also introduced me to the importance of feature extraction techniques such as HOG and the advantages of deep learning for image classification.

**Algorithm Used:** Support Vector Machine

**Accuracy:** Approximately 54.7%

**Key Concepts:**

* Image preprocessing
* Image resizing
* Feature vectors
* Support Vector Machines
* Classification metrics
* Precision, Recall and F1-score

---

### 4. Hand Gesture Recognition using CNN

The final project focuses on recognizing different hand gestures from images using a Convolutional Neural Network.

The model was trained on the LeapGestRecog dataset containing multiple hand gesture classes.

Images were resized, normalized, and passed through convolutional and pooling layers to extract visual features. The trained model was then used to predict gesture classes and display prediction confidence.

I also explored how the trained model could be connected to a webcam-based system for real-time hand gesture recognition.

**Algorithm Used:** Convolutional Neural Network

**Key Concepts:**

* Deep learning
* Image classification
* Convolutional layers
* Max pooling
* Softmax classification
* Prediction confidence
* Real-time gesture recognition

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* OpenCV


These projects were a practical step in strengthening my understanding of machine learning and applying concepts beyond theory.
