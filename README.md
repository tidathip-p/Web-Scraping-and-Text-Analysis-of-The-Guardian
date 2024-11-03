# Web Scraping and Text Analysis of International Media Coverage on Regional Conflicts

## Project Overview

This project analyzes the coverage of a prolonged regional insurgency by an international media outlet over two decades, focusing on **word frequency**, **sentiment analysis**, and **topic modeling**. Utilizing web scraping and text analysis techniques in **R**, this analysis aims to explore how international media coverage might affect perceptions of ongoing regional conflicts.

## Table of Contents

- [Background](#background)
- [Technologies Used](#technologies-used)
- [Data Collection](#data-collection)
- [Data Processing](#data-processing)
- [Analysis Techniques](#analysis-techniques)
- [Results](#results)
- [Installation](#installation)

## Background

The representation of regional conflicts in international media plays a crucial role in shaping public perception and policy responses. This project seeks to provide insights into the themes and sentiments presented in the media coverage over time.

## Technologies Used

- **R**: For data analysis and visualization
- **rvest**: For web scraping
- **dplyr**: For data manipulation
- **tidytext**: For text processing and analysis
- **ggplot2**: For data visualization
- **topicmodels**: For topic modeling
- **tm**: For text mining

## Data Collection

Data was collected using web scraping techniques to gather articles related to the regional insurgency from the selected international media outlet. The URLs of the articles were compiled, and their content was extracted programmatically.

## Data Processing

The collected data underwent several preprocessing steps, including:

- Text cleaning (removing punctuation, stopwords, etc.)
- Tokenization
- Creation of a Document-Term Matrix (DTM)

## Analysis Techniques

1. **Word Frequency Analysis**: Identifying the most common words used in the articles to understand dominant themes.
2. **Sentiment Analysis**: Evaluating the tone of the articles (positive, negative, or neutral) using sentiment lexicons.
3. **Topic Modeling**: Using Latent Dirichlet Allocation (LDA) to identify underlying topics within the articles.

## Results

The results of the analysis provide insights into the themes and sentiments prevalent in the media coverage over the two decades. Visualizations illustrate the most common words, sentiment scores by article, and top terms associated with identified topics.

## Installation

To run this project locally, ensure you have R installed along with the necessary packages. You can install the required packages using the following command in R:

```R
install.packages(c("rvest", "dplyr", "stringr", "tm", "tidytext", "ggplot2", "tidyr", "topicmodels", "SnowballC"))
