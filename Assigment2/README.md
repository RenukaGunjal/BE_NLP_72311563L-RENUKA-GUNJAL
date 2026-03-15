1. Problem Statement

Implement the Bag of Words approach including count occurrence and normalized count occurrence, compute TF-IDF, and create word embeddings using Word2Vec on the given dataset using Python libraries.

Dataset used: Car dataset (data.csv).

2. Explanation
Bag of Words (Count Occurrence)
Bag of Words is a technique used to convert text into numerical form by counting the frequency of words in a document.

Example:
Sentence:
BMW coupe premium fuel
Bag of Words representation:
Word	Count
BMW	1
coupe	1
premium	1
fuel	1
Normalized Count Occurrence
Normalized count divides each word frequency by the total number of words in the sentence to scale the values between 0 and 1.

Example:
normalized count = word count / total words
This helps compare documents of different lengths.

TF-IDF (Term Frequency – Inverse Document Frequency)
TF-IDF measures the importance of a word in a document compared to the entire dataset.

TF (Term Frequency) → frequency of word in a document
IDF (Inverse Document Frequency) → importance of word across documents
Words that appear frequently in one document but rarely in others get higher weight.

Word2Vec
Word2Vec is a word embedding technique that converts words into dense vector representations.
It captures semantic relationships between words.

Example:
king – man + woman ≈ queen
Word2Vec helps machine learning models understand word similarity and context.


3. Conclusion
In this assignment, different text representation techniques such as Bag of Words, normalized count occurrence, TF-IDF, and Word2Vec were implemented using Python libraries. These methods help convert textual data into numerical form which can be used for further Natural Language Processing and machine learning tasks.
