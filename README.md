# 🚦🌧️ Traffic & Weather Anomaly Detection System

## 📌 Overview
This project presents a **Computer Vision-based anomaly detection system** that identifies unusual events in **traffic conditions influenced by weather factors**.

It combines:
- 📷 Traffic video/image data
- 🌦️ Weather data (rain, fog, humidity, etc.)
- 🤖 Deep learning techniques

to detect anomalies such as:
- Traffic congestion spikes  
- Accidents or unusual vehicle behavior  
- Weather-induced disruptions  

---

## 🎯 Objectives
- Detect **traffic anomalies in real-time**
- Analyze **impact of weather on traffic**
- Build a **deep learning-based anomaly detection pipeline**
- Contribute towards **smart city solutions**

---

## 🧠 Methodology

### 1. Data Collection
- Traffic images/videos  
- Weather-related data  

### 2. Preprocessing
- Frame extraction  
- Image resizing and normalization  
- Feature preparation  

### 3. Model
- CNN for spatial feature extraction  
- (Optional) LSTM for temporal analysis  
- Autoencoder / anomaly scoring  

### 4. Detection
- Learn normal patterns  
- Identify anomalies using deviation  

---

## 🏗️ Tech Stack
- Python  
- OpenCV  
- NumPy, Pandas  
- TensorFlow / PyTorch  
- Matplotlib  

---

## 📌 Output Note
All the **outputs, visualizations, and results are included directly inside the `.ipynb` notebook file**.

To view them:
- Open the notebook in **Google Colab / Jupyter Notebook**
- Run all cells (if needed)

The notebook contains:
- Model outputs  
- Graphs and plots  
- Intermediate processing results

## 📂 Dataset
The dataset used in this project is hosted on Google Drive due to its large size.

👉 **Download Dataset:** https://drive.google.com/drive/folders/18OUhpzdWs8-Cp22xGHZvHixKP74cNtcv?usp=sharing

### 📌 Dataset Details
- Contains traffic images/videos  
- Includes weather-related conditions (rain, fog, etc.)  
- Used for training and testing anomaly detection models  

### ⚠️ Note
- Please download the dataset manually from the link above  
- Place the dataset inside the `data/` folder before running the project  
