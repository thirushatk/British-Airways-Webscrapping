✈️ Airline Review Sentiment Analysis (Web Scraping + NLP)

📌 Overview
This project builds an end-to-end NLP pipeline to analyze customer sentiment from airline reviews. It combines web scraping, text preprocessing, and sentiment analysis to extract insights from real-world data.

The system scrapes airline reviews, processes unstructured text, and classifies sentiment into Positive, Negative, and Neutral categories.

🎯 Objective
Extract real customer reviews from web sources
Perform text preprocessing and normalization
Analyze sentiment using NLP techniques
Generate insights to understand customer experience.

🌐 Data Collection (Web Scraping)
Scraped 1000+ airline reviews from Skytrax using:
requests
BeautifulSoup
Parsed paginated data and extracted raw review text
Stored data into structured DataFrame for analysis

🧹 Data Preprocessing Pipeline
Built a complete NLP preprocessing pipeline:

Text cleaning (removal of special characters)
Tokenization (NLTK)
Stopword removal
POS tagging
Lemmatization for meaningful word normalization

This ensured high-quality input for sentiment analysis.

🧠 Sentiment Analysis
Used VADER (Valence Aware Dictionary for Sentiment Reasoning):

Calculates sentiment intensity score
Classifies reviews into:
Positive
Negative
Neutral

📊 Results
Positive: 47.9%
Negative: 41.3%
Neutral: 10.8%

📈 Visualization
Pie chart for sentiment distribution
WordCloud for key review terms
Data exported to CSV for further analysis

⚙️ Tech Stack
Language: Python
Libraries:
Pandas, NumPy
BeautifulSoup, Requests
NLTK
VADER Sentiment
Matplotlib, Seaborn
WordCloud

🔄 Workflow
Web scraping (data collection)
Data cleaning and preprocessing
NLP transformations (tokenization, POS tagging, lemmatization)
Sentiment scoring using VADER
Visualization and insights generation

📊 Key Insights
Significant portion of reviews are negative → indicates service gaps
Text preprocessing significantly improves sentiment accuracy
VADER is effective for real-world review sentiment classification
Customer feedback can be transformed into actionable insights

▶️ How to Run
git clone https://github.com/your-username/airline-sentiment-analysis
cd airline-sentiment-analysis
pip install -r requirements.txt

Run the notebook/script to scrape and analyze data.

🚀 Future Improvements
Use deep learning models (BERT / Transformers)
Build real-time sentiment dashboard
Expand scraping to multiple airlines
Deploy as API using FastAPI

📚 Key Learnings
End-to-end NLP pipeline design
Handling unstructured real-world text data
Importance of preprocessing in NLP tasks
Combining data engineering + NLP for business insights

👤 Author
Thirusha TK
AI Engineer | NLP | Machine Learning

GitHub: https://github.com/thirusha
