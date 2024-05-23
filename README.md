# Twitter-Sentiment-Analysis
This is a project on Text Sentiment Analysis. The dataset from Kaggle represents the comments of customers of the Virgin Atlantic Airlines in the United States of America, in the year 2015.
In this project, I have used the `Tokenizer` and `Pad_sequences` to preprocess for modelling. The `Tokenizer` is inbuilt in Keras and fits the dataset, which splits the sentences into words and creates a dictionary of all unique words found and their uniquely assigned integers. Each sentence is converted into an array of integers representing all the individual words present in it.
A Keras sequential model is built. The model is compiled with `binary cross-entropy` loss and `adam` optimizer. Since we have a binary classification problem, `binary cross-entropy` loss is used. `Accuracy` is used as the primary performance metric.
The model achieved an accuracy of around 95%.
