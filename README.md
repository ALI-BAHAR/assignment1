# assignment1
Text Classification using Wikipedia: Coffee vs. Non-Coffee
Description
This project classifies a given text as either coffee-related or non-coffee-related by using Wikipedia articles as the source of data. 
The classification is done using Python with the Scikit-learn library and the Wikipedia API.
Operational Structure
•	Fetch text data from Wikipedia: Coffee-related and non-coffee-related texts are gathered from Wikipedia using the Wikipedia API.
•	Preprocess the text data: This involves text tokenization and feature extraction using TF-IDF.
•	Build and train the classifier: A Naive Bayes model is built and trained on the processed text data to distinguish between coffee and non-coffee categories.
•	Evaluate the model: The model’s performance is measured using evaluation metrics such as precision, recall, and F1-score.
•	Classify new texts: A function is implemented to classify new, unseen texts.
Technologies Used
•	 Python
•	Scikit-learn
•	Wikipedia API
•	Naive Bayes Classifier
