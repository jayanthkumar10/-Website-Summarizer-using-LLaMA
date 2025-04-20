# 🧠 Website Summarizer using LLaMA (Ollama)

This project uses a **locally hosted LLaMA model via Ollama** to summarize content from any webpage. It fetches a webpage, cleans the content using BeautifulSoup, and sends a prompt to the LLaMA model for summarization in Markdown format.

## 🚀 Features

- Web scraping using `requests` and `BeautifulSoup`
- Local LLaMA model interaction via `Ollama` and `openai` Python client
- Cleans and preprocesses website text by removing navigation, styles, and scripts
- Outputs the result in a clean Markdown summary using IPython's `Markdown` display

## 🛠️ Setup

1. **Install dependencies:**
   ```bash
   pip install requests beautifulsoup4 openai python-dotenv

2. **Start Ollama with LLaMA:**
    ```bash
   ollama run llama3

2.  **Run Jupyter Notebook:**
    ```bash
    jupyter notebook
**File Structure**
-summarizer.ipynb – Main Jupyter Notebook
-README.md – Project documentation

Feel free to ⭐ the repo if you find it helpful!

