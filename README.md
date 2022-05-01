# BigDataAnalysis

The goal of this project is to analyze Amazon reviews written by paid Amazon Vine program members, a service that allows manufacturers and publishers to receive product reviews, and see if there are any biases between Vine members' and non-Vine members' reviews.

Companies that will pay a fee to Amazon and provide free products to Vine members in exchange for a review. To see if there is a bias toward positive reviews from Vine members versus non-members, we need to know the percentage of 5 star ratings to total rating.We were asked to select one of 50 datasets to extract, transform, and load into a dataframe in order to complete our analysis. Throughout this analysis, we will make use of the following terms:

PySpark will be used to extract the dataset, transform it, connect to an AWS RDS instance, and load the transformed data into pgAdmin.
Google Collaboratory for importing PySpark libraries and connecting to Postgres to create SQL tables and export the results.
I chose to analyze reviews made by users in the "VideoGames" category from among the 50 datasets.

# Results

Total of reviews:
Vine reviews: 94
Non vine Reviews: 40471


Total number of 5-star reviews
Vine reviews: 48
Non vine reviews; 15,663

Percentage of 5-star reviews
Vine reviews: 51.06
Non vine reviews: 38.701

According to the findings, Vine members did not exhibit bias when rating their products, despite the fact that the number of 5-star ratings was approximately 10% lower than that of non-Vine members (42 percent vs. 46.4 percent ). As a result, we can assume Vine customers are more critical when submitting a review. To further support this assumption, we should include all of the data rather than filtering it to a percentage of helpful vs. total votes, as we did in this analysis. Examining the data as is would provide us with more information and allow us to further support our hypothesis, as shown below.
