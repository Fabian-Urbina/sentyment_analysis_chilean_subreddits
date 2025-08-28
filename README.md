# Sentiment Analysis of Chilean Subreddits

This project applies sentiment analysis to discussions in Chilean subreddits in order to explore how online communities differ in tone and emotional expression.

* Data Collection & Preprocessing: Extract Reddit comments, clean and normalize Spanish text (including slang like weon, bacán, etc.).

* Modeling: Start with a pretrained Spanish sentiment model and experiment with fine-tuning on Chilean data to better capture local dialect and context.

* Evaluation: Compare the performance of the base model vs. the fine-tuned version.

* Analysis & Insights:

* Compute positivity/negativity/neutrality scores for each subreddit.

* Visualize and compare subreddits (e.g., which are more positive, more negative, or more polarized).

* Identify common words or phrases strongly associated with sentiment.

Objective: Beyond testing AI models, the project aims to show how cultural and linguistic variations (like Chilean Spanish slang) affect NLP tasks, and how fine-tuning can improve performance.

## ⚙️ Requirements

- Python ≥ 3.8  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- jupyter  
- MySQL or SQL Server (SSMS)
