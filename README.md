📘 MAKE IT ASAAN

"Make It Asaan" is a Streamlit web application that uses AI to summarize research papers and extract key insights in a blog-style format. Simply upload a PDF paper, and the app will generate a clear, concise summary using cutting-edge LLMs and retrieval-based QA.


🚀 FEATURES

🔍 Upload any research paper in PDF format

🤖 Summarization powered by LLaMA 3 via Groq

🧠 Automatically extracts:

Problem Statement
  
Methodology
  
Key Takeaways
  
Conclusion
  
📎 Uses LangChain, HuggingFace Embeddings, and FAISS for document retrieval

🌐 Built with Streamlit for an intuitive web interface



🛠️ TECHNOLOGIES USED

Python

Streamlit – Web app framework

LangChain – LLM orchestration

FAISS – Vector database for fast retrieval

HuggingFace Transformers – Embedding model

ChatGroq (LLaMA 3) – For answer generation



💡 FUTURE IMPROVEMENTS

Support for other file types (DOCX, TXT)

Custom question input by the user

Multilingual summaries

Caching & faster load times



▶️ Getting Started
1. Clone the Repository
   
        git clone https://github.com/yourusername/make-it-asaan.git
        cd make-it-asaan

2. Install Dependencies

        pip install -r requirements.txt

Or manually install the key packages:

    pip install streamlit langchain faiss-cpu sentence-transformers langchain_groq


3. Add Your Groq API Key
Create a .streamlit/secrets.toml file:

        GROQ_API_KEY = "your_groq_api_key_here"

4. Run the App

           streamlit run app.py


🤝 Contributing

Feel free to open issues, suggest improvements, or contribute!
