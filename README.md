# Facial Expression Recognition System

A real-time facial expression recognition system that detects and classifies human emotions from webcam input using **deep learning** and **computer vision** techniques. The system can accurately identify emotions such as **happiness**, **sadness**, **anger**, **surprise**, and more.

---

## 🚀 Features

- 📷 Real-time facial expression detection via webcam
- 🧠 Uses a **Convolutional Neural Network (CNN)** model trained on **FER-2013 dataset**
- 🔧 Fine-tuned using **Adapter Layers** for improved emotion classification
- 🔍 Performs live **face detection** and **expression inference**
- ✅ Accurate performance even in dynamic lighting or environments

---

## 📁 Dataset

- **FER-2013** (Facial Expression Recognition 2013)  
  - 48x48 grayscale face images  
  - 7 emotion labels: `angry`, `disgust`, `fear`, `happy`, `sad`, `surprise`, `neutral`
  - Available via [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)

---

## 🧠 Model Architecture

- CNN with convolutional + pooling layers
- Adapter Finetuning on pre-trained model
- Fully Connected Layers + Softmax for classification
- Trained with categorical cross-entropy

---

## 🛠️ Technologies Used

| Tool/Library   | Purpose                           |
|----------------|------------------------------------|
| Python         | Core programming language         |
| TensorFlow / Keras | Model training & deployment   |
| OpenCV         | Webcam integration & face detection |
| NumPy / Pandas | Data processing                   |
| Matplotlib     | Visualization                     |

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/facial-expression-recognition.git
cd facial-expression-recognition
