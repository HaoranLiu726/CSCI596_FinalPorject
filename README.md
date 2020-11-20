# CSCI596_FinalPorject
This is the final project of class SCIENTIFIC COMPUTING &amp; VISUALIZATION.

What is the problem?
What methods were used?
What are the expected result? 




Recommendation system based on GPU


Dataset: 
review.json - contains user_id, business_id, review_text and so on

Object:
Since we have thousands of reviews that a user make for a business, we want to know if a user want to review a given business.

To achieve this goal, we will perform content-base and collaborative filtering recommendation method to make the prediction.

Related to CSCI 596:
The review dataset is too large to be analyzed by a single computing node, so the traditional recommendation based on single CPU is hard to meet our requirement. Therefore, we will use CUDA to accelerate the calculation speed and avoid memory corruption.
