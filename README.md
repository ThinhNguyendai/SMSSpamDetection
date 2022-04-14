# SMS Spam Detection
Training a classifier to classify emails depending on whether they're spam or not, using deep learning methods.
The dataset is publicly available at https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

Features implemented
  1. Word embedding layer from Keras, seems to make a huge difference in terms of performance
  2. Oversampling the minority class using backtranslations (translating text to another language then back to English)
  3. Convolutional neural network (not sure what this changes but nice to try)
  4. Using more relevant metrics like sensitivity and specificity to measure performance of model

Things to try to improve the model (Thu 14th April 2022) :
  1. LSTM or any sequential network architecture
  2. **The dataset is old** : spam messages have become significantly more refined over the years
  3. Understanding how the model detects differences : "looking hunder the hood"
