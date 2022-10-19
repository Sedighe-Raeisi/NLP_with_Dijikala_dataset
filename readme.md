
# Sentiment prediction of digikala customers post with machine learnings
In this project I downloaded the dataset of comments of customers of digikala from kaggle.   
These coments were either positive, negativie or neutral.    
The following pie chart shows the distribution of each group.   
![image](https://user-images.githubusercontent.com/67642255/196615843-75b2dc1e-72b7-4f6c-80d7-10a7782b033e.png)

I used the Hazm library to clean the texts. The cleaning process includs the normalization , tokenizing, removing stop words and stemming. 
Then I used the TfIdf vectorization to vectorize the texts. 
# Random Forest Classifier ACC=80   
After vectorization I used the Random Forest classifier of sklearn. Here is the confusion matrix   
![image](https://user-images.githubusercontent.com/67642255/196615668-deff35cf-ae93-4060-b7d3-7f46d1e90755.png)

# SGD Classifier ACC=79  
I also used the SGD classifier of sklearn and here is the confusion matrix.   
![image](https://user-images.githubusercontent.com/67642255/196615743-5eb51c9a-ae12-4c9f-848c-b336ae0b7d61.png)

