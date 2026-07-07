🤖 CodeAlpha FAQ Chatbot

A simple AI-powered FAQ Chatbot built using Python, NLTK, and Scikit-learn. The chatbot uses Natural Language Processing (NLP) techniques such as tokenization, lemmatization, TF-IDF vectorization, and cosine similarity to understand user queries and return the most relevant response from a predefined FAQ dataset.

📌 Features
💬 Interactive command-line chatbot
🧠 Uses NLP for text preprocessing
🔍 Matches user questions using TF-IDF and Cosine Similarity
📚 Predefined FAQ knowledge base
❓ Handles unknown questions gracefully
🍎 Compatible with macOS, Windows, and Linux
🛠️ Technologies Used
Python 3.x
NLTK
Scikit-learn
NumPy
📂 Project Structure
Chat_Bot_For_FAQs/
│
├── Chat_Bot_For_FAQs.py      # Main chatbot program
├── README.md                 # Project documentation
└── requirements.txt          # Required libraries (optional)
📦 Installation
1. Clone the repository
git clone https://github.com/yourusername/Chat_Bot_For_FAQs.git
cd Chat_Bot_For_FAQs
2. Install dependencies
pip install nltk scikit-learn numpy

Or

pip install -r requirements.txt
▶️ Run the Chatbot
python Chat_Bot_For_FAQs.py
💬 Sample Interaction
==================================================
🤖 CodeAlpha FAQ Chatbot Initialized
Type 'quit' or 'exit' to stop the chat.
==================================================

You: hours
Bot: We are open from 9 AM to 5 PM, Monday to Friday.

You: reset password
Bot: You can reset your password by clicking on 'Forgot Password' on the login screen.

You: refund
Bot: Yes, we offer a 30-day money-back guarantee on all our products.

You: contact support
Bot: You can contact support via email at support@codealpha.tech.

You: located
Bot: CodeAlpha is a leading software development company, operating remotely and globally.

You: exit
Bot: Goodbye! Good luck with your CodeAlpha projects.
📚 FAQs Included
What are your working hours?
How can I reset my password?
Do you offer refunds?
How do I contact support?
Where is the company located?
🧠 How It Works
Stores predefined FAQs and answers.
Preprocesses text using:
Lowercasing
Tokenization
Lemmatization
Converts FAQ questions into TF-IDF vectors.
Converts the user's query into a TF-IDF vector.
Calculates cosine similarity between the query and stored FAQs.
Returns the most relevant answer if the similarity score exceeds a threshold; otherwise, asks the user to rephrase.
🚀 Future Enhancements
GUI using Tkinter or Streamlit
Voice-based interaction
Larger FAQ database
Database integration (SQLite/MySQL)
Web deployment using Flask or Django
Deep learning models for improved accuracy
👨‍💻 Author

Ayan Raj

GitHub: https://github.com/yourusername
LinkedIn: https://linkedin.com/in/yourusername
📜 License

This project is developed for educational purposes as part of the CodeAlpha Artificial Intelligence Internship. Feel free to modify and use it for learning.
