# Sentiment Analysis with TextBlob & VADER

This project explores the strengths and weaknesses of two popular lexicon-based sentiment analysis tools — **TextBlob** and **VADER** — by comparing their sentiment predictions on real-world social media text data.

## 🔍 Objective
To evaluate the consistency and divergence of sentiment predictions between TextBlob and VADER, understand where and why they disagree, and build a foundation for more accurate sentiment analysis solutions.

## 📊 Dataset
- Source: [Kaggle Dataset - Sentiment Analysis](https://www.kaggle.com/datasets)
- Features: `Year`, `Month`, `Day`, `Time of Tweet`, `Text`, `Sentiment`, `Platform`
- Size: 499 samples of social media posts

## 🛠️ Tools & Libraries
- **Python**
- **TextBlob** for polarity-based sentiment classification
- **NLTK VADER** for rule-based compound sentiment scoring
- **Pandas** for data preprocessing and analysis
- **Seaborn & Matplotlib** for data visualization

## 📈 Visualizations
- Countplot showing distribution of prediction agreements
- Scatterplot comparing TextBlob polarity and VADER compound scores

## 💡 Key Takeaways
- TextBlob performs better on structured, formal text.
- VADER handles informal, social-media-style text (slang, emojis, abbreviations) more effectively.
- Around 100+ entries showed conflicting predictions.
- Disagreements can be flagged for manual review or resolved via ensemble techniques.

## 🚀 Future Enhancements
- Incorporate a fine-tuned transformer model (e.g., BERT)
- Build a combined/ensemble classifier using both models
- Add neutral classification for more nuanced labeling

## 📁 Folder Structure

```
├── sentiment-analysis.ipynb
├── README.md
├── LICENSE
└── sentiment_dataset.csv
```

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
