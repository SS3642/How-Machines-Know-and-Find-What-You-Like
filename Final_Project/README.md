# Final Project: A Chat-Based Recommender

## Pipeline

1. Embed the user's message.
2. Retrieve the top ~20 items by cosine similarity on item embeddings.
3. Re-score them with your collaborative filtering or matrix factorisation scores.
4. Put the top 5 to 10 items, with descriptions and ratings, into a prompt (RAG).
5. The LLM picks the best 3, respects the constraints and explains each pick.
6. Show the result in a Streamlit chat app.

## Evaluation

Run about 20 identical requests through three systems: the recommender alone, the LLM alone (no retrieval), and RAG. Count how often each suggests items that are not in the catalogue, and judge how relevant the picks are.

## Domains

Same pipeline, your choice of data: movies, books (goodbooks-10k), recipes (Food.com), IITB electives, news (MIND) or playlists.

## Every team must have

- a baseline plus at least one better method, compared with a number
- embeddings or similarity used somewhere
- a working demo
- a report of at most 2 pages

## Grading (draft)

| Part | Weight |
|---|---|
| Weekly notebooks | 40% |
| Baseline and comparison | 20% |
| Method | 15% |
| Demo | 15% |
| Report | 10% |
