# 📰 Fake News Detection Using Deep Learning

This project implements a deep learning-based system to detect and classify news articles as real or fake. It leverages natural language processing and deep learning techniques including LSTM, BiLSTM, and a hybrid CNN-BiLSTM model to analyze and predict the authenticity of news content.

---

## 📂 Dataset

- **Source:** Labeled dataset of real and fake news articles
- **Size:** Approx. 44,000+ records
- **Target:** Binary label indicating real (1) or fake (0)

---

## 🧹 Preprocessing Steps

1. **Text Cleaning:** Lowercasing, stopword removal
2. **Tokenization & Padding:** Using Keras tokenizer with max sequence length
3. **Feature Extraction:**
   - **TF-IDF Vectorization** for initial representation
   - **GloVe Embeddings** for semantic representation
4. **Label Encoding:** Convert categorical target to binary integers

---

## 🧠 Deep Learning Models

| Model         | Description                                   | Accuracy  |
|---------------|-----------------------------------------------|-----------|
| LSTM          | Captures sequential dependencies              | ~97.5%    |
| BiLSTM        | Bidirectional LSTM for richer context         | ~98.1%    |
| CNN-BiLSTM    | CNN for feature extraction + BiLSTM for flow  | **98.41%** |

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

---

## ✅ Key Features

- Combined **traditional TF-IDF features** with **deep learning architectures**
- Used **GloVe embeddings** for semantic understanding of words
- Achieved high performance with CNN-BiLSTM architecture
- Identified important text patterns for fake news detection

---

## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- NLTK
- Scikit-learn
- Pandas, NumPy, Matplotlib

---

## 🔮 Future Scope

- Integrate transformer-based models (e.g., BERT)
- Build a web app interface using Streamlit or Flask
- Extend to multi-class classification (e.g., satire, opinion)

---

## 📬 Contact

**Satyam Prashant**  
B.Tech AI & DS – IIITDM Kurnool  
📧 satyamprashant2002@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/satyam-prashant/)
