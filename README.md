# Movie Recommendation System
There are different types of Recommender systems that generally fall
into two groups: content-based recommender systems and collaborative filtering recommender systems. There are also some recommender systems using algorithms of both groups, which are the hybrid approaches.
Matrix factorization models are a group of recommender systems that are a subset of collaborative filtering approaches. These models generally find an embedding for both users and items representing their features. The application of Deep learning models to the Recommender Systems domains is one of the most powerful latent factor approaches which have gained a lot of attention in the community, given its promising results. 

<img src = "https://github.com/arashasg/Recommender-System-Movie/blob/main/img/12.PNG?raw=true">

In this repository, We trained two deep learning models and compared the effect of embedding length on the models' performance. Based on the results, a higher dimension of embeddings will result in lower loss, which was totally predictable as embeddings with a higher dimension will capture more features, assisting the model in predicting with higher accuracy.  
Our model architecture is as follows: 
<img src = "https://github.com/arashasg/Recommender-System-Movie/blob/main/img/6.png?raw=true">

The loss of each of our models is presented in the following images. The first loss plot is for the model with an embedding length of 20, and the next one shows the loss of the model having an embedding dimension of 10. 

<img src = "https://github.com/arashasg/Recommender-System-Movie/blob/main/img/8.png?raw=true">

<img src = "https://github.com/arashasg/Recommender-System-Movie/blob/main/img/9.png?raw=true">

Dataset
The Movielens Dataset used for training our models is accessible through [Kaggle](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset).




