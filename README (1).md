
# 🍍 Fruit Classifier CNN 🧠

A lightweight Convolutional Neural Network (CNN) built using TensorFlow & Keras to classify Amazonian fruits such as **Açaí, Cupuaçu, Graviola, Guaraná, Pupunha,** and **Tucumã** from image data.

This project was created as a college assignment to demonstrate understanding of CNN fundamentals and model evaluation.

---

## 📁 Project Structure

```
📦 fruit-classifier-cnn/
├── 📓 Fruit_Classifier_CNN.ipynb         # Main Colab Notebook
├── 📦 fruit_classifier_amazon.h5         # Trained model file (.h5 format)
├── 📦 fruit_classifier_amazon.keras      # Optional SavedModel format
├── 🖼️ model_architecture.png             # CNN architecture diagram
├── 📄 README.md                          # This file
```

---

## 🧺 Dataset Classes

- `acai` → Açaí Berry
- `cupuacu` → Cupuaçu
- `graviola` → Soursop
- `guarana` → Guaraná
- `pupunha` → Peach Palm Fruit
- `tucuma` → Tucumã

Dataset was pre-organized into `train/` and `test/` folders.

---

## 🔗 File Navigation

- 🔍 **[Colab Notebook](Fruit_Classifier_CNN.ipynb)** - Full code and results
- 💾 **[Model (.h5 format)](fruit_classifier_amazon.h5)** - Save/Load in Keras
- 🧠 **[Model (.keras format)](fruit_classifier_amazon.keras)** - Alternative format
- 🖼️ **[Model Architecture Image](model_architecture.png)** - Visual structure of the CNN

---

## 📊 Features

- CNN model built from scratch with Conv2D, MaxPooling2D, Flatten, Dense
- Accuracy and loss visualization (40 epochs)
- Classification report with precision, recall, F1-score
- Confusion matrix for performance breakdown
- Dataset preview (image grid)
- `.h5` + `.keras` model saving

---

## 🧪 How to Use

1. Clone this repo or open the notebook in Google Colab.
2. Mount Google Drive & unzip dataset if needed.
3. Train the model and evaluate results.
4. Save, load, or visualize the model structure.

---

## 🚀 Future Enhancements

- Add image augmentation to generalize better
- Increase dataset size with more samples per fruit
- Try transfer learning (e.g., MobileNetV2)
- Deploy using Flask/Streamlit as an interactive web app

---

## 🙋‍♂️ Author

**Siddharth (7even)** — Final Year IT Student 🤓  
_With help from Axa, the ever-elegant AI secretary 💼_

> If this helped you understand CNNs better, don't forget to ⭐ star the repo!
