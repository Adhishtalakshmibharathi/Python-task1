# 🕷️ WebScrape Analyzer — Python Internship Task 1

## 📌 Project Overview
**WebScrape Analyzer** is an interactive web-based dashboard that simulates a **Python Web Scraping and Sentiment Analysis system**.  
It allows users to select a source type, choose a topic, and generate realistic scraped news articles with sentiment results.

This project is created as part of a **Python Internship Task 1** to demonstrate concepts like **web scraping, NLP sentiment analysis, and data visualization**.

---

## 🚀 Features
- Select different content sources (News / Tech / Finance / Science)
- Choose analysis topic (AI, Climate, Crypto, Space, Healthcare, EV)
- Choose number of articles (5 / 8 / 10)
- Terminal-style scraping simulation
- Scraped data displayed in a clean table format
- Sentiment classification (Positive / Neutral / Negative)
- Sentiment score visualization bar
- Sentiment distribution chart
- Sentiment trend line graph
- Top keyword cloud generation
- AI summary of sentiment trend
- Python code preview tab included inside UI

---

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript
- Anthropic Claude API (used to generate realistic JSON data)

---

## 📂 Project File
- `web_scraper_analyzer.html` → Main file (contains full UI, CSS, and JavaScript)

---

## ⚙️ How to Run the Project
### Method 1: Run in Browser
1. Download or copy the project file
2. Open `web_scraper_analyzer.html` in **Google Chrome**
3. Select source, topic, and number of articles
4. Click **Run Scraper & Analyze**

---

## 🔑 API Note (Important)
This project includes a fetch request to:

`https://api.anthropic.com/v1/messages`

To make the project fully working, you must provide a valid **Anthropic API Key** inside request headers.

Otherwise, the terminal simulation will work but the data may not load properly.

---

## 📊 Output Displayed
After running the scraper, the dashboard shows:

- Headline
- Source
- Date
- Sentiment type
- Sentiment score
- Keywords
- Total article stats
- Sentiment trend chart
- Sentiment distribution chart
- AI-generated summary

---

## 🧠 Internship Task Learning Outcomes
This project demonstrates:
- Web scraping workflow simulation
- Sentiment analysis concept (VADER style)
- JSON data generation and parsing
- Data table rendering
- Dashboard UI and visualization design
- API integration using JavaScript

---

## 👩‍💻 Author
**Adhi**  
Python Internship Project — Task 1  
Department: Computer Science and Engineering  

---

## 📌 License
This project is for educational and internship demonstration purposes.
