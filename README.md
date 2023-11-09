8# Amazon-Sentiment-Analysis
This is the repository in which I have performed Sentiment analysis on Amazon review dataset.
This project is developed to analyse the reviews of the customers on Amazon and divide them into positive, negative so that we can understand that is, if that product is good or not. Where 1 represents Positive review ans 0 represents Negative reviews.
## Dataset Link:
https://www.kaggle.com/datasets/bittlingmayer/amazonreviews

## About Dataset
- This dataset consists of a few million Amazon customer reviews (input text) and star ratings (output labels) for learning how to train fastText for sentiment analysis.
- The idea here is a dataset is more than a toy - real business data on a reasonable scale - but can be trained in minutes on a modest laptop. link: https://www.kaggle.com/datasets/bittlingmayer/amazonreviews

## Tools Used
- Google Colab
- Python
- GitHub
- Kaggle
- Laptop
- Internet
## Colab File Link
https://colab.research.google.com/drive/1pf8xAVGLflUA1A-IO3qRCP8DF7yQkZV6?usp=sharing

## Tokenizer file link:
https://drive.google.com/file/d/10M-z03b2nmEYukWdyTweW5o0qPbLfhSc/view?usp=sharing

## Model file link:
https://drive.google.com/file/d/1WLkod-wBaN0260D9fG8vclY6Mk9DPmFK/view?usp=sharing

## Visualizations
### Graph 1
The graph below shows us the distribution of the Train Labels.
![Graph1](https://github.com/AbhishekGit23/Amazon-Sentiment-Analysis/assets/123490715/5a5396b6-16c1-4d12-8dad-49e696722284)

### Graph 2
The graph below shows us the distribution of the Test Labels.
![Graph2](https://github.com/AbhishekGit23/Amazon-Sentiment-Analysis/assets/123490715/2312983b-b5a8-4987-a1d9-aa10a30ab1e5)

## WordCount Graph
![WordCount](https://github.com/AbhishekGit23/Amazon-Sentiment-Analysis/assets/123490715/527d252c-3004-4a4f-90e5-831168e5796c)

## Confusion Matrix
The below matrix shows us the probabilities of True Positive, True Negative, False Positive and False Negative
![CM](https://github.com/AbhishekGit23/Amazon-Sentiment-Analysis/assets/123490715/d0a379ee-0a90-492b-aa9b-9bab6d7ad0b3)

## Model Training
In the model training part I have tried using LSTM with SpatialDropout1D. I have used the rate as 0.2 and the number of units as 32. For this model I have used Sigmoid Activation Function.

## Model Compiling 
- For compiling I have used the loss function as-"Binary_Crossentropy", optimizer as "adam" and metrics is "accuracy".
- Then for fitting the model I have used 2 epochs and 0.1 as validation split.
the first batch size of 101250 gave the loss of 0.1781 and accuracy of 0.9309, validation loss as 0.1518 and validation accuracy as 0.9425.
The second batch size of 101250 gave the loss of 0.1455 and accuracy of 0.9454, validation loss as 0.1455 and validation accuracy as 0.9452.

## Conclusion 
So, I conclude that our model had an accuracy of 0.94389 and loss as 0.14847.This means that our model is giving a good results for the sentiments. 

So, this is the project that I have prepard for Amazon Sentiment Analysis. Hope you liked it.
Thank You.
