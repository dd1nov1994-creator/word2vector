# Word2Vec Animal Text Example

A small Python example that preprocesses a sample paragraph about animals and
trains a Word2Vec model with Gensim. It demonstrates tokenization, stop-word
removal, word vectors, and finding words similar to `animals`, `dogs`, `cats`,
and `wild`.

## Requirements

- Python 3.9 or newer
- Dependencies listed in [`requirements.txt`](requirements.txt)
- NLTK data packages: `punkt`, `punkt_tab`, and `stopwords`

## Setup

Create and activate a virtual environment, then install the dependencies:

```bash
python -m venv .venv
```

On Windows:

```powershell
.venv\Scripts\Activate.ps1
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

Install Python packages and download the NLTK data:

```bash
python -m pip install -r requirements.txt
python -c "import nltk; nltk.download('punkt'); nltk.download('punkt_tab'); nltk.download('stopwords')"
```

## Run

```bash
python Word2Vector.py
```

The script trains the model and assigns the vocabulary, the `animals` vector,
and the similar-word results to variables in the script.
