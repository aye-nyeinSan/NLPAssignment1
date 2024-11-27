# NLPAssignment1
Text Preprocessing and Tokenization in NLP

This repository demonstrates how to clean text from an input file and perform tokenization to extract the top 10 most common words. The implementation is written in Python and designed for use in a Jupyter Notebook, allowing for clear separation of code blocks and corresponding outputs.

## Features
Clean and preprocess text data.
Tokenize the text into individual words.
Perform frequency analysis to identify the top 10 most common words.
Measure the execution time for each processing step.

# Setup and Requirements
(Python Version)
Python 3.x

## External Libraries
re: For performing regular expression operations (e.g., cleaning text).
collections.Counter: For counting word frequencies efficiently.
time: For calculating execution times.



# How to use 
Download Input File

Download the input file (alice29.txt) by extracting it from the canterbury.tar.gz file available at Canterbury Corpus.
Run the Notebook

Open the Jupyter Notebook and execute each code cell step by step to:
Clean the text data.
Tokenize the cleaned text into words.
Perform frequency analysis to identify the top 10 words.
Generated Output Files The following files will be created in the same directory:

cleaned.txt: Contains the cleaned text.
words.txt: A list of all tokenized words (one word per line).
top10words.txt: A file listing the top 10 most frequent words with their counts.
time_compares.txt: A log of execution times for each processing step.

