#LSTM for Sentiment Analysis
  This project demonstrate how to use a Long Short-Term Memory (LSTM) neural network for sentiment analysis. The dataset used is the IMDB reviews dataset, consisting of 50,000 labeled movie reviews, split evenly between positive and negative sentiments. Thehere is two model with different optimizers: RMSprop and Adam, for performance comparison.

---

##Project Features
  -**Dataset** : [IMDB Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews/code)
  -**Model Framework** : Built using KERAS library.
  -**Model Architecture** : Long Short-Term Memory(LSTM) for sequence processing and sentiment classification
  -**Optimizers** = RMSprop and Adam for training the model
  -**Evaluation Metrics** = Accuracy

##Results
  |Optimizer | Test Accuracy|
  |----------|--------------|
  |RMSprop   | 0.8822       |
  |Adam      | 0.8758       |

##Conclusion
  The model with the RMSprop optimizer achieved around 89% accuracy during the training process and approximately 88% during testing/validation. Meanwhile, the model with the Adam optimizer achieved around 95% accuracy during training but approximately 87% during testing/validation. Various results I found in other users' notebooks on Kaggle show similar outcomes. There might be a bias in the dataset. For instance, neutral sentences tend to be predicted as negative by the model, such as the sentence *"The movie plot is terrible, but it had good acting,"* which is predicted as negative. Overall, this model performs quite well in sentiment analysis.
