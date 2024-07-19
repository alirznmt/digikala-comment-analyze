# Digikala Product Review Analysis using Web Crawling and NLP

## Overview
This project involves analyzing reviews of a specific product on the Digikala website using web crawling and Natural Language Processing (NLP). The collected data is processed using the Hazm library and stored in Elasticsearch for further analysis.

## Product Information
- **Product Name**: Cream Cheese Vili
- **URL**: [Cream Cheese Vili on Digikala](https://www.digikala.com/product/dkp-856812/%D9%BE%D9%86%DB%8C%D8%B1-%D8%AE%D8%A7%D9%85%D9%87-%D8%A7%DB%8C-%D9%88%DB%8C%D9%84%DB%8C-%DA%A9%D8%A7%D9%84%D9%87-350-%DA%AF%D8%B1%D9%85/)

## Steps

### 1. Data Collection
- **Objective**: Crawl the reviews and ratings for the product from the Digikala website.
- **Tools**: Selenium for web crawling, Elasticsearch for data storage.
- **Tasks**:
  - Crawl the product reviews from the provided URL.
  - Save the collected data in an Elasticsearch database.

### 2. Data Processing
- **Objective**: Process the collected data using NLP techniques.
- **Tools**: Hazm library for Persian language processing.
- **Tasks**:
  - **Normalization**: Clean the data, segment sentences and words, and perform stemming and lemmatization.
  - **POS Tagging**: Extract Part-of-Speech (POS) tags for each word and assign them accordingly.
  - **Similarity Analysis**: Implement the Sent2Vec model and calculate the cosine similarity of each candidate with the entire text and other candidates.
  - **Keyword Extraction**: Extract keywords based on cosine similarity.

### 3. Data Storage
- **Objective**: Store the processed data in Elasticsearch.
- **Tasks**:
  - Save the extracted information in separate indices.
  - Provide a detailed explanation of the selection of indices in the report.

## Requirements
- Python 3.x
- Libraries: Selenium, Elasticsearch, Hazm, pandas, selenium, bs4, nltk, conver_numbers, sklearn

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Set up Elasticsearch.
4. Run the provided Python scripts to:
   - Crawl the product reviews using Selenium.
   - Process the data using the Hazm library.
   - Store the data in Elasticsearch.

## Results
- Processed and stored product review data.
- Keyword extraction and similarity analysis using NLP techniques.

## Conclusion
This project demonstrates web crawling, data processing using NLP, and data storage in Elasticsearch. It provides insights into customer reviews and keyword analysis for a specific product on the Digikala website.

