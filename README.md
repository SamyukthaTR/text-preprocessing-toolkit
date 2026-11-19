# NLP Lab 1 – Text Preprocessing and Word Frequency Analysis

## Objective
This lab demonstrates fundamental Natural Language Processing (NLP) preprocessing techniques using NLTK and spaCy, followed by word-frequency analysis.

## Tasks Covered
### Task 1: Environment Setup
- Install Python and the required Python libraries.
- Download the NLTK tokenization and stopword resources.
- Install the spaCy English language model (`en_core_web_sm`).

### Task 2: Text Preprocessing
The notebook demonstrates:
1. Tokenization
2. Lowercasing
3. Stopword removal
4. Punctuation removal
5. Stemming using NLTK's `PorterStemmer`
6. Lemmatization using spaCy

### Task 3: Word Frequency Analysis
- Preprocess a separate sample text.
- Count the frequency of the remaining words.
- Display the five most frequent words.

## Requirements
- Python 3.7 or later
- NLTK
- spaCy
- pandas
- spaCy English model: `en_core_web_sm`

Install the Python packages:

```bash
python -m pip install -r requirements.txt
```

Download the required NLTK resources and spaCy model. You can run these commands in VS Code's notebook cells:

```python
import nltk

nltk.download("punkt")
nltk.download("punkt_tab")
nltk.download("stopwords")
```

```python
!python -m spacy download en_core_web_sm
```

## How to Run
1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Install the Python and Jupyter extensions if they are not already installed.
4. Open `CB.PS.I5DAS23016_Lab1.ipynb`.
5. Select the Python environment where the requirements are installed.
6. Run the notebook cells from top to bottom.

## Repository Contents
- `CB.PS.I5DAS23016_Lab1.ipynb` – Jupyter Notebook containing the lab implementation.
- `nlp_lab1.py` – Python script exported from the notebook (if included).
- `requirements.txt` – Python package dependencies.

## Note
The text samples are used to demonstrate preprocessing and frequency analysis. Their inclusion does not imply independent verification of any factual claims they may contain.

## Author
Samyuktha T R
