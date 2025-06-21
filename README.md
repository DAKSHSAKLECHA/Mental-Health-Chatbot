# 🧠 Mental Health Chatbot
A simple Python-based chatbot that provides supportive responses for mental health and well-being. It uses machine learning to classify user intents and generate empathetic replies based on predefined patterns.

# 📁 Project Structure

| File         | Description                                                    | 
| chatbot.py   | Main script that runs the chatbot.                             | 
| train.py     | Model training script using intents and NLP processing.        | 
| intents.json | Contains labeled intents and patterns the chatbot understands. | 
| chatbot_model.h5 | The trained model saved in HDF5 format.                    | 
| words.pkl/classes.pkl | Pickled data for tokenized words and intent classes.                                                                        | 
| .venv/       | Virtual environment setup for dependencies.                    | 
| .gitignore   | Specifies files to ignore in version control.                  | 
| pyvenv.cfg   | Configuration file for the virtual environment.                | 


# 🚀 Getting Started
- Clone the repo
git clone https://github.com/DAKSHSAKLECHA/Mental-Health-Chatbot.git

- Activate virtual environment
source .venv/Scripts/activate  # Windows

- Install dependencies
pip install -r requirements.txt

- Train the model (optional)
python train.py

- Run the chatbot
python chatbot.py


✨ Features
- Intent recognition using NLP and TensorFlow/Keras.
- Empathetic responses tailored to user mental states.
- Easy to expand with more intents and responses.

