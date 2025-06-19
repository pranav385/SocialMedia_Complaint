# 🚀 Social Media Complaint Scraper – Twitter & LinkedIn (Blinkit Case Study)

⚠️ Disclaimer:
This project is intended for educational purposes only.

This project focuses on scraping complaint posts about **Blinkit** from **Twitter (X)** and **LinkedIn**, with the goal of extracting user grievances, analyzing sentiment, and enabling issue tracking through structured data.

---

## 📌 Objective

To extract customer complaints from social media platforms and convert unstructured posts into a clean dataset for further analysis like:
- Sentiment classification
- Reason identification (refund, delivery, expired item, etc.)
- Trend detection

---

## 📊 Platforms Covered

- **Twitter (X)** – Public tweets with complaint-related keywords
- **LinkedIn** – Public posts with complaint content (login required)

---

## ⚙️ Features

### ✅ Twitter Scraper:
- Automated login with fallback from email to username
- Custom search URL using keywords and date range
- Dynamic scrolling and tweet loading using **Selenium**
- Extracts:
  - Complainant name & handle
  - Date posted
  - Tweet content
  - Link to tweet
  - Media presence
  - Engagement (comments, reposts, likes, views)

### ✅ LinkedIn Scraper:
- Automated login via email or username with password
- Handles redirects and alternate input prompts
- Parses posts using **BeautifulSoup**
- Extracts complaint content and metadata

---

## 📁 Output Format

Saved as `.csv` or `.xlsx`, including:
- `Complainant Name`
- `Username`
- `Date Posted`
- `Cleaned_Post_Text`
- `Post Link`
- `Media Presence`
- `Comments`, `Reposts`, `Likes`, `Views`

---

## 🧠 NLP Potential (Future Scope)

- **Sentiment Analysis**: Classify posts as Positive / Negative / Neutral
- **Structured Extraction**: Extract place, reason, product, affected component
- **Trend Alerts**: Detect surges in specific complaints (e.g., late delivery, expired items)

---

## 🔧 Tech Stack

- Python
- Selenium
- BeautifulSoup
- Pandas
- ChromeDriver
- Randomized delays (anti-bot detection)

---
