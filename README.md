# Text Preprocessing Toolkit
A Python-based Natural Language Processing (NLP) project exploring text preprocessing, linguistic normalization, and word frequency analysis using **NLTK** and **spaCy**.

The project demonstrates how raw text can be transformed into structured, meaningful representations through fundamental NLP preprocessing techniques.

## Overview
Text preprocessing is an essential stage in Natural Language Processing. Raw text often contains inconsistent capitalization, punctuation, commonly occurring words, and variations of the same word.

This project implements a preprocessing workflow to clean and normalize textual data before further analysis.

## Features
- **Tokenization:** Splits text into individual words or tokens.
- **Lowercasing:** Converts text into lowercase for consistent processing.
- **Stopword Removal:** Filters out common words that contribute limited meaning to the analysis.
- **Punctuation Removal:** Removes punctuation marks from the text.
- **Stemming:** Reduces words to their root forms using NLTK's Porter Stemmer.
- **Lemmatization:** Converts words into their dictionary base forms using spaCy.
- **Word Frequency Analysis:** Counts word occurrences and identifies the five most frequent words in a sample text.

## Technology Stack
| Technology | Purpose |
|---|---|
| Python | Core programming language |
| NLTK | Tokenization, stopword removal, stemming |
| spaCy | Linguistic processing and lemmatization |
| pandas | Data manipulation library |
| Jupyter Notebook | Interactive development and execution |

## Project Structure
```text
text-preprocessing-toolkit/
│
├── README.md
├── requirements.txt
└── text_preprocessing.ipynb
```

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/SamyukthaTR/text-preprocessing-toolkit.git
```

Navigate into the project directory:

```bash
cd text-preprocessing-toolkit
```

### 2. Install dependencies
```bash
python -m pip install -r requirements.txt
```

### 3. Download NLP resources
Download the required NLTK resources:

```python
import nltk

nltk.download("punkt")
nltk.download("punkt_tab")
nltk.download("stopwords")
```

Download the spaCy English language model:

```bash
python -m spacy download en_core_web_sm
```

### 4. Run the notebook
1. Open the project directory in Visual Studio Code.
2. Ensure the Python and Jupyter extensions are installed.
3. Select the Python environment containing the required dependencies.
4. Open `text_preprocessing.ipynb`.
5. Execute the notebook cells sequentially.

## Workflow
The project follows a simple NLP preprocessing pipeline:

```text
Raw Text
   |
   v
Tokenization
   |
   v
Lowercasing
   |
   v
Punctuation Removal
   |
   v
Stopword Removal
   |
   v
Stemming and Lemmatization
   |
   v
Word Frequency Analysis
```

## Learning Outcomes
This project provides practical experience with:
- Fundamental NLP preprocessing operations.
- Text normalization using NLTK and spaCy.
- Differences between stemming and lemmatization.
- Identifying frequent terms in textual data.
- Working with Python-based NLP libraries and Jupyter Notebooks.

## Author
**Samyuktha T R**
[GitHub Profile](https://github.com/SamyukthaTR)
