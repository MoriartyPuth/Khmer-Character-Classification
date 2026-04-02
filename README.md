# Project Overview 📄🚀

This project is designed to automate the recognition of Khmer characters (consonants, vowels, and numerals). It addresses the complexity of the Khmer script, which includes unique features like subscript consonants `(Cheung Akshar)` and complex vowel placements.

## ✨ Key Components
### 1. Model Architecture:
* It utilizes a Convolutional Neural Network (CNN), which is the standard for image classification tasks.
* The model is trained to identify various classes of Khmer characters from image data.
### 2. Dataset:
* The project uses a dataset of handwritten or digital Khmer characters.
* Preprocessing involves resizing images (typically to 32x32 or 64x64 pixels) and normalizing pixel values to improve training efficiency.
### 3. Core Files:
* `Khmer_Character_Recognition.ipynb`: The primary Google Colab/Jupyter notebook used for training the model and evaluating its accuracy.
* `model.h5`: The saved weights of the trained neural network.
* `Data`: https://aupp.instructure.com/courses/4513/files/635583?wrap=1 , https://aupp.instructure.com/courses/4513/files/635585?wrap=1
* `Sample Code`: https://colab.research.google.com/drive/1bKYQ7iOEd89nCsdb0v_xJQLv5qEQgzff?usp=sharing
## 🛠️ Features
* High Accuracy: The model aims for a high recognition rate across different character types.
* End-to-End Pipeline: Includes steps from data loading and augmentation (to handle different handwriting styles) to final prediction.
* Keras/TensorFlow: The implementation is built using the TensorFlow framework and Keras API for deep learning.
## 📐 How it works
* Input: An image of a single Khmer character.
* Processing: The CNN extracts spatial features (curves, lines, and intersections) from the character.
* Output: A classification label corresponding to the specific Khmer Unicode character (e.g., ក, ខ, គ).

---

*Current Status: The repository serves as a research or educational tool for Khmer OCR (Optical Character Recognition).*
