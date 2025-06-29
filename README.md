# Waste Classification Week-1
An AI model to classify waste types using CNN
This project uses a Convolutional Neural Network (CNN) to classify waste images into six categories:
**cardboard**, **glass**, **metal**, **paper**, **plastic**, and **trash**.
Built and trained entirely in Google Colab using a Kaggle dataset.

Dataset
Name:Trash Type Image Dataset  
Source: [Kaggle - farzadnekouei/trash-type-image-dataset](https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset)  
- Contains labeled images for 6 waste types

Tools & Technologies
 - Python
 - TensorFlow / Keras
 - Google Colab
 - Matplotlib
 - Kaggle API

Model Details
 - Architecture: CNN (Convolutional Neural Network)
 - Input Size:224x224 pixels
 - Epochs:10
 - Framework: TensorFlow (Keras)

How to Run?
1. Clone this repo or open the Colab notebook
2. Insert your Kaggle API credentials:
os.environ['KAGGLE_USERNAME'] = 'your_username_here'
os.environ['KAGGLE_KEY'] = 'your_key_here'

# Waste Classification Week-2

Integrated data augmentation using ImageDataGenerator to improve model generalization.

Increased model depth by adding an extra Conv2D layer to enhance feature learning.

Added a confusion matrix to visualize class-wise prediction accuracy.

Included a classification report showing precision, recall, and F1-score per class.

Analyzed performance drops and planned to improve training with more epochs and cleaner input images.
