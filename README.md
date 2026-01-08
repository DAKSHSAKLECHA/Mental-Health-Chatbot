Mental Health Chatbot

This is a Python-based Mental Health Chatbot that interacts with users through text and provides supportive, empathetic responses.
The chatbot uses Natural Language Processing (NLP) and a trained deep learning model to understand user intent and reply appropriately.

This project was built to learn and apply NLP concepts in a practical, real-world scenario.

About the Project

Mental health is an important topic, and even small supportive conversations can help users feel better.
This chatbot is designed for basic guidance and conversation, not as a replacement for professional mental health services.

Through this project, I learned how to:

Process and clean text data

Train a neural network for intent classification

Structure a complete Python ML project

Work with NLP libraries like NLTK

Features

Text-based chatbot interaction

Intent classification using NLP

Deep learning model trained with TensorFlow

Simple and extendable intent–response system

Beginner-friendly and well-structured code

Technologies Used

Python

TensorFlow / Keras

NLTK

NumPy

JSON

Project Structure
Mental-Health-Chatbot/
│
├── chatbot.py        # Script to run the chatbot
├── train.py          # Script to train the model
├── intents.json      # Intents and responses dataset
├── chatbot_model.h5  # Trained neural network model
├── words.pkl         # Processed vocabulary data
├── classes.pkl       # Intent labels
└── README.md

How It Works

The user enters a message

The text is preprocessed (tokenization, stemming, normalization)

The trained model predicts the intent

A matching response is selected from the dataset

The chatbot replies to the user

How to Run the Project
Step 1: Clone the repository
git clone https://github.com/DAKSHSAKLECHA/Mental-Health-Chatbot.git
cd Mental-Health-Chatbot

Step 2: Install required libraries
pip install tensorflow nltk numpy

Step 3: Train the model (optional)
python train.py

Step 4: Run the chatbot
python chatbot.py

Example Conversation
User: I am feeling anxious today
Bot: I'm sorry you're feeling this way. Do you want to share what's been bothering you?

Future Enhancements

Add more intents and training data

Improve response accuracy

Build a web interface using Flask

Add voice input/output support

Deploy the chatbot online

Disclaimer

This project is created for educational purposes only.
It does not provide medical advice or professional mental health treatment.

Author

Daksh Saklecha

GitHub: https://github.com/DAKSHSAKLECHA

LinkedIn: https://www.linkedin.com/in/dakshsaklecha/
