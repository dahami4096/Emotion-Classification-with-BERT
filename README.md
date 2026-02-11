# 🧠 BERT-Based Text Emotion Classifier

A transformer-based Natural Language Processing (NLP) project that classifies short English text into six emotion categories using a fine-tuned BERT model. This project demonstrates deep learning, transfer learning, and handling class imbalance in real-world text data.

---

## 📌 Project Overview

Understanding human emotions from text is an important task in NLP with applications in:

- Sentiment Analysis  
- Mental Health Monitoring  
- Customer Feedback Analysis  
- Chatbots & Conversational AI  

This project fine-tunes a pre-trained **BERT (Bidirectional Encoder Representations from Transformers)** model to classify text into the following six emotions:

- 😊 Joy  
- 😢 Sadness  
- 😠 Anger  
- 😨 Fear  
- ❤️ Love  
- 😲 Surprise  

### ✅ Model Performance

- **Test Accuracy:** 93%  
- **Macro F1-Score:** 0.88  

---

## 🏗️ Model Architecture

- Pre-trained BERT encoder (`bert-base-uncased`)
- Tokenization using BERT tokenizer
- Fully connected classification head
- Softmax output layer
- Cross-entropy loss
- Fine-tuned on labeled emotion dataset

---

## 🛠️ Tech Stack

- Python  
- PyTorch  
- Hugging Face Transformers  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  

---

## 📂 Project Structure

```
emotion-classifier/
│
├── emotion-classifier-ai-project.ipynb
├── dataset/
├── models/
├── results/
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/emotion-classifier.git
cd emotion-classifier
```

### 2️⃣ Create a virtual environment (Recommended)

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install torch transformers scikit-learn pandas numpy matplotlib jupyter
```

---

## 🚀 How to Run

Open Jupyter Notebook:

```bash
jupyter notebook emotion-classifier-ai-project.ipynb
```

Run all cells to:

- Load and preprocess dataset  
- Tokenize text using BERT tokenizer  
- Fine-tune BERT model  
- Evaluate model performance  
- Generate metrics and visualizations  

---

## 📊 Evaluation Metrics

The model was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score (Macro)  
- Confusion Matrix  

The model successfully captures semantic nuance and emotional context in text data.

---

## 📈 Key Features

✔ Fine-tuned transformer-based NLP model  
✔ Handles class imbalance  
✔ High generalization performance  
✔ Clean training & evaluation pipeline  
✔ Performance visualization  

---

## 💡 Future Improvements

- Deploy as REST API using FastAPI  
- Build web interface using Streamlit  
- Implement multi-label emotion detection  
- Experiment with RoBERTa / DeBERTa  
- Hyperparameter tuning  

---

## 📎 Applications

- Social media monitoring  
- Customer feedback analysis  
- Mental health text screening  
- Conversational AI systems  

---

## 👩‍💻 Author

**Dahami Nethsarani**  
Computer Engineering Graduate | AI & Full-Stack Developer  

GitHub: https://github.com/your-username  
LinkedIn: https://linkedin.com/in/your-link
