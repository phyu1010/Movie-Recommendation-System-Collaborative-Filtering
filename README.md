# Movie-Recommendation-System-Collaborative-Fitering

Cause this notebook is created and run in databricks, so it fit in the Spark environment. 

The data comes from Movielens lateset small dataset. https://grouplens.org/datasets/movielens/latest/ 

This model applied Collaborative Fitering method to build a recommendation system, after that applying RMSE to evaluated the model. 


# KEY OBSERVATION
- According to the RMSE result comparsion in test data set,  between Mean-Value model (0.9684681096936459) and Collaborative-Fitering model (0.8884978333224407), we could see that Collaborative-Fitering(ALS) model perform better than Mean-Value model.

- RMSE in the test dataset is 0.8884978333224407, even lower than the best performance validation (0.8959979908871762) data set, so I think the model performance is convinced. 

- The movie dataset is not large enough, so if this Collaborative-Fitering(ALS) model was trained in larger dataset, the final result could probably perform better. 

# Suggestions
 
 - Need more training data to cover more samples.
 - In order to make the model more reliable, we could add more features into the dataset. 


 # References of ALS

- Building a Movie Recommendation Service: https://www.codementor.io/jadianes/building-a-recommender-with-apache-spark-python-example-app-part1-du1083qbw
- MLlib - Collaborative Filtering: https://spark.apache.org/docs/1.1.0/mllib-collaborative-filtering.html
- Collaborative Filtering - RDD-based API: https://spark.apache.org/docs/latest/mllib-collaborative-filtering.html
- Evaluation Metrics - RDD-based API: https://spark.apache.org/docs/2.2.0/mllib-evaluation-metrics.html
- ML - ALS: https://towardsdatascience.com/prototyping-a-recommender-system-step-by-step-part-2-alternating-least-square-als-matrix-4a76c58714a1

