
# Text Summarization using NLP and Transformers

A lightweight extractive text summarization tool built with Python. The project uses **NLTK** for natural language processing and automatically falls back to a custom tokenizer when NLTK resources are unavailable.

## 🚀 Features

* Extractive text summarization
* NLTK-based sentence and word tokenization
* Automatic fallback tokenizer
* Stopword removal
* Word frequency analysis
* Sentence scoring and ranking
* Error handling and robustness
* Beginner-friendly code structure

## 📌 How It Works

1. Preprocesses the input text.
2. Removes stopwords and punctuation.
3. Calculates word frequencies.
4. Scores each sentence based on important words.
5. Selects the highest-scoring sentences.
6. Returns a concise summary.

## 🛠️ Technologies Used

* Python 3
* NLTK
* Regular Expressions (re)
* Heapq

## 📊 Example Output

### Input

Artificial intelligence has transformed numerous industries in recent years. Machine learning algorithms are now capable of processing vast amounts of data and making complex decisions. Natural language processing has enabled computers to understand and generate human-like text. Computer vision systems can now recognize objects and faces with remarkable accuracy.

### Summary

Natural language processing has enabled computers to understand and generate human-like text. Researchers are working to ensure AI systems remain transparent and accountable. The future of AI holds both exciting possibilities and important challenges to address.

## 🎯 Future Improvements

* Support for PDF and DOCX files
* Web-based interface using Flask
* Transformer-based summarization
* Multi-language support
* Custom summary length control



