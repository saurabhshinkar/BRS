# Book Recommendation System
## Abstract

During the last few decades, with the rise of YouTube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers’ articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.
In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).


## Problem Description:
Recommendation systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

### Data Description:
The Book-Crossing dataset comprises 3 files.

#### Users:
Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

#### Books:
Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-Image-URL-M, Image-URL-L), i.e., small, medium and large. These URLs point to the Amazon website.

#### Ratings:
Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

## Conclusions
1. Wild Animus is the best-selling book

2. Author Agatha Christie, William Shakespeare and Stephen King wrote most of the books

3. Harlequin publication published the most books

4. More than 50% readers are from USA

5. Book-Ratings are negatively distributed with median rating of 8.

6. Root mean squared error of model SVD is 0.31 and mean absolute error is 0.21

7. Root mean squared error of model NMF is 0.34 and mean absolute error is 0.24

8. Root mean squared error of model Slope One is 0.39 and mean absolute error is 0.27

9. SVD++ is the best recommendation model with root mean squared error of 0.30 and mean absolute error of 0.20

## References
1. GeekforGeeks
2. Kaggle
3. Analytics Vidya

