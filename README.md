
# 🍍 Fruit Classifier CNN 🧠

A lightweight Convolutional Neural Network (CNN) built using TensorFlow & Keras to classify Amazonian fruits such as **Açaí, Cupuaçu, Graviola, Guaraná, Pupunha,** and **Tucumã** from image data.

This project was created as a college assignment to demonstrate understanding of CNN fundamentals and model evaluation.

---

## 📁 Project Structure

```
📦 fruit-classifier-cnn/
├── 📓 CNN.ipynb         # Main Colab Notebook
├── 📦 CNN.h5         # Trained model file (.h5 format)
├── 📦 CNN.keras      # Optional SavedModel format
├── 🖼️ architecture.png             # CNN architecture diagram
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

- 🔍 **[Colab Notebook](CNN.ipynb)** - Full code and results
- 💾 **[Model (.h5 format)](CNN.h5)** - Save/Load in Keras
- 🧠 **[Model (.keras format)](CNN.keras)** - Alternative format
- 🖼️ **[Model Architecture Image](architecture.png)** - Visual structure of the CNN

---

## 📊 Features

- CNN model built from scratch with Conv2D, MaxPooling2D, Flatten, Dense
- Accuracy and loss visualization (20 epochs)
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

> If this helped you understand CNNs better, don't forget to ⭐ star the repo!
