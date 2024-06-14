# Simple-Fake-News-Detection-Approaches

### Abstract
Fake news is a major threat to social media and internet users today. Therefore, there are different ways to filter and analyse them.
For this reason, we use simple text classification methods to see how well they can detect 'fake news' using the small dataset.

We use the data set from the repo: https://github.com/KaiDMML/FakeNewsNet/tree/master?tab=readme-ov-file

### Procedure

First, we perform a simple data analysis in Jupyter Notebook Analysis.ipynb to familiarise ourselves with the data.
Later, we find a DistilBert and a Bert Base Uncased Model and compare the results with each other.

### Results

The analysis shows that the existing fake news mainly originates from one topic group. This means that we cannot generalise for other groups.
Furthermore, the data set is very small (20,000 data points) and unbalanced, which was taken into account when training the model. Therefore, the average precisions of approx. 83-85% 
are not particularly high.

However, the repository shows a simple way of using finger-tuned models for text classification and the effects of various parameters on the performance of these models.
of these models.
