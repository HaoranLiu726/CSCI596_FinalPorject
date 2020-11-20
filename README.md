# CSCI596_FinalPorject
This is the final project of class SCIENTIFIC COMPUTING &amp; VISUALIZATION.

Recommendation system based on GPU

1. What is the problem?
Our goal is to help users find new content based on the user’s preference. The system could recommend products, websites, blogs, any new items. 

2. What methods were used?
To achieve this goal, we will perform content-base and collaborative filtering recommendation method to make the prediction.
We will use machine learning techniques to implement this system. Our training set contains user_id, business_id, and review test. We want to try different classifiers such as Naïve Bayes, Decisions trees, and KNN. 
Since review dataset is too large to be analyzed by a single computing node, so the traditional recommendation based on single CPU is hard to meet our requirement. Therefore, we will use CUDA to accelerate the calculation speed and avoid memory corruption.

3. What are the expected result? 
