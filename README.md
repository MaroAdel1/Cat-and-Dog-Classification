# 🐶🐱 Cat vs Dog Image Classification (Grayscale 80x80)

This project implements and compares two Convolutional Neural Network (CNN) architectures to classify grayscale images of cats and dogs at 80x80 resolution.

## 🧠 Objective
To build a deep learning model that accurately classifies grayscale images of cats and dogs using custom CNN architectures and OpenCV-based preprocessing.

## 🧰 Technologies Used
- **Python**
- **TensorFlow / Keras** – for building CNN models
- **OpenCV** – for image preprocessing (grayscale conversion, resizing)
- **Matplotlib & Seaborn** – for data visualization
- **NumPy** – for image array processing

## 🔍 Project Highlights
- Preprocessed image dataset using OpenCV (resized to 80x80 grayscale).
- Built two CNN architectures:
  - **Model 1:** 4-layer CNN with learning rate scheduling.
  - **Model 2:** 6-layer CNN for deeper feature extraction.
- Visualized training vs validation accuracy and loss.
- Compared the performance of both models.

## 📊 Results
- Both models achieved good classification accuracy.
- Model 2 (6-layer CNN) showed improved generalization on the validation set.
- Training performance was visualized to track convergence.

## 📂 Dataset
Original Dataset (30k Images, 150x150 Grayscale):  
[Kaggle – Cats & Dogs Grayscale Dataset](https://www.kaggle.com/datasets/unmoved/30k-cats-and-dogs-150x150-greyscale)

Dataset was resized to 80x80 grayscale for training.

## 📌 Future Improvements
- Add data augmentation to reduce overfitting.
- Experiment with transfer learning using pretrained models.
- Try batch normalization and dropout tuning.

---

Feel free to fork, clone, or contribute to this project! ⭐
