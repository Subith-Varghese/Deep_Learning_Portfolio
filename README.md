
 # 🤖 Deep Learning Projects

Welcome to my Deep Learning project portfolio!  
This repository contains various real-world projects developed using deep learning techniques.

## 🔍 Computer Vision Projects
### 1. 🧑‍💻 Face Recognition with Liveness Detection & Attendance System https://github.com/Subith-Varghese/FaceSecure-Attendance

A secure face recognition system that prevents spoofing and automatically logs attendance. Integrates:

- YOLOv11 → Face detection
- MobileNetV2 (CNN) → Liveness detection (anti-spoofing)
- FaceNet (InceptionResnetV1) → Face recognition

### Key Features

- ✅ Multi-face detection
- ✅ Anti-spoofing via CNN-based liveness detection
- ✅ Real-time recognition & attendance logging
- ✅ User-friendly registration system
- ✅ Scalable database of registered users

Tech Stack
Python | PyTorch/Facenet | YOLOv11 | TensorFlow/Keras | OpenCV | NumPy | Scikit-learn

### 2. ✅ Face Mask Detection (with MobileNetV2)  https://github.com/Subith-Varghese/Face_Mask_Detector
A complete end-to-end project for real-time face mask detection using MobileNetV2 (transfer learning), MTCNN (Face Detection), and a Flask web application.
Key Features

 - 📥 Automatic dataset download from Kaggle
 - 🖼️ Image upload for mask detection
 - 🎥 Real-time webcam detection with OpenCV
 - 🧑‍💻 Transfer learning with MobileNetV2

Example Outputs
 - ✅ Green box → Mask detected
 - ❌ Red box → No Mask
 - ⚠️ Yellow box → Unknown (low confidence)

## 🧠 NLP Projects

### 🎬 Movie Review Sentiment Analysis (LSTM + Word2Vec)

An end-to-end solution to analyze IMDb movie reviews and classify them as Positive, Neutral, or Negative with star ratings.

Key Features

- 📥 IMDb dataset integration (50,000 movie reviews)
- 🔤 Text preprocessing, tokenization, Word2Vec embeddings
- 🧑‍💻 LSTM-based deep learning model for sentiment classification
- 🌐 RESTful Flask web app for real-time predictions
- ⭐ Assigns star rating (0.5⭐ – 5⭐) with probability score

Tech Stack
Python | TensorFlow/Keras | Word2Vec | LSTM | Flask | NLP

Example Prediction
Input: "This movie was absolutely fantastic! Brilliant acting and storyline."

Sentiment → Positive ✅
Probability → 0.93
Rating → 4.5 / 5
Stars → ★★★★⯪

---

### 2. ✅ Fake News Detector (LSTM + Word2Vec) https://github.com/Subith-Varghese/Fake_news_detector
A deep learning application that detects whether a news article is Fake or Real using LSTM with Word2Vec embeddings.

### Key Features

- 📥 Kaggle dataset integration (Fake & True news articles)
- 🔤 Advanced text preprocessing (cleaning, lemmatization, contractions handling)
- 🧑‍💻 LSTM model training with Word2Vec embeddings

### Model Overview

- 📐 Architecture: LSTM + Pre-trained Word2Vec (300D)
- 📝 Sequence Length: 300 | Vocabulary Size: 20,000
- 🛑 Training: Early stopping & checkpoint saving

### Example Outputs

- 🟢 Real News → Output label = Real
- 🔴 Fake News → Output label = Fake

  
More projects coming soon!
