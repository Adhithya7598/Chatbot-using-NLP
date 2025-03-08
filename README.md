 ## 🤖 NLP Chatbot

A simple AI chatbot using **Python, NLTK, and Scikit-Learn**, designed to classify user input into predefined **intents** and provide relevant responses. It uses **TF-IDF vectorization** for text processing and **logistic regression** for classification, supporting topics like **greetings, budgeting, and credit scores** while handling unknown inputs gracefully.

---

## 🛠 Tech Stack

### 📌 Backend
- **Python** - Core programming language used for the chatbot logic
- **NLTK** - For natural language processing tasks such as tokenization and lemmatization
- **Scikit-Learn** - Machine learning library used for logistic regression classification
- **NumPy** - For numerical operations and data handling

---

## 🚀 Features
✅ **Intent-based responses** - The chatbot can recognize and classify various intents  
✅ **Text preprocessing** - Uses tokenization, lemmatization, and TF-IDF vectorization  
✅ **Machine learning model** - Implements logistic regression for intent classification  
✅ **Randomized responses** - Makes interactions feel more natural  
✅ **Graceful handling of unknown inputs**  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/chatbot.git
cd chatbot
```

### 2️⃣ Install Dependencies
```bash
pip install nltk numpy scikit-learn
```

### 3️⃣ Download Required NLTK Data
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

### 4️⃣ Run the Chatbot
```bash
python chatbot.py
```

---

## 📌 Example Interaction
```
You: Hello
NLP BOT: Hi there!
You: How can I improve my credit score?
NLP BOT: Improve your credit score by paying bills on time and maintaining low credit utilization.
You: quit
```

---

## 🏗 Project Structure
```
├── chatbot.py       # Main chatbot script
├── intents.json     # Predefined intents and responses
├── README.md        # Project documentation
└── requirements.txt # Required dependencies
```

---

## 🔍 How It Works
1️⃣ **Preprocessing:** Tokenizes and lemmatizes user input using NLTK  
2️⃣ **Vectorization:** Converts processed text into TF-IDF vectors  
3️⃣ **Classification:** Uses logistic regression to predict intent  
4️⃣ **Response Selection:** Randomly picks a response from predefined options  
5️⃣ **Error Handling:** Provides fallback responses for unknown inputs  

---

## 📌 Future Enhancements
🔹 Expand intent categories for broader conversation scope  
🔹 Integrate deep learning models for better intent recognition  
🔹 Add a GUI or integrate with a chatbot web interface  
🔹 Connect to APIs for real-time data fetching (e.g., weather updates)  



