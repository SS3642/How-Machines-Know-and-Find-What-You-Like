# How Machines Know and Find What You Like

A 4-week WiDS 6.0 guided project (Analytics Club, IIT Bombay) on recommender systems and LLMs.

The one idea that ties everything together: **embeddings**. Turn things (users, movies, words, sentences) into vectors so that similar things sit close together, then find what is close.

- **Week 0:** a gentle toolkit warm-up (Python, classes, NumPy, pandas, matplotlib).
- **Weeks 1 and 2:** encode taste as vectors and find what is relevant (recommender systems).
- **Weeks 3 and 4:** turn text into vectors, then connect a pretrained LLM to our data with RAG (Retrieval-Augmented Generation).
- **Final project:** a chat-based recommender. Example request: *"Something like Inception but lighter, preferably Hindi, I liked 3 Idiots."*

## Who this is for

No ML background needed. Basic Python and school-level maths are enough. If you have never written Python, start with Week 0.

## How it runs

| Day | What happens |
|---|---|
| Monday | That week's material is released |
| Midweek | 1-hour live session |
| Sunday | Deliverables due |

Expected load: about 3 hours of reading or videos plus 3 to 4 hours of notebook work per week. Everything runs on free Google Colab. No paid APIs.

## Weekly plan

| Week | Theme | You build |
|---|---|---|
| [0](Week_0_Toolkit) | Your toolkit | Small demos with Python classes, NumPy, pandas and matplotlib |
| [1](Week_1_Taste_as_Vectors) | Taste as vectors | Popularity and "friends like you" recommenders |
| [2](Week_2_Learning_and_Measuring) | Learning and measuring | Item-item CF and SVD, compared on one leaderboard |
| [3](Week_3_Text_as_Vectors_and_Search) | Text as vectors and search | Bigram model, semantic "more like this" search |
| [4](Week_4_RAG_and_Final_Build) | RAG and the final build | Chat recommender app with Streamlit or Gradio |

See [Final_Project](Final_Project) for the brief and grading.

## Getting started

1. Open a week's notebook in Colab. Week 0: [open in Colab](https://colab.research.google.com/github/SS3642/How-Machines-Know-and-Find-What-You-Like/blob/main/Week_0_Toolkit/week0_toolkit.ipynb).
2. Choose **File > Save a copy in Drive** and work on your own copy.
3. Run the cells from top to bottom.

## Resources

### Week 0: Toolkit

| Resource | Type | Time | Notes |
|---|---|---|---|
| [Week 0 notebook](Week_0_Toolkit/week0_toolkit.ipynb) | Ours | 3 to 4 h | Start here |
| [Kaggle Learn: Python](https://www.kaggle.com/learn/python) | Course | As needed | Only if you have never written Python |
| [Python tutorial, chapter 9: Classes](https://docs.python.org/3/tutorial/classes.html) | Read | 30 min | Sections 9.3 and 9.5 are enough |
| [NumPy: the absolute basics for beginners](https://numpy.org/doc/stable/user/absolute_beginners.html) | Read | 45 min | Creating, indexing and operating on arrays |
| [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html) | Read | 30 min | Selecting, grouping, merging |
| [Matplotlib quick start guide](https://matplotlib.org/stable/users/explain/quick_start.html) | Read | 30 min | Just the first half |

### Week 1: Taste as vectors

| Resource | Type | Time | Notes |
|---|---|---|---|
| [Reading page: Similarity is everything](https://ss3642.github.io/How-Machines-Know-and-Find-What-You-Like/Week_1_Taste_as_Vectors/reading.html) | Ours | 1 h | The story, worked numbers, playground and starter code |
| [3Blue1Brown, Essence of Linear Algebra, ch. 1: Vectors](https://www.3blue1brown.com/lessons/vectors) | Watch | 10 min | Different ways to think about a vector |
| [3Blue1Brown, ch. 9: Dot products and duality](https://www.3blue1brown.com/lessons/dot-products) | Watch | 14 min | Focus on the first half (dot product as projection); duality is optional |
| [Kaggle Learn: Pandas](https://www.kaggle.com/learn/pandas) | Course | 2 to 3 h | Lessons 1 to 4; lesson 4 (grouping) is needed for the popularity recommender |
| [Google, Recommendation systems overview](https://developers.google.com/machine-learning/recommendation/overview/types) | Read | 15 min | The big picture: candidate generation, scoring, re-ranking |
| [Google, Candidate generation overview](https://developers.google.com/machine-learning/recommendation/overview/candidate-generation) | Read | 15 min | Cosine vs dot product vs distance; same lesson as Zoya in our reading page. Only these two Google pages for now |

### Weeks 2 to 4 (links added before each week is released)

| Week | Resources |
|---|---|
| 2 | StatQuest: Gradient Descent; Surprise library documentation; Mining of Massive Datasets, chapter 9 (optional) |
| 3 | Jay Alammar: The Illustrated Word2vec and The Illustrated Transformer; 3Blue1Brown: transformer and attention chapters; Andrej Karpathy: makemore part 1 (optional); sentence-transformers documentation |
| 4 | Hugging Face LLM course; Streamlit: Get started; Andrej Karpathy: Let's build GPT (optional) |

### Datasets

| Dataset | Used in | Notes |
|---|---|---|
| [MovieLens, small](https://grouplens.org/datasets/movielens/latest/) | Weeks 1 to 4 | 100,836 ratings of 9,742 movies by 610 users; about 1 MB. Notebooks download it and check the row count so everyone gets the same numbers |
| goodbooks-10k, Food.com recipes, MIND, Spotify Million Playlist | Final project | Optional domains; links added in Week 4 |

## Mentors

- Sanidhya Saraf
- Saanvi Walvekar
