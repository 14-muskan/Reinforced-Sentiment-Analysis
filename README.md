<h1 align="center"> <strong> Reinforced Sentiment Analysis Using Single Convolutions </strong> </h1>

>*The domain of **sentiment analysis** has attracted a lot of recent advancements in improving the existing state-of-the-art methodologies due to the promising impact it has on any corporation's decision making. Existing methods are utilised and a way beyond accurate, however the urge for developing more ideas and practices still remains.*

This project aims to deep dive into the existing technologies and try to bring to table a model that uses **Cost Sensitive Learning** and **Single Convolutions** to address this task.

The models used for the comparative study are:
1. **Multinomial Naive Bayes model** - a probablistic model that works on the likelihood of a input tag
2. **LSTM based model** - uses BiLSTM layers 
3. **CNN based model** - loss function is sparse categorical crossentropy
4. **CNN based reinforced model** - custom loss function that penalises the misclassification by resampling the misclassified sample for lambda times and then calculating the cost.

The idea is to perform a comparative analysis for these models and evaluate each of these on the following metrics
1. F1 score
2. F2 score
3. Macro weighted average
4. Accuracies on train, test and validation data



