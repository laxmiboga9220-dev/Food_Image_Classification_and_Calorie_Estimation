# Food_Image_Classification_and_Calorie_Estimation
Food image classification and calorie estimation using EfficientNet with a dual-output deep learning model.

# 🍔 Food Recognition and Calorie Estimation

## 📌 Overview

This project uses deep learning to classify food images and estimate their calorie values. A dual-output model based on EfficientNet performs both classification and regression tasks.

## 🗂️ Dataset

* Food-101 dataset (10 selected classes)
* Images are preprocessed and split into training and validation sets

## 🧠 Model

* Backbone: EfficientNet-B0
* Outputs:

  * Food category (classification)
  * Calorie estimation (regression)

## ⚙️ Technologies

* Python, PyTorch
* NumPy, Pandas
* Google Colab

## 📈 Metrics

* Accuracy (classification)
* Mean Squared Error (regression)

## 🚀 How to Run

1. Open in Google Colab
2. Load dataset (Drive or online)
3. Run all cells

## 📎 Conclusion

The model effectively predicts food categories and provides reasonable calorie estimates using a multi-task learning approach.
