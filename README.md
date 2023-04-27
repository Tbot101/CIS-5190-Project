# CIS-5190-Project

This 5190 Project looks at the [Amazon Fine Food Review Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?datasetId=18&sortBy=voteCount)

Some of the initial cells may need to be edited to work with the path to `cleaned_reviews.csv`

The files in this repository are described as follows:

---------- BERT.ipynb ----------

What is in it:
- Dataset loading
- Loading in Pytorch
- BERT (intialization, training, testing)
  - trainer
  - loading data
  - validation
  - sentimental LSTM

How to run it:
- run each cell in order

---------- Baseline.ipynb ----------

What is in it:
- import dataset
- Dummy classifier (baseline predictions)
- baseline predictions shifted (50% positive, 50% negative)

How to run it:
- run each cell starting from the top incrementally to ensure everything is imported and runs properly

---------- Logistic_Regression_and_FFNN.ipynb ----------

What is in it:
- Logistic Regression
  - with CountVectorizer
  - with n-grams and TFIDF
- Feed-forward Neural Network
  - training
  - evaluation

How to run it:
- run each cell in order

---------- Time_Shift_CIS_519.ipynb ----------

What is in it:
- implement time shift on loaded data
- run models on shifted data
  - Logistic Regression
  - Feed-forward neural network

How to run it:
- run each cell in order
- you better not run it in a different order :3
