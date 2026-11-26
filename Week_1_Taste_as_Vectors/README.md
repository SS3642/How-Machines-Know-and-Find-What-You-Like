# Week 1: Taste as Vectors

## Concepts

- pandas basics
- vectors and the dot product
- Euclidean distance vs cosine similarity
- popularity baseline
- user-user collaborative filtering

## Start here

Open [`reading.html`](reading.html), "Similarity is everything". It covers the story, the worked numbers, a playground and the starter code. To view it as a web page, use the [live version](https://ss3642.github.io/How-Machines-Know-and-Find-What-You-Like/Week_1_Taste_as_Vectors/reading.html), or download the file and open it in your browser.

## Watch and read (about 3 hours)

| Resource | Time | Notes |
|---|---|---|
| [3Blue1Brown, Essence of Linear Algebra, ch. 1: Vectors](https://www.3blue1brown.com/lessons/vectors) | 10 min | Different ways to think about a vector |
| [3Blue1Brown, ch. 9: Dot products and duality](https://www.3blue1brown.com/lessons/dot-products) | 14 min | Focus on the first half (dot product as projection); duality is optional |
| [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas) | 2 to 3 h | Lessons 1 to 4; lesson 4 (grouping) is needed for the popularity recommender |
| [Google, Recommendation systems overview](https://developers.google.com/machine-learning/recommendation/overview/types) | 15 min | The big picture of a recommender |
| [Google, Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | 15 min | Cosine vs dot product vs distance can rank items differently, the same lesson as Zoya |

## Notebook (about 3 hours)

- Load MovieLens (small) with pandas, and find the most-rated and best-rated movies
- Build Recommender A: popularity, with a minimum of 50 ratings
- Build Recommender B for one user using cosine similarity
- Plot a histogram of ratings with plain matplotlib

Dataset: [MovieLens, small](https://grouplens.org/datasets/movielens/latest/) (100,836 ratings, 9,742 movies, 610 users, about 1 MB).

## Submit by Sunday

- The completed notebook
- Answers to the 3 check questions on the reading page
- One paragraph: a recommendation you got recently that felt wrong, and why
