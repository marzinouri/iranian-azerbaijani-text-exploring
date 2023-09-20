# Exploring Text in Iranian Azerbaijani (azb)

## Overview

This GitHub repository contains the code and documentation for an NLP (Natural Language Processing) course assignment focused on exploring text in Azerbaijani (azb). In this assignment, I gathered Wikipedia articles from various categories, conducted data analysis, and developed a keyword extraction tool using the YAKE algorithm.

## Details

### Dataset
I collected Wikipedia articles in Azerbaijani (azb) from five different categories:
1. Literature
2. History
3. Geography
4. Cinema
5. Music

### Data Collection
The repository includes the code and documentation for the data crawling process, explaining how I obtained the Wikipedia articles for each category.

### Data Analysis
I compared the number of articles in each category and analyzed the number of sentences within each category. This analysis helps in understanding the distribution of content across different topics.

### Data Cleansing
I performed various data cleansing operations on the collected text data, including:
- Removal of special characters and symbols
- Elimination of references (e.g., [1], [2])
- Unification of numbers by converting Arabic and Persian numerals to English numerals
- And more, using regular expressions to clean and preprocess the text.

### YAKE Keyword Extraction
I developed a YAKE (Yet Another Keyword Extractor) tool specifically tailored for Azerbaijani (azb) by incorporating language-specific stopwords. This tool is capable of extracting meaningful keywords from text data, which can be valuable for text summarization, topic modeling, and information retrieval.
