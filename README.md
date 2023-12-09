# News-Classification-FAKE or REAL

**Dataset Description:**

* The dataset consists of 6,335 entries with four columns: Unnamed, title, text, and label.
* There are no missing values in the dataset.
* The dataset contains both real and fake news articles labeled as "REAL" and "FAKE."

**Data Pre-processing:**

* Text data underwent pre-processing, including converting to lowercase, removing special characters, URLs, punctuation, and numbers.
* Tokenization and lemmatization were performed to clean and normalize the text data.
* Word clouds were generated to visualize the most frequent words in both titles and texts.

**Feature Engineering:**

TF-IDF Vectorizer and Count Vectorizer were used to convert the text data into numerical features for machine learning models.

**Machine Learning Algorithms:**

***Passive Aggressive Classifier:***

* Achieved an accuracy of 92.37% on the test set.
* Precision, recall, and F1-score were high for both classes (REAL and FAKE).
* The confusion matrix showed good performance, with 900 true positives for FAKE and 856 true positives for REAL.

***Naive Bayes Classifier (GaussianNB):***

* Achieved an accuracy of 80.59% on the test set.
* Precision, recall, and F1-score were reported for both classes.
* The confusion matrix indicated 742 true positives for FAKE and 790 true positives for REAL.

***Random Forest Classifier:***

* Achieved an accuracy of 89.64% on the test set.
* Precision, recall, and F1-score were balanced for both classes.
* The confusion matrix showed 873 true positives for FAKE and 831 true positives for REAL.

**Conclusion:**

* The Passive Aggressive Classifier outperformed the other models in terms of accuracy, precision, recall, and F1-score.
* The project successfully demonstrated the use of natural language processing techniques and machine learning algorithms for fake news detection.
* The choice of the best model may depend on specific requirements and considerations such as false positives or false negatives.

**Visualization:**

Bar chart comparing the accuracy of three machine learning models (Passive Aggressive Classifier, Naive Bayes Classifier, and Random Forest Classifier).
Overall, the project showcased the application of machine learning in identifying fake news based on textual features. The models demonstrated strong performance in distinguishing between real and fake news articles.
