# Book Recommendation

## Meet your next favourite book!

### Business problem :  
Today in the world of personalized marketing it is important to understand each customer and target them accordingly. The task is to recommend books to users based on their given ratings of other books.

### Data source :
This data is from Kaggle – the goodreads dataset. The dataset has 10,000 books which were rated by more than 6 million users. 

### Technologies :

Python 3.7.3

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
1.Cosine similarity and correlation performed pretty similar. Item based collaborative filtering maybe a better recommendation heuristic in this case.
2. A mixture of books from clsuters can be reccomeneded which can help solve the long tail problem and increase visibility of less popular but good books.


This project was built by Aadithya Anandraj, Sayesha Aravapalli, Khyathi Balusu, Lashay Fontenot and Sadhana Koneni



