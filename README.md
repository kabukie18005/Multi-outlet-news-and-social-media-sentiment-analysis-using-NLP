# NLP Sentiment Analysis — Multi-Outlet News & Social Media Coverage

An end-to-end NLP project analyzing sentiment and topics across major news outlets and YouTube comments covering a real-world geopolitical event (February–March 2026). The project combines unsupervised and supervised sentiment analysis, topic modeling, and multi-angle thematic analysis to compare how different sources framed and reacted to the same events.

## What this project does

- **Data collection & preprocessing:** Combines news articles from BBC, Reuters, Al Jazeera, and RT with YouTube comments, applying a documented 6-stage text cleaning pipeline
- **Sentiment analysis:** Uses VADER and TextBlob for unsupervised sentiment scoring, then trains a TF-IDF + Logistic Regression classifier for supervised sentiment classification, evaluated with a confusion matrix
- **Topic modeling:** Applies LDA (Latent Dirichlet Allocation) to identify dominant themes across the corpus, visualized interactively with pyLDAvis
- **Multi-angle analysis:** Breaks down sentiment and coverage across five thematic angles — military operations, geopolitical tensions, economic impact, media narratives, and public support/opposition
- **Comparative analysis:** Tracks sentiment differences across outlets and over time using visualizations (bar charts, heatmaps, time series, histograms, scatter plots)

## Tools & libraries

Python | pandas | NLTK | VADER | TextBlob | scikit-learn | Gensim (LDA) | pyLDAvis | matplotlib | seaborn | WordCloud

## Contents

- `NLP_Q2_Complete_Analysis.ipynb` — full analysis notebook, from data loading through final sentiment scoring and export

## Note on scope

This project is a methodological exercise in NLP and sentiment analysis techniques applied to real-world text data. The focus is on the analytical pipeline (preprocessing, modeling, classification, evaluation) rather than commentary on the underlying events.
