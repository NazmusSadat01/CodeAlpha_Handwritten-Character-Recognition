# Handwritten-Character-Recognition
This project uses Convolutional Neural Networks (CNNs) to recognize handwritten inputs from well-known datasets like MNIST and EMNIST. It can be extended to recognize full words or sentences using sequence models such as CRNN.

# Objective

Build a deep learning model to automatically identify handwritten digits and characters from images.

# Dataset
Source: (Kaggle Custom dataset)

MNIST Dataset
https://www.kaggle.com/datasets/mdnazmussadat1/mnist-dataset

Digits: 0–9

EMNIST Dataset
https://www.kaggle.com/datasets/mdnazmussadat1/emist-dataset

Includes alphabets (A–Z, a–z)

# Model Architecture (CNN)

<img width="715" height="456" alt="model arc" src="https://github.com/user-attachments/assets/41e82b39-2666-4d4f-8e66-4a8811b76cc7" />

# Technologies Used

Python 
TensorFlow / Keras
NumPy
Matplotlib


# Features

✔️ Image preprocessing (grayscale, normalization)
✔️ CNN-based classification
✔️ Supports both digits and characters
✔️ High accuracy on test data
✔️ Easy to extend for real-world applications

 # Results
 Error analysis, implemented in the current cell, calculates and visualizes the word accuracy and the total count of words based on their length. This helps in understanding how the model's performance varies with the length of the words it attempts to recognize. It specifically uses the test set predictions to generate these statistics.

<img width="1552" height="436" alt="accuracy" src="https://github.com/user-attachments/assets/73867b79-4ad2-4824-8bfd-635fb68c4e57" />


