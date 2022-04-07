# SMSSpamDetection
Training a classifier to classify emails depending on whether they're spam or not, using deep learning methods.
The dataset is publicly available at https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

Things to try to improve the model :
  1. Word embedding : the one we use has no reason to be good, we just order words by how often they appear, but it doesn't help us locate the words
  2. How to handle unbalanced dataset : discarding so many observations is not a great idea, we could also adapt our criterion to evaluate model (instead of just error rate)
  3. Another architecture for network
     1. Convolutional network (why does it work ?)
     2. LSTM or any sequential network architecture
