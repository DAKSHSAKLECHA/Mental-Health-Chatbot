# Mental Health Chatbot

A Python-based chatbot that uses Natural Language Processing (NLP) and a deep learning model to provide supportive and empathetic responses for mental health related conversations.

---

## Features

- Text-based chatbot interaction  
- Intent classification using NLP  
- Trained TensorFlow deep learning model  
- Easy to extend by adding new intents  
- Simple and clean project structure  

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- NLTK  
- NumPy  
- JSON  

---

## Project Structure

Mental-Health-Chatbot/
├── chatbot.py        # Run the chatbot  
├── train.py          # Train the model  
├── intents.json      # Intents and responses  
├── chatbot_model.h5  # Trained model  
├── words.pkl         # Vocabulary data  
├── classes.pkl       # Intent labels  
└── README.md  

---

## How It Works

1. User enters a message  
2. Text preprocessing is applied (tokenization, stemming)  
3. Model predicts the user intent  
4. Response is selected based on intent  
5. Chatbot replies to the user  

---

## Installation

```bash
git clone https://github.com/DAKSHSAKLECHA/Mental-Health-Chatbot.git
cd Mental-Health-Chatbot
pip install tensorflow nltk numpy
````

---

## Usage

```bash
python train.py
python chatbot.py
```

---

## Example

```
User: I feel stressed
Bot: I'm sorry you're feeling this way. Do you want to talk about it?
```

---

## Disclaimer

This chatbot is built for learning purposes only and does not provide medical or professional mental health advice.

---

Author

Daksh Saklecha

GitHub: https://github.com/DAKSHSAKLECHA

LinkedIn: https://www.linkedin.com/in/dakshsaklecha/

