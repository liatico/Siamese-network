# Siamese-network
this project is a research notebook in which i implemented a Siamese network in order to determin if a search query and product description are similar
each search query and product have a similarity score between 1 and 3. the search query and product description was preprocess as in character level and encoded in one-hot vectors 
originaly the data is from a Kaggle competition from 2017 https://www.kaggle.com/c/home-depot-product-search-relevance/data
to solve this problam i tried to implement a Siamese network from an article: Arpita Das, Harish Yenala, Manoj Chinnakotla, Manish Shrivastava, Together we stand: Siamese Networks for Similar Question Retrieval, 2016
to get a naiv statistical baseline i used Jaccard similarity.
i also tried to use this network as feature extractor and used xgboost and catboost as classifiers to feature vectors.
the results were sutisfying but this research project requres further work
