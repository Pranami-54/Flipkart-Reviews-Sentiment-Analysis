# Flipkart Reviews Sentiment Analysis

This project performs sentiment analysis on Flipkart product reviews to classify them as **Positive**, **Negative**, or **Neutral** based on the review text. The sentiment is determined using **VADER Sentiment Analysis**, a lexicon and rule-based tool specifically designed for social media text, which works well on short, informal reviews.

## Project Overview

This project aims to analyze customer feedback on Flipkart, which can help in understanding user sentiment toward various products. By categorizing reviews into sentiment labels, businesses can gain insights into the general public opinion of their products and improve decision-making.

### Key Features:
- **Sentiment Analysis**: The reviews are classified into Positive, Negative, or Neutral categories based on the sentiment score.
- **Data Visualization**: The sentiment distribution is visualized using bar charts to showcase the overall feedback on the products.
- **Compatibility**: The code is designed to work with CSV files containing Flipkart product reviews, including product names, reviews, and ratings.

## Dataset

The dataset consists of the following columns:
1. `Unnamed: 0`: Index column (can be ignored).
2. `Product_name`: Name of the product.
3. `Review`: Text content of the product review.
4. `Rating`: Rating given to the product on a scale from 1 to 5.

Sample of the dataset:

| Product_name | Review | Rating |
|--------------|--------|--------|
| Lenovo Ideapad | Best under 60k, Great performance... | 5 |
| DELL Inspiron | My wife is so happy with the product... | 5 |

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`: For handling the dataset.
- `nltk`: For sentiment analysis using VADER.
- `matplotlib`: For data visualization.
- `seaborn`: For creating enhanced plots.

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn nltk vaderSentiment
```
