# Stock Direction Prediction

Stock Direction Predictor, an ensemble of machine learning models designed to predict the direction of stock prices based on Document Term Matrices (DTMs) constructed from the textual content in relevant news articles


## Libraries
- Preprocessing (tokenization, stemming, etc)
	- spaCy
- Classifiers
	- SciKit Learn
		- LogisticRegression
		- RandomForestClassifier
		- GaussianNB
	- NVidia XGBoost
 - Vector/Matrix operations
	- NumPy
	- Pandas

#### Classifier selection:
- Logistic Regression
- XGBoost
- Random Forest
- Naive Bayes

#### Evaluation metrics:
Results from 10-fold cross validation weighted against support
- Accuracy
- F1-score
- Percision
- Recall

## Data
- Scraped news articles related to Apple and Amazon spanning 2018 -> early 2019 in JSON format
- Stock data from Apple(AAPL) and Amazon(AMZN) in CSV format collected in intervals of 5 mins, 15 mins, 30 mins, 1 hr, 4 hrs, and 1 day

## Authors
- [Matin Massoudi](https://github.com/Matin-M)
- [Benjamin Bousquet](https://www.github.com/benbousquet)
- [Adam Coates](https://github.com/adamjcoates)
- [Zi Jia Tan](https://github.com/zijia07912)
- [Ayush Rawat](https://www.github.com/)
- [Zaid Usmani](https://www.github.com/)
