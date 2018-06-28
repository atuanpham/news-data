# news-data
News text data scraped from several Vietnamese online newspapers. 

# Download crawled data:
This link below contains news text data from 4 Vietnamese online newspapers:
- Thanh Nien (TN)
- Dan Tri (DT)
- VNExpress (VNE)
- Vietnamnet (VNN)

Download data [here](https://drive.google.com/open?id=1H5LZ2Qme_eh19C6Iu1xPNYExMYc5U1oE)

# How to run code

- Requirement: Conda, Redis.
- Initialize the environment: `conda env create`
- Change environment: `source activate news-ds`
- Open `crawl_news.py` and modify `SITE_CONFIGS`.
- Start scraping: `python crawl_news.py`
