# Analysis of Yelp business, user, and reviews data

This project leverages AWS EMR and a pyspark Jupyter Notebook to analyze 10 GB of Yelp Reviews Data. 

The data was taken from [kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset).

The notebook (Analysis.ipynb) contains an analysis of Yelp's business, review, and user data.

# Docker script
This repository also contains a folder called script. The script folder contains the source of a [docker container](https://hub.docker.com/repository/docker/tbenthomas/kaggle_s3/tags?page=1) that can be ran to pull a kaggle dataset and push to S3. 

Details on usage are in the README.md within the script folder. 

# S3 Bucket
The data used in the analysis has been stored in a public S3 bucket.
The paths to the datasets are as follows: 

https://yelp-reviews.s3.amazonaws.com/data/yelp_academic_dataset_business.json

https://yelp-reviews.s3.amazonaws.com/data/yelp_academic_dataset_checkin.json

https://yelp-reviews.s3.amazonaws.com/data/yelp_academic_dataset_review.json

https://yelp-reviews.s3.amazonaws.com/data/yelp_academic_dataset_tip.json

https://yelp-reviews.s3.amazonaws.com/data/yelp_academic_dataset_user.json

# Cluster and Notebook Configs
![image](config-screenshots/cluster-configuration.png)


![image](config-screenshots/jupyter_nb-config.png)


