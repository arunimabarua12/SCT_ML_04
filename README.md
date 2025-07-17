# SCT_ML_04
# ✋ Hand Gesture Recognition with CNN

A full-featured deep learning project that classifies hand gestures using grayscale images from the [LeapGestRecog Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog). This project builds and trains a Convolutional Neural Network (CNN) from scratch with data augmentation, visualization, early stopping, and custom prediction tools.

## 📂 Dataset

- **Dataset Name**: [LeapGestRecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Classes**: 10 different hand gestures
- **Type**: Grayscale .png images in per-class folders
- **Example Classes**:
  - palm
  - I
  - fist
  - fist_moved
  - thumb
  - index
  - ok
  - palm_moved
  - c
  - down

---

## 🧠 Model Architecture

A custom-built Convolutional Neural Network (CNN) with the following layers:

- 4 × Conv2D + BatchNormalization + MaxPooling2D blocks
- Flatten + Dense (512 → 256 → 10 softmax)
- Dropout layers for regularization
- Optimized with Adam optimizer and sparse categorical crossentropy

---

## 🚀 Features

✅ **Custom Data Loader** for class-wise folders  
✅ **Data Augmentation** using `ImageDataGenerator`  
✅ **EarlyStopping** & **ReduceLROnPlateau** callbacks  
✅ **Model Evaluation** with Accuracy, Classification Report, Confusion Matrix  
✅ **Random Sample Prediction & Visualization**  
✅ **Single User Image Prediction Interface**  
✅ **Interactive Training Visualization** (loss & accuracy)  

---

## 🛠️ Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/hand-gesture-cnn.git
cd hand-gesture-cnn


🗃️ Project Structure

hand-gesture-cnn/
├── hand_gesture_recognition.py     # Main project script
├── README.md                       # Project documentation
├── requirements.txt                # List of dependencies
├── /leapGestRecog/                 # Dataset directory
└── /my-hand/                       # Custom test images (optional)

📊 Evaluation Metrics
✅ Accuracy

✅ Classification Report

✅ Confusion Matrix

✅ Per-image prediction confidence

# 🧪 Prediction Examples
<img width="1120" height="469" alt="Screenshot 2025-07-09 162827" src="https://github.com/user-attachments/assets/c24ccb0a-00fc-4b95-bd41-d14092fc1042" /> <img width="1274" height="539" alt="Screenshot 2025-07-10 023935" src="https://github.com/user-attachments/assets/66b15aa5-915f-4a44-92eb-fe5edd9f347f" />


