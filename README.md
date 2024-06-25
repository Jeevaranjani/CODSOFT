1. About the Titanic Dataset:-Task-1
The dataset from kaggle assigned by CodSoft
Survived: Outcome of survival (0 = No; 1 = Yes) Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class) Name: Name of passenger Sex: Sex of the passenger Age: Age of the passenger (Some entries contain NaN) SibSp: Number of siblings and spouses of the passenger aboard Parch: Number of parents and children of the passenger aboard Ticket: Ticket number of the passenger Fare: Fare paid by the passenger Cabin: Cabin number of the passenger (Some entries contain NaN) Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)

The dataset contains 891 rows and 12 colummns

Conclusion:

logistic regression perform with 75% accuracy
mostly women are survived
passengers travelled between the age of 20 to 40
mostly first class travelled people became survived compared to travelled in third class


2. About IMDb dataset:-Task-2
 It is about India movies.The dataset contains 15509 rows and 10 columns.
Conclusion:

1.The most of the movies are Drama,Action and followed by Romance
2. Year 2020 an Indian movie recieved 10.0 points
3. pran appears in most of the movies
4. The correlation plot indicate that the director, specific actors, and number of votes have a strong positive relationship with higher movie ratings, while the genre has a weaker positive correlation, and the 
   year of release has a negligible negative correlation.
5. Random Forest performs well with 80% of accuracy
6 .In Evaluation Metrics compare to other model Random Forest perform with low error MSE: 0.196, RMSE: 0.443, MAE: 0.237

3. sales Dataset:-Task-3
 The sales dataset contains 200 rows and 4 columns
Conclusion:
There is no missing values in the dataset.
1.the most frequent maximum times of sales occurs between 15 to 20
2.The scatter plot indicates tv is directly propertional to sales.If tv advertersing is increases and the sales also increases
3.there is strong positive correlation between tv and sales.For Radio and Newspaper has low correlation.So there is max chance of sales by advertising through TV.
4.XG boost regressor performs well with 94% of accuracy
5.Evaluation metrics for XGBoost is MSE: 1.0949672299526045


4.Credit Card Fraud Detection: The datasets contains 284807 rows and 31 columns
Conclusion:
1. there is no missing values in the datasets
2. But the dataset is more imbalanced
3. By using Oversampling "SMOTE" technique to balanced the data
4. I build only one model "logistic regression".It performs with 92% of accuracy
5. In Evaluation metrics the AUC value is 0.984 which the model performs well to distinguish the class
