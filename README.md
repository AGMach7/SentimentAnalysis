# Sentiment Analysis using PySpark

This project focuses on sentiment analysis using PySpark, a powerful distributed computing framework for big data processing. The goal of this project is to classify textual data into positive or negative sentiments using a machine learning approach.

## Prerequisites

To run this project, you need the following dependencies:

- Python (version 3.11.1)
- PySpark (version 3.3.1)

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine:

```
git clone https://github.com/AGMach7/SentimentAnalysis.git
```

2. Navigate to the project directory:

```
cd SentimentAnalysis
```

3. Download the sentiment analysis dataset from the following link: http://ai.stanford.edu/~amaas/data/sentiment/. Place the dataset files in the appropriate directory.
   
4. Open the Jupyter Notebook file `SentimentAnalysis.ipynb` using Jupyter Notebook:

```
jupyter notebook SentimentAnalysis.ipynb
```

5. Follow the instructions provided in the notebook to train the sentiment analysis model and perform sentiment classification on text data.

## Dataset

The dataset used for training and testing the sentiment analysis model can be downloaded from this link: http://ai.stanford.edu/~amaas/data/sentiment/. This dataset consists of labeled movie reviews, categorized as positive or negative sentiment.

## Model

This project employs two machine learning algorithms for sentiment analysis:
  - SVM (Support Vector Machine)
  - Logistic Regression
    
Both models are built and trained using PySpark's machine learning library. The models learn the patterns and relationships between the input text and the corresponding sentiment labels to classify unseen text data.

## Results

The evaluation results of the sentiment analysis models are as follows:
 - SVM:
   - Accuracy: 85.3%
 - Logistic Regression:
   - Accuracy: 90.6%
