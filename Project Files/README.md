
# 🦋 Butterfly Species Classifier Web App

A deep learning-based web application that classifies butterfly species from user-uploaded images using a VGG16 Convolutional Neural Network model. Built with Flask, this project demonstrates how AI can be applied to support biodiversity and species identification.

---

## 🌟 Features

- 🎯 Predicts butterfly species from uploaded images
- 💡 Uses a pre-trained VGG16 model (transfer learning)
- 🧠 Classifies 75 unique butterfly classes
- 🌐 Beautiful web interface using HTML, CSS & Flask
- 🆓 Deployable on Render or Railway for free hosting

---

## 📸 Demo

![Demo UI](static/images/demo_screenshot.jpg) <!-- Add a screenshot path or image link -->

---

## 📁 Project Structure

```
butterfly-classifier/
├── app.py                  # Flask backend
├── vgg16_model.h5          # Pre-trained butterfly classifier model
├── requirements.txt        # Project dependencies
├── static/
│   ├── style.css           # CSS styling
│   └── images/             # Uploaded & demo images
├── templates/
│   ├── index.html          # Home page
│   ├── input.html          # Image upload form
│   └── output.html         # Prediction display
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/ShyamPradeepReddy/butterfly-classifier.git
cd butterfly-classifier
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Add Model File
Download or place your `vgg16_model.h5` file into the root directory.

---

## 🚀 Running the Application

```bash
python app.py
```

Access it at:  
📍 `http://127.0.0.1:5000`

---

## 🧠 Model Details

- **Architecture:** VGG16 + Custom Dense Layers
- **Input Shape:** 224x224 RGB images
- **Output:** 75 butterfly species
- **Frameworks:** TensorFlow / Keras

---

## Requirements

```txt
Flask==2.3.2
tensorflow==2.12.0
keras==2.12.0
numpy==1.24.3
Pillow==9.5.0
gunicorn==20.1.0
```

---

## 🙌 Contributing

Contributions, suggestions, and improvements are welcome! Fork this repo and submit a pull request.

---

## 👤 Author

**Pradeep Reddy**  
🔗 [GitHub](https://github.com/ShyamPradeepReddy) | [LinkedIn](https://linkedin.com/in/shyampradeepreddy)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Acknowledgements

- Butterfly image datasets from Kaggle
- TensorFlow & Keras for the ML framework
- Render for free deployment hosting
