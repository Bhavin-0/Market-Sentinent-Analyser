# 📊 Market Sentiment Analyzer

A real-time, frontend-only web dashboard that analyzes and visualizes public sentiment around financial assets like **Tesla**, **Bitcoin**, and **Apple** using data from Twitter, news sources, and crypto platforms. Built during a 2-day hackathon by a 6-member team.

---

## 🚀 Project Overview

Market Sentiment Analyzer collects and processes real-time social media and news content, performs sentiment analysis via Hugging Face models, and visualizes market mood with charts and metrics — all **without a backend**.

Users can:
- Track current and historical sentiment
- Overlay asset price with sentiment trends
- View sentiment breakdown of news and social posts
- Filter by asset, platform, and time range

---

## 🧠 Tech Stack

| Layer        | Technology                         |
|-------------|-------------------------------------|
| **Frontend**| React, TypeScript                   |
| **Styling** | Tailwind CSS, ShadCN UI             |
| **Visualization** | Recharts / Chart.js          |
| **APIs**     | NewsAPI, Twitter API, CryptoPanic  |
| **ML**       | Hugging Face Inference API         |
| **Hosting**  | Vercel                             |

---

## 🖥️ Features

- 🔍 Asset Selector (Tesla, Apple, Bitcoin, etc.)
- 📰 Platform Filters (News, Twitter, Crypto)
- 📆 Time Range Filters (1D, 7D, 30D, 90D)
- 📊 Interactive Charts:
  - Sentiment Trend Line
  - Price vs Sentiment Correlation
  - Daily Volume with Sentiment Breakdown
- 📌 Key Metrics:
  - Current and Avg. Sentiment
  - Total Posts Analyzed
  - Sentiment Percentages (Pos/Neg/Neutral)
- 🧾 Recent Posts Feed with:
  - Source attribution
  - Confidence scores
  - Color-coded sentiment badges

---

## 🔗 API Integrations

- **NewsAPI** – Financial & global news
- **Twitter API v2** – Tweets about selected asset
- **CryptoPanic API** – Crypto-specific updates
- **Hugging Face API** – Sentiment classification (positive, neutral, negative)
---

## 🛠️ Setup Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/market-sentiment-analyzer.git

2. Install dependencies:
  ```bash
  cd market-sentiment-analyzer
  npm instal

3.start the app:
 ```bash
 npm run dev

---
## 📦 Deployment

Hosted on **Vercel**  
➡️ Live Demo: [Coming Soon]

## 👥 Team

- [@abhiii09abhi](https://github.com/abhiii09abhi)
- [@prajwal435](https://github.com/prajwal435) 
- [@sanketdattatraymane](https://github.com/sanketdattatraymane) 
- [@SiddhantMishra](https://github.com/silicon005) 
- [@Bhavin](https://github.com/Bhavin-0) 

## 📄 License

MIT License
