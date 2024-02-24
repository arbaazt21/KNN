# KNN (K-Nearest Neighbor)

- KNN is a Supervised Machine Learning Algorithm.
- It is a Simplest algorithm.
- It is Distance-based algorithm.
- KNN is used for both Classification and  Regression. 
- But it is widely used for classification problems.
- It is also called as Voting-Classifier.
- It is NON-PARAMETRIC.
- KNN is also called as LAZY-LEARNER Algortithm, bcoz it doesn't learn from the Training Dataset immediately, instead it stores the dataset & at the time of classification it performs an action on the dataset.



## Working of KNN

- Step-1: Select the number K of the neighbors
- Step-2: Calculate the Euclidean distance of K number of neighbors
- Step-3: Take the K nearest neighbors as per the calculated Euclidean distance.
- Step-4: Among these k-neighbors, count the number of the data points in each category.
- Step-5: Assign the new data points to that category for which the no. of the neighbors is maximum.
- Step-6: Our model is ready



## KNN is a Distance-based Algorithm,

### So for calculating Distance, there are two methods:-
    1) Eulidean Distance (used by default):-
        it calculates the distance in straigth-line (linear-line)
        Faster
        Accuracy is GOOD.
        
    2) Manhattan Distance (Taxicab) or (City-block):- 
        it calculates the distance in travelling to other points also.
        Time Consuming.
        Accuracy is BEST.
        

# Important in KNN
- Normalization or Standardization 
- Hyperparameter-Tunning 


  
## Advantages of KNN Algorithm:
- It is simple to implement.
- It is robust to the noisy training data
- It can be more effective if the training data is large.
