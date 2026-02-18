# Dogs-vs-Cats-complete

# 🐶🐱 Dogs vs Cats - CNN Image Classifier

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Problem Statement
Implementing a Convolutional Neural Network (CNN) to classify images as either a Dog or a Cat. 
Dataset contains 25,000 images for training and 10,000 for testing.

---

## 🛠️ Tech Stack
| Category | Tools |
|----------|-------|
| Language | Python 3.10 |
| Framework | TensorFlow / Keras |
| Libraries | NumPy, Matplotlib, Seaborn, Scikit-Learn, Pandas |
| Platform | Google Colab (GPU) |

---

## 📁 Project Structure
```
Dogs-vs-Cats/
│
├── Dogs_vs_Cats_Complete.ipynb   # Main notebook
├── README.md                     # Project documentation
└── resources/
    └── dogcat_model.h5           # Saved trained model
```

---

## 🏗️ CNN Architecture
```
Input (64x64x3)
     ↓
Conv2D (32 filters, 3x3, ReLU)
     ↓
MaxPooling2D (2x2)
     ↓
Conv2D (32 filters, 3x3, ReLU)
     ↓
MaxPooling2D (2x2)
     ↓
Flatten
     ↓
Dense (128, ReLU)
     ↓
Dropout (0.5)
     ↓
Dense (1, Sigmoid) → Cat or Dog
```

---

## ⚙️ Network Parameters
- **Activation:** ReLU (hidden), Sigmoid (output)
- **Optimizer:** Adam (lr=0.001)
- **Loss Function:** Binary CrossEntropy
- **Batch Size:** 32
- **Input Shape:** 64 x 64 x 3

---

## 📊 Data Augmentation
- Horizontal Flip
- Random Zoom (10%)
- Shear Transformation

---

## 📈 Results
| Metric | Score |
|--------|-------|
| Training Accuracy | ~95%+ |
| Validation Accuracy | ~90%+ |

---

## 🖼️ Output Screenshots
### Validation Curves
![Validation Curves](validation_curves.png)

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

---

## ▶️ How to Run
1. Open `Dogs_vs_Cats_Complete.ipynb` in Google Colab
2. Set Runtime → GPU
3. Run All Cells
4. Dataset downloads automatically via TensorFlow Datasets

---

## 🌍 Real World Applications
- Pet classifiers for apps
- Visual quality checks in manufacturing
- Intro to computer vision workflows

---

## 👩‍💻 Author
**Kanna Bhavya Sree**  
[GitHub Profile](https://github.com/kannabhavyasree)
