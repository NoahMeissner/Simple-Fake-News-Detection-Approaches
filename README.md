# Simple Fake News Detection Approaches
[![GitHub Repository 1](https://img.shields.io/badge/GitHub-Explore%20the%20Code-blue?logo=github)](https://github.com/NoahMeissner/Simple-Fake-News-Detection-Approaches)



### Abstract
Fake news poses a significant threat to social media and internet users today. To combat this, we explore simple text classification methods to detect 'fake news' using a dataset comprising 134,198 tweets. Our goal is to evaluate the effectiveness of these methods and provide insights into their performance on a large, balanced dataset.

We utilize the dataset from the repository: TruthSeeker-2023, which offers a substantial volume of data for robust analysis and model training.

### Procedure
#### 1. Data Analysis
We begin by performing a preliminary data analysis in the Jupyter Notebook Analysis.ipynb. This step is crucial for familiarizing ourselves with the dataset and understanding its structure and characteristics. We explore various statistical properties and visualize the distribution of fake and real news.

#### 2. Topic Modelling
To gain insights into the topics within the dataset, we conduct topic modelling. This helps us understand the content and thematic distribution of the tweets, identifying key topics that may be indicative of fake news.

#### 3. Model Selection and Comparison
We employ two models for text classification:

- DistilBERT: A distilled version of BERT that balances performance and efficiency.
- BERT Base Uncased: A base version of BERT that provides a comprehensive approach to text understanding.
We train and evaluate both models, comparing their performance in detecting fake news.

### Results



The analysis reveals that the majority of fake news originates from a specific topic group, suggesting a lack of generalizability across different topics. Despite this, the dataset's large size and balanced nature contribute to a high average precision of approximately 99.62%, demonstrating excellent model performance for this specific use case.

This repository illustrates a straightforward approach to utilizing pre-trained models for text classification. It also highlights the impact of various parameters on model performance, offering valuable insights for future applications in fake news detection.


### Clone Repository
```
git clone https://github.com/NoahMeissner/Simple-Fake-News-Detection-Approaches.git
cd Simple-Fake-News-Detection-Approaches
```

### Conclusion
This project demonstrates the effectiveness of simple text classification methods in detecting fake news using a large, balanced dataset. The high precision achieved highlights the potential of these models for practical applications in real-world scenarios. Future work could focus on improving the generalizability of these models across different topics and datasets.
