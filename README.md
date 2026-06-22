# 📘 Deep Learning Text Generation using RNN, LSTM, and GRU

## 📖 Overview

This project demonstrates **text generation using Deep Learning sequence models**:

* Vanilla RNN (Recurrent Neural Network)
* LSTM (Long Short-Term Memory)
* GRU (Gated Recurrent Unit)

The objective is to learn how neural networks capture grammar, sentence structure, and contextual dependencies from text data and generate meaningful text sequences through next-word prediction.

This project is designed for **students and beginners** who want to understand the fundamentals of sequence modeling and Natural Language Processing (NLP).

---

## 🎯 Problem Statement

Design and implement deep learning models capable of learning the underlying structure and contextual dependencies of a text corpus to generate coherent text sequences.

The project compares:

* Training Loss
* Learning Behavior
* Text Generation Quality
* Model Performance

using:

1. Vanilla RNN
2. LSTM
3. GRU

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```text
Assignment_5/
│
├── week_5_Dinesh_Jangir_pu.ipynb
├── README.md
└── requirements.txt
```

---

## 📥 Dataset

A small sample text corpus is used for demonstration purposes.

Example:

```text
deep learning is transforming artificial intelligence
recurrent neural networks are useful for sequential data
lstm helps remember long term dependencies
gru is faster and simpler than lstm
text generation models predict the next word
```

The corpus can easily be replaced with:

* Shakespeare text
* Story datasets
* Song lyrics
* Chatbot conversations
* Custom text files

---

## 🔤 Data Preprocessing

The following preprocessing steps are performed:

1. Text Tokenization
2. Vocabulary Creation
3. Integer Encoding
4. N-gram Sequence Generation
5. Sequence Padding
6. Input-Output Preparation

---

## 🧠 Models Implemented

### 1. Vanilla RNN

A basic recurrent neural network that processes sequential data.

**Advantages**

* Simple architecture
* Easy to understand

**Limitations**

* Suffers from vanishing gradients
* Struggles with long-term dependencies

---

### 2. LSTM (Long Short-Term Memory)

Uses memory cells and gating mechanisms to retain important information over longer sequences.

**Advantages**

* Handles long-term dependencies
* Better context understanding
* Improved text generation

---

### 3. GRU (Gated Recurrent Unit)

A simplified version of LSTM with fewer parameters.

**Advantages**

* Faster training
* Lower computational cost
* Performance comparable to LSTM

---

## 📊 Model Architecture

Each model consists of:

```python
Embedding Layer
↓
RNN / LSTM / GRU Layer
↓
Dense Output Layer (Softmax)
```

---

## 📈 Performance Evaluation

Training loss is tracked and compared across all three models.

Visualization includes:

* RNN Loss Curve
* LSTM Loss Curve
* GRU Loss Curve

This helps analyze convergence behavior and learning efficiency.

---

## ✍️ Text Generation

After training, the models generate text using a seed phrase.

Example:

```python
generate_text(model, "deep learning", 5)
```

Possible output:

```text
deep learning models can generate meaningful sentences
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Dinesh-jangir/Assignment_5.git
```

Move into the project directory:

```bash
cd Assignment_5
```

Install dependencies:

```bash
pip install tensorflow numpy matplotlib notebook
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
week_5_Dinesh_Jangir_pu.ipynb
```

Run all cells sequentially.

---

## 📚 Learning Outcomes

After completing this project, you will understand:

* Text Tokenization
* Sequence Generation
* Word Embeddings
* Recurrent Neural Networks
* LSTM Architecture
* GRU Architecture
* Next Word Prediction
* Text Generation using Deep Learning

---

## 🔮 Future Improvements

* Train on larger datasets
* Use pre-trained word embeddings
* Implement Bidirectional LSTM
* Use Transformer-based architectures
* Build an AI Story Generator
* Develop a Chatbot using sequence models

---

## 👨‍💻 Author

**Dinesh Jangir**

B.Tech (Computer Science Engineering)
Poornima University, Jaipur

GitHub: https://github.com/Dinesh-jangir

---

## 📜 License

This project is created for educational and learning purposes.
