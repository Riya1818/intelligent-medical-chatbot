# 🩺 Medical Chatbot – AI-Powered Symptom Checker

An intelligent medical chatbot that interacts with users to understand their symptoms, predict possible health conditions, and recommend appropriate medications. Designed for basic diagnostic support and healthcare assistance using machine learning and natural language processing.

---

## 🚀 Features

- 💬 Conversational interface for symptom input
- 🧠 Symptom-based disease prediction using ML models
- 💊 Medicine recommendations based on predicted condition
- 📍 (Optional) Integration with location services to suggest nearby medical stores
- 🔐 Secure handling of API keys using environment variables

---

## 🛠️ Tech Stack

- Python
- Flask / Streamlit (Frontend Interface)
- Scikit-learn / Pandas (ML Backend)
- dotenv (`python-dotenv` for secure API handling)
- External Medical API (e.g., Infermedica, OpenAI)

---

## 📦 Installation

1. Clone the repository-
   git clone https://github.com/your-username/medical-chatbot.git
   cd medical-chatbot

2. Install Required Packages-
   Make sure you have Python installed (preferably version 3.8+), then install the dependencies:
   pip install -r requirements.txt

3. Set Up API Key-
   Create a file named .env in the root directory and add your API key:
   API_KEY=your_actual_api_key

 4. Run the Application-
    If using Flask:
    API_KEY=your_actual_api_key

    Then open your browser and go to:
    http://localhost:5000

5. Interact with the chatbot-
   Enter your symptoms in the chat interface.
   Get predicted diseases and medicine recommendations.

## 🧪 Usage
Run the chatbot:
python app.py

## 🛡️ Security
Your API key is kept safe by:
Storing it in a .env file
Excluding .env from GitHub via .gitignore
Providing a .env.example for easy setup

## 🙌 Acknowledgements
Inspired by the need for accessible AI-based healthcare tools
Built as part of a personal learning project to explore medical NLP and recommendation systems




