# RNN-for-sentiment-analysis

The project is about Sentiment Analysis, so a recurrent neural network is created to classify a movie review as either positive or negative.

The project consists of these steps:
1. Get the dataset: The Large Movie Review Dataset consisting of 50,000 reviews from IMDb is used.
2. Preprocess the Data: Before giving the data to the RNN all inputs must have the same length, so longer reviews are trimmed and shorter reviews are padded with zeros.
3. Build the Model: This model consists of an embedding layer, a LSTM layer and a fully connected layer.
4. Train the model: The model is trained on a subset of the data first, then it is tested or validated.
5. Test the Model: Validate the model using the test set.
6. Predict Something: This includes translating a review into the corresponding word integers, paddind it and then feedinf it into the model.
