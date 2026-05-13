
# 🌱 LetsGrowMore — Virtual Internship Program (VIP)
### Data Science Intern | September 2021

![LetsGrowMore]![Cover page](https://user-images.githubusercontent.com/69778063/133379817-69c94782-0456-48d5-ad80-43c076bae144.png)

---

## 📌 About This Repository

This repository contains all 10 data science and machine learning projects completed as part of the **LetsGrowMore Virtual Internship Program (VIP) — September 2021**.

The projects span a wide range of ML domains — from supervised classification and time-series forecasting to deep learning, computer vision, natural language processing, and recommendation systems — organized across **Beginner**, **Intermediate**, and **Advanced** difficulty levels.

**Intern:** Lakshmi Sindhu Pulugundla
**Program:** LetsGrowMore VIP — Data Science
**Duration:** September – October 2021

---

## 🗂️ Project Overview

| Task | Level | Project | Key Libraries |
|------|-------|---------|--------------|
| TASK-1 | 🟢 Beginner | Iris Flower Classification | Scikit-learn, Pandas, Seaborn |
| TASK-2 | 🟢 Beginner | Pencil Sketch Generator | OpenCV, Matplotlib |
| TASK-3 | 🟢 Beginner | Stock Market Prediction | TensorFlow, Keras, LSTM |
| TASK-4 | 🟡 Intermediate | Global Terrorism EDA | Pandas, Matplotlib, Seaborn |
| TASK-5 | 🟡 Intermediate | Decision Tree Classifier | Scikit-learn, Matplotlib |
| TASK-6 | 🔴 Advanced | MNIST Digit Classification | TensorFlow, Keras, CNN |
| TASK-7 | 🔴 Advanced | Next Word Prediction | TensorFlow, Keras, LSTM, NLTK |
| TASK-8 | 🔴 Advanced | Handwritten Math Equation Solver | OpenCV, CNN, Keras, PIL |
| TASK-9 | 🟢 Beginner | Music Recommendation System | Pandas, NumPy, Recommenders |
| TASK-10 | ⚫ More Advanced | Facial Recognition Mood-Based Music Recommender | TensorFlow, Keras, CNN, FER2013 |

---

## 🟢 Beginner Level Projects

---

### TASK-1 — Iris Flower Classification

**Problem Statement:**
Predict the species of iris flowers (Versicolor, Setosa, Virginica) based on physical parameters — Sepal width, Sepal length, Petal width, and Petal length.

**Approach:**
- Loaded and explored Fisher's Iris dataset
- Performed data preprocessing and standardization
- Trained a supervised multi-class classification model
- Evaluated model performance using accuracy metrics and confusion matrix

**Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Pickle

---

### TASK-2 — Pencil Sketch Generator

**Problem Statement:**
Transform a real-world RGB image into a pencil sketch using image processing techniques.

**Approach:**
- Read image in RGB format using OpenCV (cv2)
- Converted to grayscale
- Inverted the grayscale image to create a negative
- Applied Gaussian blur to the inverted image
- Combined grayscale and blurred image using the divide function to generate the pencil sketch

**Libraries:** OpenCV (cv2), Matplotlib

---

### TASK-3 — Stock Market Prediction using Stacked LSTM

**Problem Statement:**
Predict and forecast stock market prices using a Stacked Long Short-Term Memory (LSTM) neural network.

**Approach:**
- Loaded historical stock price data
- Scaled data using MinMaxScaler for normalization
- Built a Stacked LSTM architecture with multiple hidden layers and memory cells
- Trained the model for time-series forecasting
- Evaluated using Mean Squared Error (MSE)

**Libraries:** TensorFlow, Keras, Pandas, NumPy, Scikit-learn (MinMaxScaler), Matplotlib

---

### TASK-9 — Music Recommendation System

**Problem Statement:**
Build a music recommendation engine that suggests songs to users based on their listening patterns — similar to how Spotify and YouTube Music work.

**Approach:**
- Loaded and merged listening count and song metadata datasets
- Built a content-based and collaborative filtering recommendation engine
- Reduced dataset size for efficient processing
- Generated song recommendations based on user listening history

**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Recommenders

---

## 🟡 Intermediate Level Projects

---

### TASK-4 — Global Terrorism Exploratory Data Analysis

**Problem Statement:**
As a security/defence analyst, identify the hotspots of terrorism and derive actionable security insights through Exploratory Data Analysis.

**Dataset:** Global Terrorism Database (GTD) — 180,000+ terrorist attacks worldwide from 1970–2017, maintained by the National Consortium for the Study of Terrorism (START) at the University of Maryland.

**Approach:**
- Analyzed 180,000+ incidents across 45+ variables
- Identified geographical terrorism hotspots
- Explored attack types, targets, weapons, and temporal trends
- Derived key security insights through visualizations

**Note:** Dataset is 155MB — available via [Google Drive](https://drive.google.com/file/d/1luTU7xBvI7QAGPbQMxEHcgKUi9d6UeP_/view)

**Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

### TASK-5 — Decision Tree Classifier with Visualization

**Problem Statement:**
Build and visualize a Decision Tree classifier on the Iris dataset. The classifier should be able to predict the correct class for any new data fed to it.

**Approach:**
- Loaded Iris dataset from Scikit-learn
- Split data into training and test sets
- Trained a Decision Tree Classifier
- Visualized the full decision tree graphically
- Evaluated using accuracy score and confusion matrix
- Also implemented Decision Tree Regressor for comparison

**Libraries:** Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 🔴 Advanced Level Projects

---

### TASK-6 — MNIST Handwritten Digit Classification

**Problem Statement:**
Build a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset.

**Dataset:** MNIST — 70,000 grayscale images (28×28 pixels) of handwritten digits 0–9
- Training set: 60,000 images
- Test set: 10,000 images

**Approach:**
- Loaded MNIST dataset directly from Keras
- Built a CNN architecture using TensorFlow and Keras
- Trained the model on 60,000 training images
- Evaluated on 10,000 test images
- Visualized model architecture and training performance

**Libraries:** TensorFlow, Keras, NumPy, Matplotlib

---

### TASK-7 — Next Word Prediction using RNN/LSTM

**Problem Statement:**
Train a deep learning model to predict the next word in a sequence — similar to smartphone keyboard prediction and Google's search suggestions.

**Approach:**
- Loaded and preprocessed a large text corpus
- Tokenized text using NLTK RegexpTokenizer
- Built a Sequential RNN/LSTM model using Keras
- Trained the model to predict the next word given a sequence of input words
- Saved model for inference and tested next word predictions

**Libraries:** TensorFlow, Keras (LSTM, Dense, Activation), NLTK, NumPy, Matplotlib, Pickle

---

### TASK-8 — Handwritten Mathematical Equation Solver

**Problem Statement:**
Build a system that identifies numbers, symbols, and characters in a handwritten mathematical equation using image processing and CNN, then solves the equation and returns the result.

**Dataset:** Handwritten Math Symbols — available on [Kaggle](https://www.kaggle.com/xainano/handwrittenmathsymbols)

**Approach (3-Part Pipeline):**
- **Part 1 — Data Extraction:** Loaded and preprocessed handwritten symbol images using OpenCV and PIL. Organized and labeled dataset for training.
- **Part 2 — Model Training:** Trained a CNN model on extracted symbol data to classify mathematical characters and operators.
- **Part 3 — CNN Testing:** Tested the trained model on new handwritten equation images, identified each symbol, assembled the equation, and computed the result.

**Libraries:** OpenCV (cv2), PIL, NumPy, Pandas, Keras, Matplotlib

---

## ⚫ More Advanced Level Projects

---

### TASK-10 — Facial Recognition Mood-Based Music Recommender

**Problem Statement:**
Build an end-to-end system that detects a user's facial emotion using computer vision and recommends songs matching their current mood.

**Dataset:** FER2013 (Facial Expression Recognition) — available on [Kaggle](https://www.kaggle.com/msambare/fer2013)

**Approach:**
- Loaded FER2013 facial expression dataset
- Built a CNN architecture with Conv2D, BatchNormalization, MaxPooling, Dropout, and Dense layers
- Used ImageDataGenerator for data augmentation
- Trained with Adam/RMSprop/SGD optimizers
- Implemented callbacks: ModelCheckpoint, EarlyStopping, ReduceLROnPlateau, TensorBoard
- Detected real-time facial emotions via webcam
- Mapped detected emotions to a song recommendation engine

**Emotion Categories:** Happy, Sad, Angry, Fear, Disgust, Surprise, Neutral

**Libraries:** TensorFlow, Keras, NumPy, Pandas, OpenCV, Matplotlib

---

## 🛠️ Technical Stack

```
Languages:        Python
Deep Learning:    TensorFlow, Keras
ML:               Scikit-learn
Computer Vision:  OpenCV (cv2), PIL
NLP:              NLTK
Data Processing:  Pandas, NumPy
Visualization:    Matplotlib, Seaborn
Architectures:    CNN, RNN, LSTM, Stacked LSTM
Techniques:       Transfer Learning, Collaborative Filtering,
                  Content-Based Filtering, EDA, Time-Series Forecasting,
                  Image Processing, Text Tokenization
```

---

## 📁 Repository Structure

```
Let-s-Grow-More-VIP-Sept21/
│
├── TASK-1 Beginners Level/          # Iris Flower Classification
├── TASK-2 Beginners Level/          # Pencil Sketch Generator
├── TASK-3 Beginners Level/          # Stock Market Prediction (LSTM)
├── TASK-4 Intermediate Level/       # Global Terrorism EDA
├── TASK-5 Intermediate Level/       # Decision Tree Classifier
├── TASK-6 Advance Level/            # MNIST Digit Classification (CNN)
├── TASK-7 Advance Level/            # Next Word Prediction (RNN/LSTM)
├── TASK-8 Advance Level/            # Handwritten Math Equation Solver
│   ├── Part-1 (Data Extraction)
│   ├── Part-2 (Model Training)
│   └── Part-3 (CNN Test)
├── TASK-9 Beginners Level/          # Music Recommendation System
└── TASK-10 More Advance Level/      # Facial Recognition + Music Recommender
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/Lakshmi-Sindhu-P/Let-s-Grow-More-VIP-Sept21.git
```

2. Install required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras opencv-python nltk pillow
```

3. Open any notebook in Jupyter or Google Colab and run all cells.

**Note:** Tasks 4 and 8 require downloading datasets separately — links provided in each task's README.

---

## 🏆 Key Learnings

Through this internship program, I developed hands-on experience across:
- **Supervised Learning** — Classification and regression using Scikit-learn
- **Deep Learning** — CNN and RNN/LSTM architectures using TensorFlow and Keras
- **Computer Vision** — Image processing, feature extraction, and real-time detection using OpenCV
- **Natural Language Processing** — Text tokenization, sequence modeling, and word prediction
- **Recommendation Systems** — Collaborative and content-based filtering
- **Exploratory Data Analysis** — Large-scale dataset analysis and insight generation
- **Time-Series Forecasting** — Stacked LSTM for sequential prediction problems

---

## 📬 Connect

**Lakshmi Sindhu Pulugundla**
- LinkedIn: [/in/lakshmi-sindhu-p](https://www.linkedin.com/in/lakshmi-sindhu-p/)
- GitHub: [/Lakshmi-Sindhu-P](https://github.com/Lakshmi-Sindhu-P)
- Email: sindhu.pl@outlook.com

---

*Completed as part of LetsGrowMore Virtual Internship Program — September 2021*
![Cover page2](https://user-images.githubusercontent.com/69778063/133380003-6b40090f-5949-4ee3-8b8a-690f16687832.png)
