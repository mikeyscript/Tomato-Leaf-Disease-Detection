# 🍅 Tomato Leaf Disease Detection

A Deep Learning-based Tomato Leaf Disease Detection system built using **TensorFlow**, **Keras**, **MobileNetV2**, and **Gradio**. The model classifies tomato leaf images into different disease categories, helping identify plant diseases quickly through image classification.

---

## 📌 Project Overview

This project uses Transfer Learning with MobileNetV2 to classify tomato leaf images into multiple disease categories. The dataset is preprocessed using TensorFlow's image dataset utilities, and the trained model is deployed through an interactive Gradio interface.

The application allows users to upload a tomato leaf image and instantly receive the predicted disease class.

---

## ✨ Features

- 🍅 Tomato leaf disease classification
- 🧠 Transfer Learning using MobileNetV2
- 📷 Image classification with TensorFlow
- ⚡ Fast prediction using a trained deep learning model
- 🌐 Interactive Gradio interface
- 📊 Image preprocessing and visualization

---

## 🛠️ Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Gradio
- Kaggle Tomato Leaf Dataset

---

## 📂 Dataset

This project uses the **Tomato Leaf Disease Dataset** from Kaggle.

Download the dataset and update the dataset path in the notebook if you wish to retrain the model.

**Note:** The trained model (`tomato_leaf_model.h5`) is included in this repository, so retraining is not required for disease prediction.

---

## 🧠 Deep Learning Workflow

1. Load the tomato leaf dataset.
2. Split the dataset into training and validation sets.
3. Preprocess images.
4. Load the pre-trained MobileNetV2 model.
5. Freeze the base model.
6. Add custom classification layers.
7. Train the model.
8. Save the trained model.
9. Predict diseases from uploaded images.
10. Deploy using Gradio.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/mikeyscript/Tomato-Leaf-Disease-Detection.git
```

### 2. Install the required libraries

```bash
pip install tensorflow numpy matplotlib pillow gradio
```

### 3. Run the notebook

Open the notebook in Google Colab and execute all cells.

---

## 🚀 Usage

- Upload a tomato leaf image.
- The image is resized and preprocessed.
- The trained MobileNetV2 model predicts the disease.
- The predicted disease class is displayed instantly.

---

## 📁 Project Structure

```
Tomato-Leaf-Disease-Detection/
│
├── Tomato_Leaf_Disease_Detection.ipynb
├── tomato_leaf_model.h5
├── README.md
├── .gitignore
└── LICENSE
```

---

## 🔮 Future Improvements

- Improve model accuracy through fine-tuning
- Support additional crop disease datasets
- Display prediction confidence scores
- Recommend treatments for detected diseases
- Deploy as a Flask or Streamlit web application

---

## 👨‍💻 Author

**Prajeesh**

Machine Learning & Artificial Intelligence Enthusiast

---

## 📜 License

This project is licensed under the MIT License.
