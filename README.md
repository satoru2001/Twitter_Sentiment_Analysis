# Twitter_Sentiment_Analysis
<img src='twitter.jpg' height=256px width=450px>

## Libraries and API's
- Keras
- Scikit Learn
- Pandas
- MatplotLib
- Beautiful Soup
## Datasets
- [Tweets](http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip)
- [Embeddings](http://nlp.stanford.edu/data/glove.twitter.27B.zip)
## Info
- The dataset contains 1600000 rows with 6 coulmns
- Dropped unwanted columns,Preprocessed Sentences from the dataset
- Used transfer Learning for embedded matrix [Glove 100d](http://nlp.stanford.edu/data/glove.twitter.27B.zip)
- The model contain a mix of Conv1D,BiDirectional LSTM,Dense Layers followed by Dropout,BatchNormalization layers
- Achieved ~78% Training accuracy, ~80% Test accuracy(model ran for 5 epochs)
- Got F1 Score of 0.80
### Prepocessing
- converted unconevrted HTML with BS4
- Removed usernames,Urls,BOM's
- Removed #,Numbers
- Removed StopWords
