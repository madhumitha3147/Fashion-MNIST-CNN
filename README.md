# 👗 Fashion MNIST Classification using CNN

This project classifies fashion items using deep learning techniques on the Fashion-MNIST dataset. Developed as part of a **Major Project for Artificial Intelligence**, it implements both image preprocessing and a custom **Convolutional Neural Network (CNN)** model to recognize clothing categories such as shirts, sneakers, and more.

---

## 📁 Dataset

- Source: [Fashion MNIST - Keras Dataset](https://github.com/zalandoresearch/fashion-mnist)
- Contains:
  - 60,000 training images
  - 10,000 test images
- Image size: **28x28 grayscale**
- Categories (Labels 0–9):
  1. T-shirt/top
  2. Trouser
  3. Pullover
  4. Dress
  5. Coat
  6. Sandal
  7. Shirt
  8. Sneaker
  9. Bag
  10. Ankle boot

---

## 🚀 Model Used

### ✅ Custom CNN
- Input: Grayscale (1 channel)
- Layers:
  - Convolutional Layers with ReLU
  - MaxPooling for downsampling
  - Dropout for regularization
  - Fully Connected Dense Layer
  - Softmax output (10 classes)
- Trained for **10 epochs**

---

## 📊 Results

- **Training Accuracy**: ~91–92%
- **Validation Accuracy**: ~88–90%
- Evaluation included:
  - Accuracy vs Epochs
  - Loss vs Epochs
  - Confusion Matrix (heatmap)
  - Classification Report (Precision, Recall, F1-score)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn
- Scikit-learn

---

## 📌 How to Run

1. Open `Fashion_MNIST_Project.ipynb` in Google Colab
2. Run each cell step-by-step
3. No need to download dataset manually (loaded via Keras)
4. Model is trained and evaluated in notebook
5. Optionally save using:
   ```python
   model.save('fashion_cnn_model.keras')
---
##👤 Author

- Madhumitha
- Major Project | Artificial Intelligence
- GitHub: @madhumitha3147


