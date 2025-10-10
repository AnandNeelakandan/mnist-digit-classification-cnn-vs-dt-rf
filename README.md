# 🧠 MNIST Digit Classification | Deep Learning vs Classical ML

A complete supervised learning pipeline for handwritten digit recognition using the MNIST dataset. This project benchmarks a Convolutional Neural Network (CNN) against classical models like Decision Tree and Random Forest, with full evaluation and visualization.

---

## 📦 Project Summary

- **Dataset**: MNIST (Modified National Institute of Standards and Technology)
- **Problem Type**: Multi-class Image Classification (Digits 0–9)
- **Tech Stack**: Python, TensorFlow/Keras, Scikit-learn, Matplotlib, Seaborn
- **Models Implemented**:
  - ✅ Convolutional Neural Network (CNN)
  - ✅ Decision Tree Classifier
  - ✅ Random Forest Classifier
- **Evaluation Metrics**:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-Score
- **Visualizations**:
  - Class distribution
  - Sample digit images
  - Actual vs Predicted grids
  - Accuracy comparison bar chart

---

## 🚀 Key Features

- 📂 **Raw Data Loader**: Reads `.idx` format directly using `struct` and `numpy`
- 🧠 **CNN Architecture**: 2 Conv2D layers + MaxPooling + Dense layers with softmax output
- 🌲 **Classical ML Models**: Decision Tree and Random Forest applied on flattened image vectors
- 📊 **Model Evaluation**: Confusion matrix, classification report, and side-by-side prediction grids
- 💾 **Model Saving**: CNN model exported as `.h5` for future reuse or deployment

---

## 📈 Performance Comparison

| Model               | Accuracy |
|--------------------|----------|
| Decision Tree       | 88.57%   |
| Random Forest       | 97.25%   |
| Convolutional Neural Network | 99.03%   |

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AnandNeelakandan/mnist-digit-classification-cnn-vs-dt-rf/blob/main/CNN.ipynb
