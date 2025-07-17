# 🍍 Fruit Classifier CNN 🧠

A lightweight Convolutional Neural Network (CNN) built using TensorFlow & Keras to classify Amazonian fruits such as **Açaí, Cupuaçu, Graviola, Guaraná, Pupunha,** and **Tucumã** from image data.

This was developed as a college assignment for learning core CNN principles, model evaluation, and fruit classification on a small custom dataset.

---

## 📂 Dataset
The dataset used is called **`ds_frutas_am`**, containing 6 categories of fruits with around 15 images per class, split into `train/` and `test/` folders.

### 🧺 Classes:
- `acai` → Açaí Berry
- `cupuacu` → Cupuaçu
- `graviola` → Soursop
- `guarana` → Guaraná
- `pupunha` → Peach Palm Fruit
- `tucuma` → Tucumã

---

## 🚀 Features

- 📸 Dataset visualizer
- 🧠 CNN with Conv2D, MaxPooling2D, Flatten, Dense
- 📊 Accuracy and loss visualization
- 📋 Classification report with precision, recall, and F1-score
- 💾 Model saving in `.h5` format
- 🔍 Model architecture visualization (`model.summary()` & optional `plot_model()`)

---

## 🛠️ Technologies Used

- Python 3.x
- TensorFlow / Keras
- Matplotlib
- NumPy
- Scikit-learn
- Google Colab (for free GPU training)

---

## 🧪 How to Run

1. Upload the dataset to your Google Drive.
2. Open the `CNN.ipynb` notebook in Google Colab.
3. Mount your Drive and unzip the dataset if needed.
4. Train the model (`epochs=20`) and evaluate.
5. Save model and analyze metrics.

---

## 📉 Results

The model achieves good accuracy despite the small dataset size, and shows promising classification results across all 6 fruit classes. Graphs and reports included in the notebook.

---

## 📌 Future Improvements

- Increase dataset size for better generalization.
- Use data augmentation to handle low data.
- Try transfer learning with MobileNet or ResNet.
- Deploy as a web app using Streamlit or Flask.

---

## 🙋‍♂️ Author

**Siddharth** (a.k.a 7even)  
Final Year IT Student | Passionate about AI, Full-Stack, and Problem Solving  

---

## 🌟 Star this repo if it helped you learn!
