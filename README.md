# Sentiment-Analysis--Hindenberg_Report_on_Adani

# <span style = 'color:blue'> Problem statement : Perform sentiment analysis on Hindenberg report, data fetching directly from twitter</span>
**Sentiment analysis is the process of identifying feelings and emotions expressed in words, through ML or AI**

**Project Pipeline**

Various steps in completing project are

- **Import Necessary Dependencies**
- **Read and Load the Dataset**
- **Exploratory Data Analysis**
- **Data Visualization of Target Variables**
- **Data Preprocessing**
- **Splitting our data into Train and Test Subset**
- **Transforming Dataset using TF-IDF Vectorizer**
- **Function for Model Evaluation**
- **Model Building**
- **Conclusion**

![image](https://user-images.githubusercontent.com/113114746/217746251-e61c808e-db30-4e7a-941c-a7ed7ba467ea.png)

# WordCloud 
![image](https://user-images.githubusercontent.com/113114746/217825145-2cc50f5d-7516-44c6-b2dc-d11b0482e935.png)

# Conclusion:
- 1- We have imported  tweets using SNScraping module regarding Hindenberg Report for Adani
- 2- We have Implemented Text Preprocessing like Text cleaning,Tokenization,stemming, lemmatization etc
- 3-We have Transform the data using TF-IDF Vectorizer
- 4-.we have tested our data with various machine learning models.
- 5- SVM classifer with linear kernal performing well which is giving accuracy near about 77 % 
- 6- We are getting descent accuarcy with XGB classifier around 74 % 
- 7- When we are balancing Data our Accuracy and recall is getting Down..we can work more on it to Improve the results
