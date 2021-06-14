# web-mining
This repository is for web mining project: Music Artist PersonalRank Recommender based on social network and tag system
In this project, we implemented 2 PersonalRank Recommenders, one with social network , one with social network and tag system.
In the meantime, we implemented 3 basic recommenders as our baseline: Content-based RS, Iterm-based CF RS and User-based CF RS.

## Features
this project implemented the following featrues
* Section 1: Download and Split data set
* Section 2: Tag Clustering
    * Section 2.1: Tag preprocessing
    * Section 2.2: Tag clustering: BERT
    * Section 2.3: Tag clustering: Levenshtein distance
    * Section 2.4: Tag clustering: user artist correlation
    * Section 2.5: Tag clustering Result
* Section 3: PersonalRank-based Recomender
    * Section 3.1: User similarity computation
    * Section 3.2: Graph Construction
    * Section 3.3: PersonalRank implementation: Based on Iteration & Matrix
    * Section 3.4: Example
* Section 4: User-based CF & Item-based CF Recommenders
    * Section 4.1: Calculate similarity matrix for user & item
    * Section 4.2: Predict rating based on item-based or user-based methods
    * Section 4.3: Recommend artists based on user preference
* Section 5: Content-based Recommender
* Section 6: Evaluation
    * Section 6.1: User-based metrics
    * Section 6.2: Item-based metrics
    * Section 6.3: Content-based
    * Section 6.4: PersonalRank without tags
    * Section 6.5: PersonalRank with tags

## File Structure
The project is organized as below. 
we put all the data in data directory. if you want to run the code from scratch  , you do not need to download the data directory.

we use the data set **hetrec2011-lastfm-2k**.
you can download the data set from this link:
https://files.grouplens.org/datasets/hetrec2011/hetrec2011-lastfm-2k.zip
or download from data/dataset.
we also contain a code to download and unzip automatically.


the code is organized in notebook directory.
In this directory, we put all the code in all-in-one.ipynb, you can just run this notebook.
We put individual code part in other notebooks.

- notebook
 - all-in-one.ipynb
 - separately sorted notebooks 
- data
 - dataset
 - split
 - tags
 - interim
 - external
 - result
-readme.md

