# Who Should Be Insured?

This repository includes information from an Iranian service provider application called `Achareh`.

We used the provided data for analyzing the service demands in Iran. In addition, we created a time-series model using RNN and Sentence Embedding to detect the users who should be insured.

## Files

* EDA
This notebook includes the information of the datasets, including comments of each work. At the end of the notebook, there is simple classification.

* DamagingUsers
This notebook was used to attach the users that have made any damage in their previous works to the main dataset.

* Locations
In these files, the locations of the orders related to `movement` is examined.

* Sentence Embedding
In this notebook, we used sentence embedding for clustering the users. In EDA, the features extracted from the comments were just specific words in comments.

* RNN
In this notebook, we used RNN for classifying the users by considering user actions as time series.

## Acknoledgement

This project is done at the University of Tehran Data Analysis lab.

```
Amirhossein Abaskohi
Taha Shabani
Saba Shahsavari
Houman Chamani
Shahrzad Javidi
```