# Make It Asaan

"Make It Asaan" is a Streamlit web application that uses AI to summarize research papers and extract key insights in a blog-style format. Simply upload a PDF paper, and the app will generate a clear, concise summary using cutting-edge LLMs and retrieval-based QA.


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```

## Getting Started

1. Clone the Repository

```python
git clone https://github.com/yourusername/make-it-asaan.git
cd make-it-asaan
```

2. Install Dependencies

```python
pip install -r requirements.txt
```

Or manually install the key packages:

```python
pip install streamlit langchain faiss-cpu sentence-transformers langchain_groq
```

3. Add Your Groq API Key
Create a .streamlit/secrets.toml file:

```python
GROQ_API_KEY = "your_groq_api_key_here"
```

4. Run the App

```python
streamlit run app.py
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
