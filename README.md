# ✋ PRODIGY_ML_04 – Hand Gesture Recognition using Deep Learning

This project recognizes hand gestures in real-time using a deep learning model integrated with OpenCV. It classifies 10 different gestures from the leapGestRecog dataset.

---

## 📌 Project Description

Hand gesture recognition enables intuitive human-computer interaction. This project builds a CNN model to classify gestures and uses OpenCV to capture real-time webcam input.

---

## 🛠 Tech Stack / Tools Used

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**:
  - NumPy
  - Pandas
  - OpenCV
  - TensorFlow / Keras
  - Matplotlib
  - Scikit-learn
- **Dataset**: leapGestRecog (Kaggle)

---

## 🧠 Problem Statement

How can a system recognize human hand gestures from video or image frames to enable touchless interaction for tasks like navigation or control?

---

## 🧪 Solution Approach

1. **Data Collection**:
   - Used the leapGestRecog dataset containing 10 gesture classes.
2. **Preprocessing**:
   - Resized and normalized grayscale images
   - Encoded labels
   - Split into training and testing sets
3. **Model Building**:
   - Built a CNN using Keras with Conv2D, MaxPooling, Dropout layers
   - Trained with categorical cross-entropy loss
4. **Evaluation**:
   - Accuracy and loss visualization
   - Confusion matrix
5. **Real-Time Prediction**:
   - Integrated OpenCV to recognize hand gestures using webcam

---

## 💻 Installation & Setup

```bash
git clone https://github.com/yourusername/hand-gesture-recognition.git
cd hand-gesture-recognition
pip install -r requirements.txt
jupyter notebook
