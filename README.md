# Project 1 ( End-to-End Pipeline to Classify News
Articles):
The project consists of building an end-to-end pipeline to
classify samples of news articles and involves the following ML components:
1. Feature Extraction: Construction of TF-IDF representations of textual data;
2. Dimensionality Reduction: Principal Component Analysis (PCA) and non-Negative
Matrix Factorization (NMF) - Generally necessary for classical ML methods
3. Application of Simple Classification Models: Applying common classification methods to the extracted features such as Logistic/Linear Classification and Support Vector
Machines;
4. Evaluation the Pipeline: Evaluating and diagnosing classification results using GridSearch and Cross Validation;
5. Replace corpus-level features with pretrained features: To apply pre-training to
a downstream classification task and evaluate comparative performance.

# Project 2 (Data Representations and Clustering):

## Part 1 - Clustering on Text Data
In this part of the project, we will work with “20 Newsgroups” dataset, which is a collection
of approximately 20, 000 documents, partitioned (nearly) evenly across 20 different newsgroups
(newsgroups are discussion groups like forums, which originated during the early age of the
Internet), each corresponding to a different topic.

## Part 2 - Deep Learning and Clustering of Image Data
In this part, we aim to cluster the images of the [tf flowers](https://www.tensorflow.org/datasets/catalog/tf_flowers) dataset. This dataset consists of
images of five types of flowers. 

## Part 3 - Clustering using both image and text

In Parts 1 and 2, the art of clustering text and images separately was practiced. However, the question arises: can both image and text be mapped to the same space? In the Pokémon world, the Pokedex catalogs appearances of Pokémon and various metadata. Our Pokedex will be constructed from the [image dataset link](https://www.kaggle.com/datasets/hlrhegemony/pokemon-image-dataset) and [metadata link](https://github.com/lgreski/pokemonData/blob/master/Pokemon.csv).


# Project 3 - Recommender systems

In this project, two types of collaborative filtering methods will be implemented and their performance analyzed:

1. Neighborhood-based collaborative filtering: This method directly leverages the choices of other users to determine potential items to recommend to the current user.
2. Model-based collaborative filtering: This technique estimates a joint model from all user data, enabling the generation of new recommendations without accessing the entire user base. It also allows for queries on a more compact model.
Additionally, the Naive collaborative filtering technique will be explored and compared among the three methods.

The project aims to build a recommendation system to predict movie ratings in the [provided dataset](https://drive.google.com/drive/folders/1_JF9plSjE3PAFBuSvUFRkDdftJWo1TFz).  Collaborative filtering techniques will be explored for predicting ratings, effectively understanding user preferences and behavior from historical data. This lays a foundational understanding of user behavior and item affinity. The focus will then shift to how ranking approaches enhance recommendation systems by not only identifying relevant items but also prioritizing them for optimal user satisfaction and engagement.

# Project 4 - Regression Analysis and Twitter data analysis

In part 1 of the project,  specific-to-regression feature engineering methods and model selection that
jointly improve the performance of regression is explored with the help of the synthetic [diamonds dataset](https://drive.google.com/file/d/1Z1a99rlufNP6qItwVY9fPPXO61y4ok55/view).

In part 2 of the project, the focus shifts to working with tweets sourced from one of the 6 Twitter hashtags. The chosen task involves the development of a Library of Prediction Tasks given a tweet:

• Predicting the likelihood that a tweet belongs to a specific team's fan base.
• Predicting the number of retweets a tweet will receive.
The #superbowl.txt dataset, which spans 5.2GB, comprises JSON-formatted data with various keys such as "firstpost date," "title," "url," "tweet," "hashtags," "retweet count," "followers count," and "citations." The objective is to determine the fan team affiliation of each tweet. This task is treated as a binary classification problem between the Hawks and the Patriots, the teams participating in the SuperBowl.








