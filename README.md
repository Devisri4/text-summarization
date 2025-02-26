# Text Summarization Project

## Abstract
Text summarization is a natural language processing (NLP) technique that condenses a large body of text into a shorter version while preserving its essential information. This project explores both extractive and abstractive summarization approaches using the **Latent Semantic Analysis (LSA)** method and the **T5 Transformer model**, respectively. Additionally, a word cloud visualization and **ROUGE evaluation metrics** are incorporated to assess the quality of the generated summaries.

## Introduction
With the exponential growth of textual data in various fields, the need for efficient summarization techniques has become essential. This project leverages NLP methodologies to generate concise and meaningful summaries of text data. The implementation focuses on extractive summarization, which selects key sentences from the original text, and abstractive summarization, which rephrases the content in a human-like manner.

## Objectives
- Implement **extractive summarization** using the **LSA algorithm**.
- Perform **abstractive summarization** using a **T5 Transformer model**.
- Preprocess text using **tokenization, stopword removal, and lemmatization**.
- Generate a **word cloud visualization** to highlight important words in the text.
- Evaluate summarization quality using **ROUGE scores**.

## Requirements
### Libraries and Dependencies
The project requires the following Python libraries:
- **NLTK** (Natural Language Toolkit) - for text preprocessing
- **Sumy** - for extractive summarization
- **Transformers** (Hugging Face) - for abstractive summarization
- **WordCloud** - for generating a visual representation of frequent words
- **ROUGE** - for evaluating summarization performance
- **Matplotlib** - for displaying the word cloud
- **Subprocess** - for handling package installations dynamically

## Implementation
1. **Preprocessing**: Tokenization, stopword removal, and lemmatization are applied to clean the input text.
2. **Extractive Summarization**: The **LSA algorithm** extracts the most informative sentences.
3. **Abstractive Summarization**: The **T5 Transformer model** generates human-like summaries.
4. **Visualization**: A **word cloud** highlights the most frequent words.
5. **Evaluation**: The **ROUGE metric** compares generated summaries against the original text.

## Results
- Extractive summarization provides a concise yet verbatim summary of key sentences from the input text.
- Abstractive summarization generates a more natural and human-like summary by rephrasing the content.
- The word cloud effectively visualizes the most significant words in the input text.
- ROUGE scores help assess the quality of the summaries by comparing them to the original text.

## Conclusion
This project demonstrates the effectiveness of **extractive and abstractive** summarization techniques in NLP. While extractive summarization retains key sentences, abstractive summarization generates more coherent and concise summaries. The use of **word clouds** and **ROUGE evaluation** further enhances the analysis. Future improvements could involve fine-tuning transformer models for domain-specific summarization tasks.

## Future Scope
- Implement **BERT-based** summarization for better contextual understanding.
- Integrate a **user interface** for interactive summarization.
- Improve **multi-document summarization** capabilities.
- Optimize the summarization model for **faster execution and better accuracy**.

---
**Author:** [M.DEVI SRI]  
**Date:** [26-02-2025]  
**Repository:** [https://github.com/Devisri4/text-summarization/tree/f1b17e27750b98027c9c522f35d0394f7d4e032e]

