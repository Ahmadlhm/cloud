# 📰 Cloud-Based News Aggregator with Sentiment Analysis

This project is a cloud-native Python application that fetches news articles using the NewsAPI, performs sentiment analysis on the headlines using TextBlob, and displays the results in a user-friendly Streamlit interface.

---

## 🚀 Features

- Fetches real-time news headlines by country and category
- Performs sentiment analysis (Positive, Negative, Neutral)
- Displays results in a table and pie chart
- Provides a web interface using Streamlit
- Saves the analysis results into a CSV file

---

## 🛠️ Technologies Used

- **Python**
- **TextBlob** – for sentiment analysis
- **Pandas** – for data handling
- **Matplotlib** – for pie chart visualization
- **Streamlit** – for the web interface
- **NewsAPI** – for fetching news headlines

---

## 🔧 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/news-sentiment-analysis.git
cd news-sentiment-analysis
```

### 2. Install the required packages
```bash
pip install -r requirements.txt
```

### 3. Add your NewsAPI key
Open the `app.py` and replace `"your_api_key_here"` with your real NewsAPI key.

### 4. Run the application
```bash
streamlit run app.py
```

---

## 📂 Output

- Interactive data table of headlines with sentiment
- Pie chart of sentiment distribution
- A CSV file (`news_sentiment_results.csv`) storing the analysis

---

## 👨‍💻 Team Members

- Mohammed Basem Nasrallah
- Mohammed Ahmad Abufoul
- Ahmad Yaser Allaham

---

## 📜 License

This project is for educational purposes and follows open academic guidelines.