# Analyzing 10Gb of Yelp Reviews Data
For this project, I am to provision a Spark cluster on AWS EMR, connect it to a Jupyter Notebook to answer a few questions about the Yelp dataset which is provided on [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset) 

The project is divided into 2 parts:

   ## Part A
   1. Create a cluster on AWS EMR, and connect it to a Jupyter Notebook
   2. Upload Yelp dataset to AWS S3
   
   ## Part B
   
   **I. Installation and Initial Setup** Import the necessary dependencies and load Yelp dataset as a pyspark dataframe
   
   **II. Analyzing Categories** 
   - How many unique categories are represented in this dataset?

   - What are the top 20 most popular categories available?

   **III. Do Yelp Reviews Skew Negative?** 
   - Oftentimes, it is said that the only people who write a written review are those who are extremely _dissatisfied_ or extremely _satisfied_ with the service received. How true is this really?
   
   **IV.  Should the Elite be Trusted?**
   - Is there a difference between ratings of Elite and Non Elite group? Can Elite ratings be trusted?
