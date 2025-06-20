# 🧠 Brain Tumor Detection Using CNN (MRI Image Classification)

This project uses a **Convolutional Neural Network (CNN)** to automatically detect the presence of a brain tumor in MRI images. The model is trained on a labeled dataset of MRI scans and predicts whether a given scan contains a tumor or not.

---

## 📁 Dataset Structure

The dataset folder should be named `brain_tumor_dataset` and organized as follows:


Each subfolder contains `.jpg` or `.png` images. All images are resized to `100x100` pixels and normalized before training.

---

## 🚀 Features

- ✅ CNN-based binary image classifier
- 🧹 Image preprocessing (resize + normalization)
- 🔁 **Image augmentation** (rotation, zoom, flip, shift) to improve generalization
- ⏹️ **Early stopping** to prevent overfitting
- 📊 **Confusion matrix** & **classification report** for evaluation
- 📈 Accuracy and loss visualizations
- 📷 Image upload support for live predictions (in Google Colab)

---

## 🔍 Improvements Over Previous Version

This version includes multiple upgrades over the earlier version:

| Feature                     | Previous Version | Updated Version |
|----------------------------|------------------|-----------------|
| CNN Architecture           | Basic            | Same (with dropout) |
| Image Augmentation         | ❌ No             | ✅ Yes           |
| Early Stopping             | ❌ No             | ✅ Yes           |
| Confusion Matrix / Report  | ❌ No             | ✅ Yes           |
| Generalization Capability  | Limited           | ✅ Improved      |
| Evaluation Metrics         | Accuracy only     | ✅ Accuracy + Precision, Recall, F1 |
| User Interaction           | Basic             | ✅ Colab-optimized blocks |

---

## 💡 How to Use (in Google Colab)

1. Upload the `brain_tumor_dataset` folder to your Colab working directory.
2. Copy-paste the Colab-ready code blocks into cells and run them in order.
3. Use the upload widget to test predictions on new MRI scans.

---

## 🧪 Sample Prediction Output
🧠 Prediction: Tumor
✅ Test Accuracy: 95.67%


---

## 📌 Requirements

- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- Seaborn
- scikit-learn

---

## 📄 License

This project is licensed for educational use. Please cite if used in research or publication.

