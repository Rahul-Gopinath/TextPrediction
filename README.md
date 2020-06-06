# TextPrediction

Our goal is to train a model to emulate the speaking style of the text it is trained on.
Dataset: https://www.kaggle.com/c/spooky-author-identification

Steps to be followed:
1. Arrange training data
Here we use the Keras Tokenizer. We remove the punctuation, convert the words to lower case, assign unique integers to each word and then substitute the words with the integers in the training set.
2. Model Architecture
The model will have 5 layers: an embedding layer, 2 stacked LSTM layers, a Dense layer with ReLU activation as well as another Dense layer with Softmax activation
3. Testing
We test the model with various test cases
