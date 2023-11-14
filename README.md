# PaperView
This repo contains a CSV file containing about 2000 articles from the Straits Times from 04 Jan 2022 to 07 Nov 2023.

The file was generated using a script adapted from [Ari's Scrapeyard: Straits Times](https://colab.research.google.com/drive/1sfS0PhIDUJ_TtT9SKr1YKBD_H81K0mrH?usp=sharing).

## Test Queries and Relevance
A set of test queries and expected results are provided in `test.csv`. Relevance information was assigned using boolean retrieval techniques, computed in the `extract.ipynb` notebook, and saved to `relevance.csv`.