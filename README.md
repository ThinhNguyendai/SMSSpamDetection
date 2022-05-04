# SMS Spam Detection
Training a classifier to classify emails depending on whether they're spam or not, using deep learning methods.
The dataset is publicly available at https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

Features implemented
  0. Tokenizer from keras to convert words to integers
  1. Word embedding layer from Keras and word2Vec
  2. Oversampling the minority class using backtranslations (translating text to another language then back to English)
  3. Convolutional neural network
  4. Using more relevant metrics like precision and recall to measure performance of mode

Files :
- SMSSpamCollection and BacktranslatedSpam contain our dataset and data augmentations respectively.
- SpamClassifiers.ipynb is the main file and contains our results
- MLPSpam.ipynb was our minimum viable project and contains explanations of what the tokenizer from keras does
- UnbalancedDataset.ipynb contains some exploration of the dataset and the preperation to augment the data using machine translation. We also analyze how many words we drop based on vocabulary size and a given fixed length of sequence
