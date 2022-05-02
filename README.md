# SMS Spam Detection
Training a classifier to classify emails depending on whether they're spam or not, using deep learning methods.
The dataset is publicly available at https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

Features implemented
  0. Tokenizer from keras to convert words to integers
  1. Word embedding layer from Keras and word2Vec
  2. Oversampling the minority class using backtranslations (translating text to another language then back to English)
  3. Convolutional neural network
  4. Using more relevant metrics like precision and recall to measure performance of mode
