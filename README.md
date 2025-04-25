# 🧠 AI-Based Shelf Life & Expiry Date Detection System  
*Flipkart Grid 6 Hackathon Project*

This project combines **Computer Vision** and **OCR (Optical Character Recognition)** to address real-world problems in **grocery quality control**, **FMCG inventory**, and **supply chain optimization**. Developed entirely in **Google Colab**, it accurately predicts **how many days** a fruit or vegetable will stay fresh and extracts **expiry dates and brand details** from packaging labels.

---

## 📌 Project Overview

Fruits and vegetables spoil at different rates. Knowing how many **days of freshness remain** can reduce waste, improve storage handling, and enhance customer satisfaction.

This project includes:

- 🥦 **Shelf Life Prediction (in days):** A CNN model trained on a dataset of 1900+ images of apples, bananas, tomatoes, carrots, and expired items. The model outputs the **predicted number of days the item will stay fresh**, based on its color, wrinkles, and texture.

- 🏷️ **OCR for Product Info:** Extracts brand name, manufacturing date, and other packaging details using OCR to support smarter inventory and labeling systems.

- 📅 **OCR for Expiry Date Detection:** Reads expiry dates from product packaging to validate shelf life predictions and enable alert systems for near-expiry goods.

---

## 🔧 Tech Stack

- **Platform:** Google Colab  
- **Language:** Python  
- **Libraries:** TensorFlow, Keras, OpenCV, EasyOCR, Tesseract OCR, NumPy, Matplotlib

---

## 🧠 Core Features

### 🔍 1. Shelf Life Prediction (CNN Model)
- Predicts the **remaining freshness in days** (e.g., 1–20 days).
- Based on visual cues such as discoloration, wrinkling, and shape.
- Supports real-time testing through image upload or webcam capture.
- Trained using labeled image folders such as:
  - `Apple(1-5)`, `Banana(10-15)`, `Carrot(3-4)`, `Tomato(5-10)`, etc.

### 🧾 2. OCR for Label & Expiry Detection
- Uses EasyOCR and Tesseract to extract:
  - Brand name  
  - Manufacturing (MFG) and Expiry (EXP) dates  
  - Additional printed product information
- Helpful for automated stock audits and expiry tracking in warehouses.

---

## 📂 Dataset Structure

Stored in Google Drive and organized by predicted freshness (in days):

📁 dataset/ ┣ 📁 train/ ┃ ┣ 📁 Apple(1-5)/ ┃ ┣ 📁 Banana(10-15)/ ┃ ┣ 📁 Carrot(3-4)/ ┃ ┣ 📁 Tomato(5-10)/ ┃ ┗ 📁 Expired/ ┣ 📁 val/ ┗ 📁 test/



- **Total Files:** 1932 images  
- **Classes represent days of freshness**, e.g.:
  - `Banana(1-5)` = expected to remain fresh for 1–5 days  
  - `Apple(10-14)` = expected to remain fresh for 10–14 days  
  - `Expired` = spoiled or beyond shelf life

---

## ▶️ How to Use (in Google Colab)

1. **Mount Google Drive:**

from google.colab import drive
drive.mount('/content/drive')

2 . **Open the Colab Notebook: **
/content/drive/MyDrive/Colab Notebooks/Flipkart_Grid_6.ipynb

3.Steps:

Load and preprocess dataset

Train the CNN model

Use uploaded or live images for prediction

OCR will extract expiry/brand data

Display result: Estimated shelf life (in days) + Label details

# 📊 Sample Output
Input Image: Banana
CNN Prediction: Will stay fresh for 4 days

OCR Output:
Brand: "Lays"
MFG: 02/04/2025
EXP: 12/04/2025

# 🏆 Hackathon Achievement
Advanced to the penultimate round of Flipkart Grid 6.0 Hackathon, this project was recognized for its dual-vision system — estimating shelf life and validating expiry — enabling automation and intelligence in perishable item handling.

# 📬 Contact
Sanjay Chaurasia
📧 sanjaychaurasi22@gmail.com
🔗 LinkedIn(https://www.linkedin.com/in/sanjay-chaurasia-822001256/)
🐙 GitHub(https://github.com/Sanjaychaurasia04/)
