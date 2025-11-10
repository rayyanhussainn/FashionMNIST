# Fashion MNIST Image Classification – Deep Learning with TensorFlow/Keras

This project builds and trains a deep learning model to classify grayscale clothing images from the Fashion-MNIST dataset using **TensorFlow** and **Keras**. The goal is to understand model design, hyperparameters, overfitting behavior, and Kaggle-style evaluation by submitting predictions to a competition leaderboard.

---

## 📌 Project Overview

- Classifies 70,000 clothing images into 10 categories  
- Uses TensorFlow/Keras to build a Multilayer Feed-Forward Neural Network (Dense layers only)  
- Includes training, validation, and test prediction workflow  
- Explores hyperparameters such as learning rate, batch size, epochs, activation functions, and model architecture  
- Generates a `submission.csv` file for Kaggle competition scoring  

---

## 🧠 Dataset

- **Fashion MNIST** (reshaped to 1D arrays of 784 pixels)  
- **60,000** training examples  
- **10,000** test examples  
- 10 clothing categories:  
  *T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle Boot*

Training file: `380hw3_train.csv`  
Test file: `380hw3_test.csv`  

---

## ⚙️ What the Model Does

1. Loads the training & test datasets  
2. Performs **stratified train/validation split** (90%/10%)  
3. Normalizes pixel values to `[0, 1]`  
4. Builds a Dense-based neural network  
5. Trains with TensorFlow/Keras and monitors validation accuracy  
6. Plots accuracy/loss curves to check for overfitting  
7. Generates test-set predictions  
8. Saves predictions into `submission.csv` for Kaggle  

---

## 🛠 Tech Stack

- **TensorFlow / Keras**  
- **Python**  
- **NumPy, Pandas**  
- **Matplotlib**  
- **Kaggle GPU environment**  

---

## 🚀 How to Run (Kaggle Notebook)

1. Open the starter notebook from the competition page  
2. Load the provided CSV datasets  
3. Split the data into `X_train`, `X_valid`, `Y_train`, `Y_valid`  
4. Normalize all pixel values  
5. Build a Dense neural network  
6. Train the model and plot performance  
7. Make predictions on the test set  
8. Export predictions as `submission.csv`  
9. Upload to Kaggle leaderboard  

---

## 🔧 Hyperparameters Explored

- **Epochs** (10, 20, 50…)  
- **Hidden layer sizes** (64, 128, 256…)  
- **Number of layers**  
- **Learning rates** (0.001, 0.0001, 0.1…)  
- **Activation functions** (`relu`, `sigmoid`, `gelu`)  
- **Optimizers** (`Adam`, `SGD`)  

---

## 📈 Performance Evaluation

Includes:

- Training vs. validation accuracy plots  
- Training vs. validation loss plots  
- Kaggle private/public leaderboard scores  

---

## ✅ Output

- Trained deep learning model  
- Accuracy/loss visualizations  
- Final `submission.csv` file for Kaggle scoring  

---
