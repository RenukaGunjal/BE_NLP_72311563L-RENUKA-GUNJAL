1.Problem Statement : Perform tokenization (Whitespace, Punctuation-based, Treebank, Tweet, MWE) using nltk
library. Use porter stemmer and snowball stemmer for stemming. Use any technique for
lemmatization. Input / Dataset –use any sample sentence

2. Explanation
Tokenization

Tokenization is the process of breaking text into smaller units called tokens (words or sentences).
The following tokenization techniques are used:

1. Whitespace Tokenization
Splits the sentence based on spaces.
2. Punctuation Tokenization
Separates punctuation marks from words.
3. Treebank Tokenization
A standard tokenizer used in NLP that handles punctuation and contractions properly.
4. Tweet Tokenization
Used to tokenize text from social media such as tweets.
5. MWE Tokenization
Combines multi-word expressions such as Natural Language into a single token.

Stemming
Stemming is the process of reducing a word to its root form.
Two stemming techniques are used:
Porter Stemmer – Common stemming algorithm used in NLP.
Snowball Stemmer – Improved version of Porter Stemmer.

Example:
learning → learn
students → student
Lemmatization

Lemmatization converts words into their dictionary base form (lemma).
Example:
running → run
students → student

3.Conclusion :This assignment demonstrates basic NLP preprocessing techniques such as tokenization, stemming, and lemmatization using the NLTK library in Python. These techniques help in converting raw text into structured form and are widely used in text analysis, machine learning, and natural language processing applications.

It produces meaningful words compared to stemming.
