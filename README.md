# Features

- Extract name
- Extract email
- Extract mobile numbers
- Extract skills
- Extract total experience
- Extract college name
- Extract degree
- Extract designation
- Extract company names

# Installation

- Dependency of spacy

```bash
pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.3.1/en_core_web_sm-2.3.1.tar.gz
pip install importlib-metadata==3.2.0
```

- For NLP operations we use spacy and nltk. Install them using below commands:

```bash
# spaCy
python -m spacy download en_core_web_sm

# nltk
python -m nltk.downloader stopwords
python -m nltk.downloader punkt
python -m nltk.downloader averaged_perceptron_tagger
python -m nltk.downloader universal_tagset
python -m nltk.downloader wordnet
python -m nltk.downloader brown
python -m nltk.downloader maxent_ne_chunker
```

# Supported File Formats

- PDF and DOCx and TXT files are supported on all Operating Systems
