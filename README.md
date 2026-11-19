# Conversational-Chatbot-with-LangChain-Groq
Memory, prompt templates, and history trimming in a step-by-step notebook

A Jupyter notebook that builds a chatbot using LangChain and Groq (openai/gpt-oss-20b), covering message history, prompt templates, and conversation trimming.

Features
Chat with the Groq LLM through LangChain
Per-session memory with RunnableWithMessageHistory
Prompt templates with a dynamic language option (e.g. Hindi)
Conversation trimming with trim_messages
Setup
bash
git clone https://github.com/Namanvats24/Conversational-Chatbot-with-LangChain-Groq.git
cd Conversational-Chatbot-with-LangChain-Groq
pip install -r requirements.txt

Create a .env file with your key from the Groq Console:

GROQ_API_KEY=your_groq_api_key_here

Then run:

bash
jupyter notebook chatbot.ipynb
Tech Stack

Python, LangChain, Groq, Jupyter

Author

Naman Vats
