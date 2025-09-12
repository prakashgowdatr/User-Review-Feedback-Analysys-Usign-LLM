# User Review Feedback Analysis using LLM

A Python notebook that analyzes Google Play Store reviews using Large Language Models (LLMs) to extract sentiment, keywords, and response metrics.

## Features

- **Review Scraping**: Fetches user reviews from Google Play Store
- **Sentiment Analysis**: Classifies reviews as positive/negative/neutral using RoBERTa
- **Keyword Extraction**: Identifies key topics using KeyBERT
- **Response Analysis**: Calculates reply times and response rates
- **Data Export**: Saves results to CSV files

## Installation

```bash
pip install google-play-scraper keybert rapidfuzz transformers torch pandas numpy scipy
```

## Usage

1. Configure apps to analyze in the `apps` list
2. Run the notebook to process reviews
3. Check generated CSV files for results

## Output Files

- Individual app analysis files (`processed_[app_name]_reviews.csv`) 
- Combined results file (`all_processed_reviews.csv`)
- Analysis report with statistics

## Apps Analyzed

- Uber (`com.ubercab`)
- Ola (`com.olacabs.customer`)
