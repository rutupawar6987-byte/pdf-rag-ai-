🧠 PDF Question Answering using LangChain + Groq + Chroma
📄 Overview

This project demonstrates how to extract information from PDFs and answer user questions using LangChain, Groq LLM, and Chroma vector database.
It reads a PDF file (e.g., budget_speech.pdf), splits it into text chunks, embeds the chunks, stores them in a vector database, and retrieves the most relevant context to answer natural language questions.

🚀 Features

PDF text extraction using PyPDF2

Text chunking and preprocessing

Semantic search using Chroma vector store

Question-answering with Groq Llama 3.1 model

Context-aware responses using LangChain chain mechanism

🧩 Tech Stack

Python 3.10+

LangChain

Groq API

Chroma DB

Sentence Transformers

PyPDF2

⚙️ Setup Instructions

1️⃣ Clone the Repository
git clone https://github.com/your-username/pdf-ai-qa.git
cd pdf-ai-qa

2️⃣ Create a Virtual Environment
python -m venv venv
venv\Scripts\activate     # On Windows
# OR
source venv/bin/activate  # On macOS/Linux

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Set Up Environment Variables

Create a .env file in your project folder and add:
GROQ_API_KEY=your_groq_api_key_here

5️⃣ Run the notebook
jupyter notebook rag(padf).ipynb

📁 Project Structure
📦 rag.pdf
 ┣ 📜 rag(padf).ipynb
 ┣ 📜 requirements.txt
 ┣ 📜 .env
 ┗ 📜 README.md
