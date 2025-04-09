# 🎓 College Enquiry Chatbot 🤖

A simple, intelligent chatbot built using **Python**, **PyTorch**, and **Natural Language Processing (NLP)** techniques. This chatbot is trained to handle frequently asked questions related to college admissions, courses, fees, timings, and general information.

---


---

## 📌 Key Features

✅ Intent-based classification using a custom JSON dataset  
✅ Preprocessing with stemming, tokenization, and bag-of-words  
✅ Feedforward neural network built using PyTorch  
✅ Easy-to-extend for more domains or use-cases  
✅ Custom dataset (`intents.json`) for college-related queries  
✅ Supports training, saving, and deploying the model  

---

## 🛠️ Tech Stack

| Category          | Tools Used                        |
|-------------------|-----------------------------------|
| Programming Lang. | Python 3                          |
| NLP               | NLTK (tokenizer, stemmer)         |
| ML/DL Framework   | PyTorch                           |
| Others            | NumPy, JSON, Torch DataLoader     |

---

---

## 🧠 How It Works

1. Load and preprocess text from `intents.json`
2. Apply stemming and convert patterns into bag-of-words vectors
3. Train a feedforward neural network to predict intent tags
4. Save trained model parameters and metadata to `data.pth`
5. Use the model in a chatbot interface to respond to user queries

---

## 💻 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/NSS21CS007/college-enquiry-chatbot.git
cd college-enquiry-chatbot


