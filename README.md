# AI_sentiment_analysis

This project is part of a university course in data analysis and computational linguistics.  
It focuses on content and sentiment analysis of texts related to Artificial Intelligence (AI), based on:

- **70 news articles** (2019–2025) discussing AI and the job market
- **841 tweets** collected via scraping on the topic of AI

All scripts are written in **R**, using libraries such as `tidytext`, `quanteda`, `syuzhet`, `vader`, and `rainette`.

---

## 📁 Repository Structure

AI_sentiment_analysis/ ├── data/ # Datasets (.xlsx) used for analysis (not uploaded yet) ├── docs/ # Final PDF reports (rendered from RMarkdown) ├── scripts/ # RMarkdown source files ├── LICENSE # MIT License ├── README.md # This file └── .gitignore


---

## 📚 Project Overview

### CAP3 – AI_articles_ContentAnalysis
- Wordcloud and lexical analysis
- Dimensionality reduction (LSA)
- Topic modeling
- Cluster analysis

### CAP4 – AI_articles_SentimentAnalysis
- Sentiment polarity detection using Bing and LSD2015 lexicons
- Emotion classification using NRC lexicon
- Temporal evolution of sentiment

### CAP5 – AI_Tweets_Analysis
- Polarity and sentiment scoring with `vader` and `qdap`
- Hashtag network visualization
- Clustering of tweets and hashtags using the Reinert method (`rainette`)

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/federicocertosa2001/AI_sentiment_analysis.git
Open the .Rmd files from /scripts/ in RStudio
Install required R packages:
install.packages(c("tidyverse", "quanteda", "tidytext", "syuzhet", 
                   "vader", "rainette", "wordcloud", "reshape2", 
                   "qdap", "lubridate", "ggplot2", "readxl"))
Knit the files to HTML or PDF using RStudio
📊 Technologies & Packages Used

tidyverse, dplyr, ggplot2, lubridate
quanteda, tidytext, wordcloud, reshape2
syuzhet, vader, qdap, rainette, SnowballC
📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author

Federico Certosa Data Analytics Engineer 
Tor Vergata University project – 2025 
