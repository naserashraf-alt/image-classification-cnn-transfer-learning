# 🧠 Image Classification with CNNs & Transfer Learning (CIFAR-10)

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

An end-to-end Computer Vision & Deep Learning benchmark comparing custom **Convolutional Neural Networks (CNNs)** with pre-trained **Transfer Learning** architectures (**MobileNetV2** & **VGG16**) on the **CIFAR-10** image dataset.

---

## 📋 Methodology & Pipeline

The project systematically moves through 11 core steps to ensure structural data comprehension and model reliability:

| Step | Milestone | Objectives |
| :--- | :--- | :--- |
| **1** | 📦 Setup | Install packages and configure TensorFlow / GPU acceleration environments. |
| **2** | 📂 Data Loading | Automatically acquire the standard CIFAR-10 image corpus. |
| **3** | 📊 EDA | Visualize sample images, class distributions, and feature layouts. |
| **4** | 🧼 Preprocessing | Normalize pixel values ($[0, 255] \to [0, 1]$), one-hot encode target labels. |
| **5** | 🏗️ Custom CNN 1 | Baseline Convolutional Neural Network built from scratch. |
| **6** | 🏗️ Custom CNN 2 | Deeper CNN architecture with Batch Normalization and Dropout regularization. |
| **7** | 🧠 MobileNetV2 TL | Lightweight pre-trained vision engine via Transfer Learning. |
| **8** | 🧠 VGG16 TL | Deep visual feature extractor via Transfer Learning with fine-tuning. |
| **9** | 📈 Loss/Accuracy | Generate diagnostic training vs validation curves. |
| **10** | 🧪 Model Auditing | Evaluate and compare precision, recall, F1-score, and confusion matrices. |
| **11** | 🔮 Inference | Run sample prediction inference on unseen test images. |

---

## 🛠️ Tech Stack

* **`TensorFlow / Keras`**: Neural network architecture building, training, and callbacks.
* **`NumPy`**: Multidimensional array manipulation and vectorized math.
* **`Matplotlib / Seaborn`**: Visualizing accuracy/loss trajectories and confusion matrices.
* **`Scikit-Learn`**: Classification metrics, classification reports, and evaluation.

---

## 📦 Dataset Overview (CIFAR-10)

* **Volume**: 60,000 $32 \times 32$ color images (50,000 training, 10,000 test).
* **Classes (10)**: `airplane`, `automobile`, `bird`, `cat`, `deer`, `dog`, `frog`, `horse`, `ship`, `truck`.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/naserashraf-alt/image-classification-cnn-transfer-learning.git
cd image-classification-cnn-transfer-learning
```

### 2. Set Up Virtual Environment & Dependencies
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

pip install tensorflow keras numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch the Notebook
```bash
jupyter notebook "Image Classification with CNNs & Transfer Learning.ipynb"
```

---

## 👤 Author

**Naser Ashraf**
- 🌐 [Portfolio Website](https://naserashraf-alt.github.io/portfolio/)
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/naser-ashraf-742106358)
- 📧 [Email](mailto:naserashraf248@gmail.com)
