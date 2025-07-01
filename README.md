# Twitter-Sentimental-Analysis-Using-NLP-and-Python

## Objective:
**Used Python libraries such as Pandas for data operations, Seaborn & Matplotlib for 
data visualization, EDA tasks, NLTK to extract and analyze the information, Sklearn for model 
building and performance visualization, to predict our different categories people’s mindsets.**

## Tools & Libraries
- **Tools:** Python & Jupyter notebook
- **Libraries:** pandas, numpy, string, re, nltk, tensorflow, sklearn & warnings 

## Problem Statement
1. Read the Data from the Given excel file. 
2. Change our dependent variable to categorical. ( 0 to “Neutral,” -1 to “Negative”, 1 to “Positive”)
3. Do Missing value analysis and drop all null/missing values 
4. Do text cleaning. (remove every symbol except alphanumeric, transform all words to lower case, and remove punctuation and stopwords )
5. Create a new column and find the length of each sentence (how many words they contain)
6. Split data into dependent(X) and independent(y) dataframe 
7. Do operations on text data  \
    Hints: 
    - Do one-hot encoding for each sentence (use TensorFlow) 
    - Add padding from the front side (use Tensorflow) 
    - Build an LSTM model and compile it (describe features, input length, vocabulary size,    information drop-out layer, activation function for output, ) 
    - Do dummy variable creation for the dependent variable 
    - split the data into tests and train  
8. Train new model 
9. Normalize the prediction as same as the original data(prediction might be in decimal, so whoever is nearest to 1 is predicted as yes and set other as 0) 
10. Measure performance metrics and accuracy 
11. print Classification report  

## Process:
1. **Data Cleaning & Preprocessing** 
2. **Feature Engineering** 
3. **Text Tokenization and Embedding**  
4. **Sentiment Label Mapping**  
5. **Model Building with LSTM**  
6. **Training and Evaluation**

## Key Features
- Cleaned and tokenized real tweet data
- Handled multi-class classification (Positive, Negative, Neutral)
- Built a sequential LSTM model for text prediction
- Used categorical encoding and padding to handle variable sentence lengths
- Evaluated performance using precision, recall, and F1-score

## Outcome:
**The model predicts the sentiment of a tweet, helping businesses and analysts gauge user opinions and emotional tone. This can be used for product feedback, public opinion tracking, and more.**
