# Sentiment Classification & Summarization of Amazon Reviews using IBM Granite Models

## Project Overview
This project analyzes Amazon product reviews to extract valuable insights using AI.  
We classify the sentiment of each review (Positive, Negative, Neutral) and generate short summaries to highlight the main idea of each review.  
This helps businesses understand customer satisfaction and areas for improvement efficiently.

## Objective
- Classify sentiment of reviews to understand customer perception.
- Summarize reviews for quick insights.
- Demonstrate the use of IBM Granite LLM (simulated via Transformers).

##  Dataset
- Original dataset: [Kaggle - Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- Subset used: 1,000 randomly sampled reviews (included in this repository as `Reviews_subset.csv`).

## Files
- `Sentiment_Analysis_Project.ipynb`: Google Colab notebook with full analysis.
- `Reviews_subset.csv`: Raw subset dataset used for analysis.
- `README.md`: Project documentation.

## Insights & Findings
- Positive reviews: ~78%
- Neutral reviews: ~10%
- Negative reviews: ~12%
- Common positive comments: good taste, well-packaged, fast delivery.
- Common negative comments: poor packaging, late delivery.

## Conclusion & Recommendation
- Most customers are satisfied with the products.
- Improve logistics and packaging to address common complaints.

## AI Support Explanation
We used IBM Granite LLM (simulated via Huggingface Transformers) for:
- **Sentiment Classification:** using `sentiment-analysis` pipeline.
- **Summarization:** using `summarization` pipeline.

### Tools & Platform
- Google Colab: development & execution.
- Python libraries: pandas, matplotlib, scikit-learn, transformers.
- Github: repository & version control.

---

### 📂 Repository Link
[Link to this repository](https://github.com/ferdianty/amazon-review-analysis)

