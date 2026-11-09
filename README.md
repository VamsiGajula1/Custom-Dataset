Food and Animal Image Classification Dataset
📌 Project Overview

This repository contains an image dataset designed for Deep Learning and Computer Vision projects. It includes images of different food items and animals that can be used to train and evaluate image classification models.

The dataset contains 16 image categories covering food and animals.

📂 Dataset Categories
🍔 Food Categories (10 Classes)
Chicken
Sushi
Chai
Burger
Pizza
Dosa
Idly
Fried Rice
Momo
Panipuri
🐾 Animal Categories (6 Classes)
Cat
Dog
Cow
Elephant
Butterfly
Horse
📁 Dataset Structure
text
Dataset/
│
├── chicken/
├── sushi/
├── chai/
├── burger/
├── pizza/
├── dosa/
├── idly/
├── friedrice/
├── momo/
├── panipuri/
│
├── cat/
├── dog/
├── cow/
├── elephant/
├── butterfly/
└── horse/


Each folder contains images belonging to its respective category.

🎯 Project Objectives
Develop an image classification system using Deep Learning.
Classify different types of food and animals.
Train Convolutional Neural Networks (CNN).
Explore image preprocessing and data augmentation.
Evaluate model performance using accuracy and loss.
🛠️ Technologies Used
Python
TensorFlow / Keras
PyTorch
OpenCV
NumPy
Matplotlib
Google Colab
🚀 Applications
Food image recognition
Animal image classification
Computer Vision research
Deep Learning model development
Image-based prediction systems
📊 Dataset Usage

This dataset can be used for:

CNN-based image classification
Transfer learning using VGG16, ResNet50 and MobileNetV2
Training and testing computer vision models
Educational and research purposes
📥 How to Use

Clone this repository:

bash
git clone https://github.com/VamsiGajula1/DeepLearning-Dataset.git


Install the required libraries:

bash
pip install tensorflow numpy matplotlib opencv-python


Load the dataset using TensorFlow:

python
import tensorflow as tf

dataset = tf.keras.utils.image_dataset_from_directory(
    "Dataset",
    image_size=(224, 224),
    batch_size=32
)

print(dataset.class_names)

👨‍💻 Author

Vamsi Gajula

GitHub: VamsiGajula1

⭐ If you find this dataset useful, feel free to star the repository!