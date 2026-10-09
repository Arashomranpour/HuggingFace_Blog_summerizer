<div align="center">

# 📝 Blog Post Summarizer

**Scrape any blog article with BeautifulSoup and summarize it with a Hugging Face transformer.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗_Transformers-FFD21E)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-scraping-informational)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ How it works

`postSummarization_usingHuggingFace_andBeautifulSoup.ipynb`:

1. 🌐 Downloads a blog URL with `requests`.
2. 🍜 Extracts the headline and paragraphs (`h1`, `p`) with **BeautifulSoup**.
3. 🤖 Summarizes the extracted text with the Hugging Face `summarization` pipeline.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/HuggingFace_Blog_summerizer.git
cd HuggingFace_Blog_summerizer
pip install transformers torch beautifulsoup4 requests jupyter
jupyter notebook postSummarization_usingHuggingface_andBeautifulSoup.ipynb
```

Change the `url` variable in the notebook to summarize a different article.

## 📁 Project Structure

```
.
└── postSummarization_usingHuggingface_andBeautifulSoup.ipynb
```

## 🛠️ Tech Stack

`Hugging Face Transformers` · `BeautifulSoup` · `requests`
