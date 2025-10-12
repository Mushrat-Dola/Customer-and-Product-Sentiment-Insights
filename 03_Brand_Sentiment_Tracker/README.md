# 📈 Brand Sentiment Tracker (Twitter / Reddit)

### 🧭 Objective
Monitor public sentiment around major brands on social media platforms and visualize trends over time.

### ⚙️ Tools & Libraries
Python (Tweepy / Pushshift API, VADER, Plotly Dash, Pandas)

### 🧠 Steps Performed
1. Collected ~1,500 recent posts mentioning a target brand (e.g., Starbucks).  
2. Cleaned and tokenized text, removed URLs and emojis.  
3. Computed daily average sentiment using VADER polarity.  
4. Visualized trends in Plotly Dash (line + pie + top keywords charts).  
5. Added filters by date, sentiment range, and keyword.

### 📊 Insights
- Positive sentiment spikes correlate with campaign launches.  
- Negative spikes align with service or PR issues.  
- ~80% of tweets analyzed had a neutral tone.

### 📈 Dashboard Preview


### 🪄 Next Steps
- Add automatic daily updates via API.  
- Integrate with Tableau or Power BI for comparative multi-brand view.
