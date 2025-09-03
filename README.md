# web-text-mining-nlp
Scrapes an HTML page, cleans text, tokenizes (sentences/words), removes stopwords, plots frequency distributions, builds a word cloud, runs simple sentiment analysis, and searches aerospace-related terms.

## How to run

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

pip install -r requirements.txt
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
python html_pages_nlp.py
