🚀 Simple LangChain Chatbot with Groq
A beginner-friendly chatbot app built using LangChain, Groq’s ultra-fast LLMs, and Streamlit. It demonstrates how to connect a Groq-hosted model like llama3-8b-8192 or gemma2-9b-it with a simple LangChain pipeline to build an interactive chat interface.

🧠 Features
Chat with Groq-hosted LLMs (LLaMA 3 or Gemma 2)

Clean and interactive UI using Streamlit

Easy to understand LangChain pipeline with ChatPromptTemplate, ChatGroq, and StrOutputParser

Real-time streaming of model responses

Sidebar settings for model selection and API key input

Session-based chat history

One-click chat clearing

🖥️ Live Demo
⚠️ Not hosted yet. You can run it locally by following the steps below.

📦 Tech Stack
Technology	Purpose
LangChain	Prompt management and chaining
Groq	Ultra-fast inference backend
Streamlit	UI and frontend for interaction
Python	Scripting language



🛠️ Installation & Setup
Clone this repo

git clone https://github.com/yourusername/langchain-groq-chatbot.git
cd langchain-groq-chatbot
Create and activate a virtual environment


python -m venv venv
source venv/bin/activate      # For Linux/macOS
venv\Scripts\activate         # For Windows
Install dependencies

pip install -r requirements.txt
Run the Streamlit app

streamlit run app.py
Enter your Groq API key

Get a free API key from Groq Console