# 👤 Age & Gender Prediction from Face Images using CNN (UTKFace Dataset)

This project implements a **multi-output Convolutional Neural Network (CNN)** that predicts both **age** and **gender** from facial images. The model is trained on the [UTKFace dataset](https://susanqq.github.io/UTKFace/), which contains over 20,000 face images labeled with age, gender, and ethnicity.

---

## 📌 Project Highlights

- 🔍 **Image Preprocessing** – Includes resizing, normalization, and splitting dataset into train/test
- 🧠 **Multi-Output CNN** – Single model predicts both age (regression) and gender (classification)
- 🎯 **Loss Functions** – Combines `MeanSquaredError` for age and `BinaryCrossentropy` for gender
- 🧪 **Evaluation** – Visualizations for accuracy and loss curves per output
- 🗃️ **Dataset** – UTKFace: human face images with annotations (age, gender, ethnicity)

---

## 🧰 Tech Stack

- Python
- TensorFlow / Keras
- NumPy / OpenCV
- Matplotlib / Seaborn

---

## 🚀 How to Run

```bash
git clone https://github.com/ritikkalyan1000/age-gender-predictor-utkface.git
cd age-gender-predictor-utkface
pip install -r requirements.txt
