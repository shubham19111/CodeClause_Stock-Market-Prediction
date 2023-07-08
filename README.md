# Stock-Market-Prediction
![images](https://github.com/shubham19nijwala/Nifty-Bank-Stock-Market-Prediction/assets/130289158/5597c409-7000-47bf-8ada-ebe482d7bcc6)

## About Dataset
### Context
The National Stock Exchange of India Limited (NSE) is the leading stock exchange of India, located in Mumbai. Nifty Bank, or Bank Nifty, is an index comprised of the most liquid and large capitalized Indian banking stocks. It provides investors with a benchmark that captures the capital market performance of Indian bank stocks. The index has 12 stocks from the banking sector.

Apart from NIFTY BANK index, there are also other indices like NIFTY IT and indexes for other sectors. Exploring these indices may help in taking investment decisions.

### Content
This dataset has daily information on NIFTY BANK index starting from 01 January 2018.

The file has the following columns

Date - date of observation
Open - open value of the index on that day
High - highest value of the index on that day
Low - lowest value of the index on that day
Close - closing value of the index on that day
Volume - volume of transaction

## Steps Involved:
*  **Data Preparation**: Import the necessary libraries and load the Nifty Bank Stock Market dataset from 2018 to 2021. Perform data cleaning to handle missing values and ensure data consistency.

* **Exploratory Data Analysis (EDA)**: Conduct exploratory analysis to understand the distribution, trends, and statistical characteristics of the dataset. Visualize the data through plots and charts to gain insights into the behavior of the Nifty Bank index.

* **Feature Engineering**: Engineer additional features based on the existing columns to enhance the predictive power of the model. This may involve creating lagged variables to capture time-dependent patterns and calculating technical indicators to capture market trends.

* **Data Split**: Split the dataset into training and testing sets. The training set will be used to train the predictive model, while the testing set will be used for evaluating its performance.

* **Model Training**: Train a tuned logistic regression model using the training data. Fine-tune the model parameters to optimize its performance. This can be done through techniques like grid search.

* **Model Evaluation**: Evaluate the performance of the tuned logistic regression model using various metrics such as precision, recall, accuracy, ROC-AUC score, and F1 macro score. These metrics provide insights into the model's predictive capabilities and its ability to classify whether the stock value will increase or decrease.

* **Conclusion**: Summarize the findings of the project. Highlight the superior performance of the tuned logistic regression model compared to the regular logistic regression model. Emphasize the improvements in precision, recall, accuracy, ROC-AUC score, and F1 macro score achieved by the tuned model. Discuss the importance of considering historical data, market trends, and relevant factors in accurately predicting stock market movements.


By following these steps, I successfully developed a predictive model using Nifty Bank Stock Market data and gained valuable insights for making informed investment decisions in the Nifty Bank Stock Market.
