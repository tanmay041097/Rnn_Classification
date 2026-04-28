# 🎬 IMDb Sentiment Analysis using Simple RNN

This project implements a **Recurrent Neural Network (RNN)** model to perform **sentiment analysis** on the IMDb movie reviews dataset. The model classifies reviews as **positive** or **negative**.

---

## 🚀 Project Overview

Sentiment analysis is a key task in Natural Language Processing (NLP). In this project, we:

- Use the IMDb dataset
- Preprocess textual data
- Build and train a Simple RNN model
- Evaluate model performance

---

## 📂 Project Structure


simple_rnn_imdb/
│
├── data/
├── notebooks/
├── model/
├── src/
│ ├── preprocessing.py
│ ├── model.py
│ └── train.py
│
├── requirements.txt
├── README.md
└── main.py


---

## 🧠 Model Architecture

- Embedding Layer  
- Simple RNN Layer  
- Dense Layer  
- Sigmoid Activation  

---

## 📊 Dataset

- IMDb Movie Reviews Dataset  
- 50,000 reviews  
- Binary classification: Positive / Negative  

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/simple_rnn_imdb.git
cd simple_rnn_imdb
2. Create virtual environment
python -m venv venv
venv\Scripts\activate
3. Install dependencies
pip install -r requirements.txt
▶️ Usage
python main.py
🔄 Workflow
Load dataset
Preprocess text (tokenization, padding)
Train RNN model
Evaluate performance
Predict sentiment
📈 Results
Accuracy: ~85–88% (depending on tuning)
🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
Scikit-learn
📌 Future Improvements
Use LSTM / GRU
Hyperparameter tuning
Model deployment (Flask / FastAPI)
Add attention mechanism
