# Level 2, Task 5: Autocomplete and Autocorrect

**Notebook:** `Autocomplete_Autocorrect_Analytics.ipynb`

## Data
Uses the tweet text from the cleaned dataset made in Level 1 Task 3 (`cleaned_election_tweets.csv`). To use a book from Project Gutenberg instead, set `CORPUS_TXT = "your_book.txt"` in the first code cell. Only pandas, numpy, matplotlib and seaborn are needed; the algorithms are written from scratch.

## What is covered
Preprocessing, word-frequency chart, bigram and trigram next-word models, word completion, three autocorrect methods (Levenshtein, Damerau/Norvig, and Norvig with context), precision and recall for both, a confusion matrix, error analysis, and a discussion of limits compared with a production keyboard.

## Results
| | Result |
|---|---|
| Autocomplete (right word in top 3) | unigram baseline 9.7%, bigram 23.1%, trigram 27.5% |
| Autocorrect accuracy (600 typos) | Levenshtein 69.3%, Damerau/Norvig 82.7%, with context 87.5% |
