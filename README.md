# Cryptocurrencies

## Purpose
    - The purpose of the following process is to group the cryptocurrencies into groups to make 
    a detailed analysis of each group later. We do not know exactly what we are looking for, for 
    that reason we will use unsupervised learning algorithms so that it finds for us some pattern 
    with which to group the similar ones.

## Results
    - Thanks to the elbow curve method, we reach the conclusion guided by the graph that we will 
    have 4 groupings (image A-1).

![](https://github.com/maadpeal/Cryptocurrencies/tree/main/Resources)
(image A-1)

    - We can see that effectively 4 groups is an acceptable number given the distribution of the 
    data (image B-1).

![](https://github.com/maadpeal/Cryptocurrencies/blob/main/Resources/B-1.png)
(image B-1)

## Summary
    - First of all, the data is cleaned, and the cryptos that are marketed remain.
    - We eliminate the column that has the names since it cannot be understood by the algorithm 
    that we will use.
    - We eliminate the rows that have null values.
    - And finally we eliminate those that have not been mined and 532 cryptos persist (image C-1).

![](https://github.com/maadpeal/Cryptocurrencies/blob/main/Resources/C-1.png)
(image C-1)

    - We transform the columns that still have words into separate boolean columns.
    - And we scale to reduce the number of columns that we currently have, which are 98(image D-1).

![](https://github.com/maadpeal/Cryptocurrencies/blob/main/Resources/D-1.png)
(image D-1)

    - With the reduced information we make the evaluation of how many groups should exist to train 
    our algorithm (image A-1).
    - Once the predictions made by the model are obtained, we proceed to visualize the information 
    in three dimensions. (image B-1).
    - These results must now be analyzed in detail group by group to determine why a crypto is in 
    a certain group or why not, so we can have more information for more informed decision making.
