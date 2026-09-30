# How Does Text Preprocessing Affect Sentiment Classification?

A simple experiment that shows how different levels of text preprocessing change the accuracy of a sentiment classifier.

## What this project does
We take movie reviews and apply 4 different preprocessing levels:
- **Level 0**: Almost no cleaning (raw text)
- **Level 1**: Lowercase + remove punctuation
- **Level 2**: Level 1 + remove stopwords
- **Level 3**: Level 2 + lemmatization

Then we train the same model (Multinomial Naive Bayes + TF-IDF) and compare accuracy.

## How to run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook notebook/preprocessing_impact.ipynb
4. Run all cells