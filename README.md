## ADS 509: Module 3- Group Comparison (Cher vs. Robyn)

## Overview
This repo compares two text groups—song lyrics and Twitter bios—for Cher and Robyn.

## What’s here 
    
    * Data ingestion (lyrics + twitter)
    * Tokenization & normalization (keep hashtags/emojis for Twitter)
    * Descriptive statistics & comparison table
    * “Distinctive tokens” via concentration ratios
    * Word clouds for all four corpora

## Data

expected layout (set as data_location)
<M1 Results>/
├─ lyrics/
│  ├─ cher/*.txt
│  └─ robyn/*.txt
└─ twitter/
   ├─ cher_followers_data.txt
   └─ robynkonichiwa_followers_data.txt

## Environment & Requirements

    * Python 3.9+
    * Jupyter (Anaconda, VS Code, or Colab)
    * Packages: pandas, numpy, nltk, emoji, wordcloud, scikit-learn, matplotlib

## Findings
    
    * Cher: larger corpus, lower lexical diversity; romance/ballad vocabulary.
    * Robyn: smaller corpus, higher lexical diversity; dance/club vocabulary.
    * Twitter bios mirror audience differences; word clouds reinforce the themes.
    
