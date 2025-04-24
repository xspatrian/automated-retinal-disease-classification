# automated-retinal-disease-classification
# 🧠 Automated Classification of Retinal Diseases

![retina](https://img.shields.io/badge/DeepLearning-CNN%20%7C%20VGG16%20%7C%20ResNet50-blue)
![status](https://img.shields.io/badge/status-Completed-green)
![license](https://img.shields.io/badge/license-MIT-lightgrey)

An AI-powered web system to **automatically detect and classify retinal diseases** from OCT images using deep learning. Built using TensorFlow, Django, and a modern frontend, this system supports real-time predictions and is designed to aid ophthalmologists in early diagnosis.

---

## 📸 Demo

> Upload an OCT image and get instant predictions from three models: Custom CNN, VGG16, and ResNet50  
> *(Screenshot placeholder – add a screenshot here)*

---

## 🚀 Features

- 🧠 **Multi-model Prediction**: Compares performance of CNN, VGG16, and ResNet50
- 📂 **Upload & Classify**: Classifies 9 categories including AMD, DR, CSR, and UNKNOWN
- 🖼️ **Image Preprocessing**: Resize, normalize, and validate input OCT images
- 🌐 **Web Interface**: Django + Chart.js frontend for interactive experience
- 📊 **Model Metrics**: Accuracy, precision, recall, F1-score with confusion matrix
- 🛡️ **Unknown Class Detection**: Filters non-retinal or noisy input images

---

## 🧠 Retinal Classes

| Label | Disease                                |
|-------|----------------------------------------|
| 1     | AMD – Age-related Macular Degeneration |
| 2     | CNV – Choroidal Neovascularization     |
| 3     | CSR – Central Serous Retinopathy       |
| 4     | DME – Diabetic Macular Edema           |
| 5     | DR – Diabetic Retinopathy              |
| 6     | DRUSEN – Yellow Deposits               |
| 7     | MH – Macular Hole                      |
| 8     | NORMAL – Healthy Retina                |
| 9     | UNKNOWN – Invalid or Non-retinal Image |

---

## 🏗️ Tech Stack

- **Frontend:** HTML, Tailwind CSS, JavaScript, Chart.js
- **Backend:** Python, Django, TensorFlow, Keras
- **Models:** Custom CNN, VGG16, ResNet50 (fine-tuned)
- **Tools:** SQLite, Git, Postman, VS Code

---

## ⚙️ Installation Guide

```bash
git clone https://github.com/xspatrian/automated-retinal-disease-classification
cd automated-retinal-disease-classification
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py runserver

