# 🐶 SCT_ML_3 - Cats vs Dogs Image Classification Using SVM & VGG16

## 💡 Project Overview

This project implements a **Support Vector Machine (SVM)** model to classify images of cats and dogs. Instead of training from scratch, we use **VGG16**, a powerful pre-trained CNN model, to extract high-level image features, which are then used to train the SVM.

---

## 🐾 Dataset Source

We use the [Dogs vs. Cats dataset from Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data), which contains 25,000 labeled images of cats and dogs for training and 12,500 unlabeled images for testing.

---

## 📂 Project Structure

```bash
SCT_ML_3/
│
├── train/                    # Folder with training images (cats & dogs)
├── test1/                   # Folder with testing images
├── sampleSubmission.csv     # Sample format for final submission
├── train_features.pkl       # Extracted features for training
├── test_features.pkl        # Extracted features for testing
├── svm_classifier.pkl       # Trained SVM model
├── submission.csv           # Final prediction output
├── cat_dog_classifier.ipynb # Main Jupyter notebook
└── README.md
