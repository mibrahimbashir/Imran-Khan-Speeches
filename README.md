# IK Speeches Rhetorical Analysis and Model Building

By Muhammad Ibrahim Bashir

## Table of Contents

1. Introduction
2. Dataset
3. Objective
4. Methodology
5. Results
6. Conclusion

## Introduction

This project explores the speeches of Imran Khan, the former Prime Minister of Pakistan, from a data science perspective. The key objectives include:

- Preprocessing textual data for natural language processing (NLP) tasks
- Building topic models to discover latent topics in the speeches
- Conducting sentiment analysis to gauge the emotional tone of the speeches
- Performing lexical diversity analysis to study the richness of vocabulary
- Visualizations with each analysis

## Dataset

The dataset compiles 67 speeches delivered by Imran Khan across various events, both domestic and international. The speeches cover a wide range of topics, including governance, foreign policy, welfare, economic development, and the socio-political landscape of Pakistan.

You can download the dataset on **kaggle** by visisting this [link](https://www.kaggle.com/datasets/zusmani/imran-khans-speeches/data)

## Kaggle Notebook

This notebook was written in kaggle environment. You can find the notebook [here](https://www.kaggle.com/code/mibrahimbashir/lda-with-analysis-vizs-of-imran-khan-speeches)

## Objective

The objective of this project is to **analyze the speeches** of Imran Khan using NLP techniques and visualize the results to gain insights into his **rhetorical style** and the topics he discussed during his tenure as Prime Minister.

## Methodology

The methodology includes:

- **Data preprocessing**: Removing speech annotations, punctuation marks, and stop words from the text data
- **Tokenization and lemmatization**: Converting text into numerical representation using bag-of-words and TF-IDF approaches
- **Topic modeling**: Training LDA model on the preprocessed data to discover latent topics
- **Sentiment analysis**: Using TextBlob and VADER to gauge the emotional tone of the speeches
- **Lexical diversity analysis**: Using TTR, MTLD, and HDD to analyze the richness of vocabulary

## Results

The results of the analysis are presented in the following sections:

- **Topic Modeling**: The LDA model identified 5 topics, which are visualized using a bar chart and a word cloud.
- **Sentiment Analysis**: The sentiment analysis revealed a slightly positive sentiment in the speeches, with a peak in 2021 and a decline in 2023.
- **Lexical Diversity**: The lexical diversity analysis showed fluctuations in TTR, MTLD, and HDD values over the years, with a significant dip in 2021 and an increase in 2022.

## Conclusion

This project provides insights into the rhetorical style and topics discussed by Imran Khan during his tenure as Prime Minister of Pakistan. The results of the analysis can be used to understand the tone and language used by the former Prime Minister and how it changed over time.

## License

This project is licensed under the MIT License.
