# 🥦 AI-Based Shelf Life Prediction System (Flipkart Grid 6 Hackathon)

This project was developed using **Google Colab** for the Flipkart Grid 6.0 Hackathon. It predicts the **shelf life of fruits and vegetables** using image input and a CNN model. The goal is to help platforms like Flipkart Grocery assess product freshness automatically and reduce wastage.

---

## 🚀 Project Highlights

- ✅ **Built in Google Colab:** Entire pipeline including training, evaluation, and testing implemented in Colab.
- 📸 **Real-Time Image Input:** Uses webcam or uploaded images for real-time predictions.
- 🧠 **CNN-Based Classifier:** Trained on a custom dataset with thousands of fruit/vegetable images labeled for freshness.
- 📊 **Binary Output:** Model predicts whether the item is **Fresh (1)** or **Not Fresh (0)**.
- 🛒 **Flipkart Use Case:** Helps in automating quality control during warehousing or delivery.

---

## 🛠️ Tech Stack

- **Platform:** Google Colab
- **Language:** Python
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy, Matplotlib

---

## 🧑‍💻 How It Works (in Colab)

1. **Dataset Loading:** Uploaded directly from Google Drive (mounted in Colab).
2. **Preprocessing:** Image resizing, augmentation, normalization.
3. **Model Training:** Convolutional Neural Network (CNN) built with TensorFlow/Keras.
4. **Prediction:** Accepts live webcam input or file upload for prediction.
5. **Result Display:** Shows the input image and predicted freshness label.

---

## 📁 Dataset Overview

- **Categories:** Apple, Banana, Carrot, Tomato, and Expired items.
- **Freshness Mapping:**  
  - `0` = Not Fresh (includes expired, wrinkled, or bruised items)  
  - `1` = Fresh  
- Dataset stored and accessed from Google Drive for seamless use in Colab.

---

## 🏆 Hackathon Achievement

Advanced to the **penultimate round** of **Flipkart Grid 6.0**, standing out for its real-world applicability and AI-driven automation approach in the grocery delivery domain.

---

## ▶️ Run It Yourself

Open the Colab notebook here:  
📎 [Shelf Life Prediction - Colab Notebook](https://colab.research.google.com/drive/your-notebook-id)  
*(Replace with your actual notebook link)*

---

## 🖼️ Sample Output

- Displays the image with a bounding box and label:
  - `Fresh`
  - `Not Fresh`

---

## 📬 Contact

**Sanjay Chaurasia**  
📧 sanjaychaurasi22@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/sanjay-chaurasia-822001256)  
🐙 [GitHub](https://github.com/Sanjaychaurasia04)


