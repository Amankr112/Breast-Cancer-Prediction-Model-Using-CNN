# 🧠 Breast Cancer Detection: Invasive Ductal Carcinoma (IDC) using Deep Learning

A deep learning project that aims to automatically detect **Invasive Ductal Carcinoma (IDC)** — the most common type of breast cancer — from histopathological tissue slice images. Built using PyTorch and CNNs to assist pathologists in faster, more consistent diagnoses.

---

## 🔍 Project Motivation

Manual detection of breast cancer by pathologists is time-consuming and subjective. This project leverages deep learning to automate and standardize the diagnosis of IDC, thereby reducing human error and assisting healthcare professionals, especially in regions with limited access to medical expertise.

---

## 📁 Dataset

The dataset contains labeled breast tissue slice images, categorized into:

- IDC (Invasive Ductal Carcinoma)
- Healthy tissue
- Other breast cancer subtypes (optional)

📦 **Dataset Size**: ~3 GB  
🔗 **Download Link**: [https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images](#) 

---

## 🧪 Project Features

- 📊 Exploratory Data Analysis of IDC vs Healthy samples
- 🧠 Custom CNN model in PyTorch for binary classification
- 🔁 Training loop with validation monitoring
- 📉 Evaluation metrics: F1 Score, Balanced Accuracy
- 🔍 Error analysis and probability landscape visualization
- 🚀 Optimized training with cyclical learning rates

---

## 🛠 Tech Stack

| Task               | Tools / Libraries                 |
|--------------------|-----------------------------------|
| Language           | Python                            |
| Deep Learning      | PyTorch                           |
| Image Processing   | OpenCV, torchvision               |
| Data Visualization | Matplotlib, Seaborn               |
| Evaluation         | Scikit-learn                      |
| Environment        | Jupyter Notebook                  |

---

## 📦 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/breast-cancer-idc-detection.git
cd breast-cancer-idc-detection

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt
