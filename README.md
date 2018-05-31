# Dataset-and-Model-Implementation-for-Implicit-Entity-Recognition-and-Classification-in-Tweets

# Overview
This repository includes a gold standard dataset containing 7870 tweets for the task of implicit entity recognition and classification. Furthermore, the python source codes for extraction of features for implicit entity recognition are provided. The publication pertinent to this work has been submitted under the title of "Implicit Named Entity Recognition and Classification in Tweets; a Benchmarking Framework."


# Dataset
This gold standard dataset for implicit entity recognition and classification is comprised of three major categories of tweets, namely tweets with explicit mention/s of entities, tweets with implicit mention/s of entities, and tweets without either. As per a random sampling using Twitter API and ratio calculation, the ratio of different types of tweets in our dataset is as follows: 35\% Explicit, 15\% Implicit, and 50\% NIL.

A two-level taxonomy comprised of fine-grained and coarse-grained class levels has been designed for structuring and collection of our gold standard dataset. Our taxonomy contains 7 coarse-grained entity types, namely PERSON, ORGANIZATION, LOCATION, PRODUCT, EVENT, and WORK. These tags and the fine-grained classes pertinent to each tag are based on the DBpedia taxonomy.

Tagged tweets have been collected in a four-month time frame spanning from October 2017 to January 2018. We maintain such information as tweet ID and user ID.


# Source Codes
As explained in the paper, several features have been designed to train classifiers. The source codes for extraction of these features are provided in Src folder.
