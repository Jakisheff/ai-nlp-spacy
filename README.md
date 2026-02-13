# NLP spaCy Exercises

This project contains solutions to a series of NLP exercises using spaCy.

## Setup

1.  **Create a virtual environment** (Recommended Python >= 3.9):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Download spaCy models**:
    ```bash
    python3 -m spacy download en_core_web_sm
    python3 -m spacy download en_core_web_md
    ```

## Usage

1.  **Start Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

2.  **Open `task.ipynb`** and run the cells.

## Exercises

-   **Exercise 0**: Environment and libraries
-   **Exercise 1**: Embedding 1 (Word Embeddings)
-   **Exercise 2**: Tokenization
-   **Exercise 3**: Embeddings 2 (Document Embeddings & Similarity)
-   **Exercise 4**: Sentences' similarity
-   **Exercise 5**: Named Entity Recognition (NER)
-   **Exercise 6**: Part-of-speech tags (POS)

## Notes

-   Make sure you have the correct spaCy models installed (`en_core_web_sm` and `en_core_web_md`).
-   Exercise 6 expects a file named `news_amazon.txt`. A sample file is created within the notebook if it doesn't exist.
