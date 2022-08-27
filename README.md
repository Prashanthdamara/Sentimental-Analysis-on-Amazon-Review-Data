# Sentimental-Analysis-on-Amazon-Review-Data

### Data Description : 

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

### Data includes:

Reviews from Oct 1999 - Oct 2012 - 568,454 reviews

256,059 Users and 74,258 products

260 users with > 50 reviews

### Task here is to transform the given data(i.e. Text files) to tabular format(i.e. csv file). The columns in the table should be:

Id - Unique row number

ProductId - Unique identifier for the product

UserId - Unique identifier for the user

ProfileName

HelpfulnessNumerator - Number of users who found the review helpful

HelpfulnessDenominator - Number of users who indicated whether they found the review helpful

Score - Rating between 1 and 5

Time - Timestamp for the review

ReviewSummary - Brief summary of the review

ReviewText - Text of the review

NOTE - Helpfulness (fraction of users who found the review helpful) = HelpfulnessNumerator / HelpfulnessDenominator

### Exploratory data analysis:

Distribution of Ratings

Popular words in Positive Reviews (4-5 Rating)

Popular words in Negative Reviews (1-2 Rating)

Distribution of Helpfulness

How does rating affect Helpfulness?

How does word count vary by rating?
Etc…

Note - Using this blog (https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/) written by Rob Castellano to understand the data analysis and how he generated insights (conclusion) from the visualizations. 

### Build a model which takes the text review as input and predicts the rating of the review.
