# Processing-Disaster-Tweets
Twitter has become an important communication channel in times of emergency. The omnipresence of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programmatically monitoring Twitter.  No much clarity on whether words are announcing disaster. 

# Key Parameter
Keyword : Particular keyword from tweet
Target : denotes whether tweet is about disaster(1) or no (0)
Location : Location from where tweet was posted 
Id : Unique Identifier for tweets
Text: text of the tweet

# Methodology 
1. Exploratory Data Analysis  : Identifying Missing Values Cardinality, Identified Target Distrbution Meta Features. 
2. Prediction Report 
3. Target &  N Gram : Uni Grams , Bi Gram and Tri Gram
4. Cross Validation(F-Score) BERT Architecture and Layer 
5. Embedding , Text Cleaning and Mislabbeled Samples

# BERT and Disaster Detector Architecure 
1. Transformer Encoder reads entire word sequence at once, instead of text input sequentially

2. Wrapper incorporates Cross Validation and metrics like Mean F score, Accuracy, Precision, F1 Score Recall etc.)

3.Parameters like learning Rate, Epochs, and Batch_size can be used for controlling BERT learning process


