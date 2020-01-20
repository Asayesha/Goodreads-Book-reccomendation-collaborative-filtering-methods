# Book Recommendation

## Meet your next favourite book!

This project was built by Aadithya Anandraj, Sayesha Aravapalli, Khyathi Balusu, Lashay Fontenot and Sadhana Koneni

### Business problem :  
Today in the world of personalized marketing it is important to understand each customer and target them accordingly. The task is to recommend books to users based on their given ratings of other books.

### Data source :
This data is from Kaggle – the goodreads dataset. The dataset has 10,000 books which were rated by more than 6 million users. 

### Toolkit  : 
Python 

### Algorithms :
1. user-based collaborative filtering   (cosine similarity and correlation) 
2. item-based collaborative filtering  (cosine similarity and correlation)
3. Apriori algorithm
4. K – means clustering

### Approach :
1.	First we looked into content-based recommendation. The dataset did not contain the synopsis of the books to use content-based recommendation and hence moved on to collaborative based recommendations.
2.	We worked with a sample of the dataset for item and user based collaborative filtering using 
Cosine similarity and correlation were used to find similarity between items/users.
3.	Further we clustered the books, to see if we can recommend better books by applying collaborative filtering on each cluster.
4.	Apart from the above we also tried aprior algorithm

### Insights :  
Cosine similarity and correlation performed pretty similar. Item based collaborative filtering maybe a better recommendation heuristic in this case.

### Future scope : 
1. The performance metric can be changed to just finding the RMSE based on the top 10 books. 
2. Can use complete dataset by using better computational resources.
3. Can also try to get the genres to better cluster books, which was very ambiguous in the dataset.
