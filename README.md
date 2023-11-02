# NLP

# Understanding the vaccine stance of Italian tweets and addressing language changes through the COVID-19 pandemic: Development and validation of a machine learning model

Social media is increasingly being used to express opinions and attitudes toward vaccines. The vaccine stance of social media posts can be classified in almost real-time using machine learning. 

We describe the use of a Transformer-based machine learning model for analyzing vaccine stance of Italian tweets, and demonstrate the need to address changes over time in vaccine-related language, through periodic model retraining.

The model that classified the data most similarly to humans was XLM-Roberta-large, a multilingual version of the Transformer-based model RoBERTa. The model hyper-parameters were tuned and then the model ran five times. The fine-tuned model with the best F-score over the validation dataset was selected. Running the selected fine-tuned model on just the first test dataset resulted in an accuracy of 72.8% (F-score 0.713). Using this model on the second test dataset resulted in a 10% drop in accuracy to 62.1% (F-score 0.617), indicating that the model recognized a difference in language between the datasets. On the combined test datasets the accuracy was 70.1% (F-score 0.689). Retraining the model using data from the first and second datasets increased the accuracy over the second test dataset to 71.3% (F-score 0.713), a 9% improvement from when using just the first dataset for training. The accuracy over the first test dataset remained the same at 72.8% (F-score 0.721). 

Regular training of machine-learning models with recent data is advisable to maximize accuracy.

https://www.frontiersin.org/articles/10.3389/fpubh.2022.948880/full

