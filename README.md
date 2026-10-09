# The hottest topics in machine learning

Text analysis of the titles of papers published at the NIPS (now NeurIPS) conference from 1987 onwards, to see how the field's research topics have changed.

## Data

`papers.csv`: one row per paper, with year, title, abstract and full text. The data comes from the DataCamp project of the same name.

## Approach

- Count papers per year to show the growth of the conference
- Clean the titles (lower-case, strip punctuation) and draw a word cloud
- Count the most common words with `CountVectorizer`
- Fit a latent Dirichlet allocation (LDA) model to find topics

## Status

Work in progress. Loading, cleaning, the yearly counts and the word cloud are done; the word-count and LDA steps are still to be completed. The dataset in `datasets/` also needs to be re-uploaded as a single `papers.csv` before the notebook can be re-run.
