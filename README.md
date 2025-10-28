# 🧠 PDF RAG AI — Intelligent Q&A over Documents  

This project demonstrates **Retrieval-Augmented Generation (RAG)** using:
- 🧩 **LangChain** — for text chunking and pipeline building  
- ⚡ **Groq LLM** — for fast, low-latency answers  
- 🗂️ **Chroma Vector DB** — for document retrieval  

## 📄 How it works
1. Extracts text from a PDF (`budget_speech.pdf`)  
2. Splits content into chunks  
3. Stores embeddings in **Chroma**  
4. Uses **LLM** to answer user queries based on the document  

## 🚀 Run it Locally
```bash
pip install -r requirements.txt
python RAG(PDF).ipynb


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
