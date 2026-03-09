# 🧠 Brain Tumor Detection using CNN

## 📌 Project Description

This project is a simple **Brain Tumor Detection Web Application** built using **Deep Learning (CNN)**.
The system allows users to upload a **brain MRI image**, and the trained model predicts whether the image contains a **Tumor** or **No Tumor**.

The model was trained using a **Convolutional Neural Network (CNN)** and connected to a web interface using **Flask**.

---

## 🛠 Technologies Used

* 🐍 Python
* 🧠 TensorFlow / Keras
* 🌐 Flask
* 💻 HTML
* 🎨 CSS
* 🔢 NumPy
* 🖼 Pillow

---

## 📂 Project Structure

```
brain-tumor-detection
│
├── brain_tumor_cnn.ipynb   # CNN training code
├── app.py                  # Flask backend
│
├── templates
│   └── index.html          # Web page
│
├── static
│   └── style.css           # Styling
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Install required libraries

```
pip install flask tensorflow pillow numpy
```

### 2️⃣ Run the application

```
python app.py
```

### 3️⃣ Open the web app in your browser

```
http://127.0.0.1:5000
```

Upload an **MRI brain image** and the model will predict:

✅ **No Tumor**
❌ **Tumor Detected**

---

## ⚠️ Note

The trained model file **model.h5** is not uploaded to this repository because of GitHub file size limits.
To run the project completely, place the trained model file in the project folder.

---

## 👨‍💻 Author

Student Project – **Brain Tumor Detection using Deep Learning**
