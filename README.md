# Amazon Sentiment Analysis with BERT and BiLSTM

## Project Overview
This project focuses on sentiment analysis using BERT and BiLSTM models. The goal is to classify Amazon reviews as positive or negative. BERT achieved an accuracy of 90%, while BiLSTM achieved 85%. An ensembling method was used to combine the strengths of both models.

## Models Used

**BERT:** Bidirectional Encoder Representations from Transformers
**BiLSTM:** Bidirectional Long Short-Term Memory

## Dataset
The dataset used for this project can be found [here](https://www.kaggle.com/code/akshitkarande/amazon-reviews-for-sentiment-analysis/input).

## Jupyter Notebook
The main analysis and implementation are done in the Jupyter Notebook Sentiment_Analysis.ipynb. You can use this notebook to:

***Explore Data:*** Load and preprocess the dataset.
***Train Models:*** Train both BERT and BiLSTM models.
***Evaluate Models:*** Visualize accuracy and loss metrics.
***Ensemble Predictions:*** Combine the predictions of BERT and BiLSTM models.

## How to Run
### Clone the repository:
```
git clone https://github.com/felixkwasisarpong/AmazonSentiment.git
cd sentiment-analysis
```
### Install dependencies:
```
pip install -r requirements.txt
```
### Open the Jupyter Notebook:
```
jupyter notebook Sentiment_Analysis.ipynb
```
### Follow the Notebook:
Execute the cells to load the dataset, train the models, and visualize the results.
Results

Accuracy Graph for Bert
![bert accuracy](https://github.com/felixkwasisarpong/AmazonSentiment/blob/main/bert_accuracy.png)
Accuracy Graph for BiLSTM
![BiLSTM accuracy](https://github.com/felixkwasisarpong/AmazonSentiment/main/BiLSTM_accuracy.png)
Loss Graphs for Bert
![bert accuracy](https://github.com/felixkwasisarpong/AmazonSentiment/blob/main/bert_loss.png)
Loss Graphs for BiLSTM
![BiLSTM loss](https://github.com/felixkwasisarpong/AmazonSentiment/blob/main/BiLSTM_loss.png)

## AWS Architecture
To support the training and deployment of these models, AWS SageMaker was used. Below is the architecture diagram:
![Amazon Architecture](https://github.com/felixkwasisarpong/AmazonSentiment/blob/main/Sentiment_Analysis.png)
## Challenges
***High Computational Resources:*** Training BERT requires significant computational power.

***Long Training Times:*** The complexity of BERT results in longer training durations.

***Fine-Tuning Complexity:*** Finding optimal hyperparameters for BERT is challenging.

***Handling Imbalanced Data:*** Sentiment analysis datasets often have class imbalances.

***Memory Consumption:*** BERT’s large model size can lead to high memory usage.

## Conclusion
Ensembling BERT and BiLSTM allowed us to achieve improved sentiment analysis performance. This notebook demonstrates the benefits of combining different model architectures for enhanced predictive capabilities.

## Contributions

Feel free to open issues or submit pull requests. Contributions are welcome!

