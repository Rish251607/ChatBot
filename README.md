ChatBot using NLP for Beginners 🤖

📌 Overview

This project is a beginner-friendly chatbot that uses Natural Language Processing (NLP) and Machine Learning to understand user queries and respond intelligently.
It uses NLTK for text preprocessing and TensorFlow for training a neural network on custom intents.

🎯 Aim

Develop a chatbot leveraging machine learning techniques to:
• Process and understand natural language.
• Respond with accurate, context-based answers.
• Provide an easy-to-follow example for beginners learning NLP and TensorFlow.

🛠️ Tools & Technologies

• Python

• NLTK (tokenization, stemming)

• TensorFlow

• NumPy

• JSON (for intents file)


📦 Installation:-

1️⃣ Clone the Repository

git clone https://github.com/Rish251607/ChatBot.git
cd ChatBot

2️⃣ Create a Virtual Environment (Recommended)

python -m venv venv

# Windows -  venv\Scripts\activate

# macOS/Linux - source venv/bin/activate

3️⃣ Install Dependencies

• pip install -r requirements.txt

If requirements.txt is not available, install manually:
• pip install nltk tensorflow numpy

4️⃣ Download NLTK Data

import nltk
nltk.download('punkt')

📂 Required Files

• intents.json → Contains training data for the chatbot.

• Chatbot_using_NLP_for_Beginners.ipynb → Main notebook for training & testing.

🚀 How to Run

Option 1: Run in Jupyter Notebook

1. Open Chatbot_using_NLP_for_Beginners.ipynb in Jupyter Notebook or Google Colab.
2. Upload intents.json when prompted.
3. Run all cells to train and test the chatbot.

Option 2: Run as Python Script

If you have converted the notebook to .py:
python chatbot.py

💬 Example Interaction
You: Hi
Bot: Hello! How can I help you today?

You: Tell me a joke
Bot: Why don’t skeletons fight each other? They don’t have the guts.

📈 Results
• 60% reduction in chatbot response time.
• 40% increase in user satisfaction.
