# 2022 Billboard Top 20 Global Hits Lyrics Corpus

## Overview
This repository contains a curated corpus of lyrics from the top 20 global hits of 2022 according to the Billboard charts. The aim is to provide a comprehensive dataset for linguistic and cultural analysis of popular music trends.

## Target Audience and Intended Use
This dataset is intended for musicologists, linguists, cultural researchers, and data scientists interested in exploring patterns in contemporary music lyrics. It can be used for sentiment analysis, thematic studies, and linguistic analysis.

## Text Selection Criteria
The lyrics were selected based on their ranking in the 2022 Billboard Global Top 20 chart. This ensures the inclusion of widely recognized and influential songs from various artists and genres.

## Data Collection Process
The lyrics were collected from publicly available websites. Each song's lyrics were manually downloaded and saved in a text format, ensuring accuracy and completeness.

## Cleaning and Preprocessing
The dataset underwent several preprocessing steps:
- Conversion to lowercase to maintain consistency.
- Removal of special characters and punctuation marks.
- Tokenization and removal of common stopwords.

## Tools Used
- Python for preprocessing and analysis.
- NLTK for natural language processing tasks like tokenization and stopword removal.
- Pandas for data manipulation and organization.
- spaCy for advanced NLP tasks.

## Corpus Format
The corpus includes:
- Text files (.txt): Each file contains the lyrics of a single song.
- A compiled CSV file: This file consolidates all the lyrics, with additional linguistic annotations such as tokens and lemmas.

## Columns in the CSV File
- Filename: Name of the original text file.
- Lyrics: Original lyrics as in the text file.
- Processed_Lyrics: Preprocessed lyrics.
- Tokens: Tokenized text of the document.
- Lemmas: Lemmatized text of the document.
- POS: Parts of speech of all tokens in the document.

## Quality Checks
The data underwent quality checks for accuracy and completeness, ensuring that each song's lyrics are correctly represented in the corpus.

## Additional Information
This project is part of an academic assignment aiming to explore modern lyrical trends and their linguistic characteristics. The dataset is publicly available for educational and research purposes.
