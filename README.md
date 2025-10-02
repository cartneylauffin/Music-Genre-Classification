# 🎵 Music Genre Classification

This project focuses on **classifying music tracks into genres** using machine learning and deep learning techniques. The dataset consists of audio features extracted from the **GTZAN Music Genre Dataset**, and a trained model is provided for quick evaluation and inference.

---


## 📊 Dataset

The dataset used is the **GTZAN Dataset for Music Genre Classification**, available on Kaggle:
🔗 [GTZAN Dataset (Kaggle)](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

It contains **10 genres**, each with 100 audio tracks of 30 seconds:

* Blues
* Classical
* Country
* Disco
* Hip-hop
* Jazz
* Metal
* Pop
* Reggae
* Rock

---

## 🤖 Model

A deep learning model was trained on the above dataset.
You can download the **pretrained model** here:

🔗 [Trained Model (Google Drive)](https://drive.google.com/file/d/1POcuJ9uk3tEsisjGdPVdNHx1yJ-rNXyX/view?usp=drive_link)

---

## 🚀 Installation & Usage

### 1️⃣ Clone the repository

```bash
git clone https://github.com/cartneylauffin/Music-Genre-Classification.git
cd Music-Genre-Classification
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Download the trained model

Place the downloaded model file into the project root directory (or update the path in your code).

### 4️⃣ Run the app / notebook

* To retrain or explore: open `model_training.ipynb`.
* To run inference:

```bash
streamlit run app.py
```

---

## 📈 Results

* The model achieves good accuracy in distinguishing between genres using spectrogram-based features.
* Example outputs:

  * Input: Jazz track → Predicted: **Jazz**
  * Input: Rock track → Predicted: **Rock**

---

## 📌 Future Improvements

* Experiment with CNNs and RNNs for better temporal feature learning.
* Expand dataset for robustness.
* Deploy as a web app with a user-friendly interface.

---
