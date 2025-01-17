![logo](https://images.pexels.com/photos/518543/pexels-photo-518543.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
# Topic Modeling on BBC News Articles

## Table of Contents
- [Introduction](#introduction)
- [Business Context](#business-context)
- [Dataset Description](#dataset-description)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Results](#results)
- [Contributing](#contributing)
  

## Introduction
This repository contains the code and documentation for a project on topic modeling using unsupervised machine learning algorithms on a collection of BBC news articles. The goal of this project is to identify major themes or topics present in the news articles and assess their correspondence with the different tags available.

## Business Context
In this project, we aim to discover and analyze significant themes across various BBC news segments, including business, entertainment, politics, sports, and technology. By leveraging clustering algorithms like Latent Dirichlet Allocation (LDA), we intend to provide insights for content recommendation, trend analysis, and understanding user interests in the news domain.

## Dataset Description
The dataset consists of news articles categorized into different segments. The segments are business, entertainment, politics, sports, and technology. The raw data is available in [data folder](data/) in .txt format. We will create an aggregate dataset by combining all the news articles for topic modeling.


## Usage
1. Preprocess the data:
- Combine the news articles from different segments into a single dataset.
- Handle any missing values or inconsistencies in the data.
- Perform text cleaning, tokenization, and stopword removal.

2. Exploratory Data Analysis (EDA):
- Visualize the distribution of articles across segments.
- Analyze word frequency and article lengths.

3. Feature Extraction:
- Convert the preprocessed text data into numerical representations using TF-IDF or Bag of Words.

4. Topic Modeling:
- Apply LDA or LSA to identify major themes in the news articles.
- Evaluate the quality of the extracted topics using coherence scores.

5. Verification:
- Compare the identified topics with the available tags to assess their correspondence.

## Project Overview
- [scripts](scripts/): Contains Python scripts for data preprocessing, topic modeling, and evaluation.
- [notebooks](notebooks/): Jupyter notebooks for EDA and topic modeling.
- [data](data/): Raw data in folders having .txt format.
- [results](results/): Visualizations and evaluation results.
- [requirements.txt](requirements.txt): List of required Python packages.

## Results
The project findings, including the identified topics and their alignment with tags, will be summarized in a report or presentation.

## Contributing
Contributions to this project are welcome! If you have any suggestions or improvements, please feel free to create an issue or submit a pull request.

