
# CRF sequence tagging for Movie Queries (NLP project assignment)

The dataset used in this project contains movie trivia questions and answers text data.
Each instance of data is a word sequence, with the target class for each word labelled
in an **IOB** (Inside, Outside, Beginning) format.

The goal of this project is to:
- Optimise the performance of a Conditional Random Field sequence tagger in classifying each word of the sequence to its corresponding label.


## Libraries

- NLTK
- NumPy
- Pandas
- Matplotlib
- Sklearn


## Pipeline

- Preprocessing (adding POS tags to text data)
- Text feature extraction (POS-tagging, capitalisation, numbers, punctuation, suffixes, prefixes, previous words, next words)
- Training


## Results

A training macro average f1 score of 0.68, and test macro average f1 score of 0.63 was 
obtained.

