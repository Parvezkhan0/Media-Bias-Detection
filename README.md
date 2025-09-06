# 📰 Newspaper-Scrape

**By Parvez Khan**

Welcome to **Newspaper-Scrape** — a project that digs into the **New York Times Technology section** and pulls out the good stuff. Using a mix of **web scraping, natural language processing, sentiment analysis**, and a little Python magic, this tool automatically:

* Extracts article text and metadata
* Summarizes content
* Analyzes polarity (positive/negative tone)
* Measures subjectivity (objective vs. opinionated writing)

Perfect if you want a quick pulse on what’s happening in tech without wading through every single article.

---

## ⚡ Features

* 🧠 **Smart NLP**: Summaries generated with `textblob`
* 😀😐☹️ **Sentiment Analysis**: Detects how positive, neutral, or negative an article feels
* 🗂️ **Metadata Extraction**: Grab titles, authors, and publication dates
* 🕵️ **Scraping Power**: Runs through the New York Times Tech section using `newspaper3k` and `BeautifulSoup`

---

## 🛠️ Installation & Dependencies

To run this project locally, make sure you’ve got **Python 3+** and the following packages installed:

```bash
pip install textblob newspaper3k requests bs4
```

No need to install `time` or `random` — those come built into Python.

---

## 🚀 Getting Started

1. Clone this repo using **GitHub Desktop** or your favorite IDE (PyCharm works great).
2. Run the script and let it pull articles directly from the NYT Tech section.
3. View summaries, sentiment scores, and metadata in seconds.

---

## 🤝 Contributing

Spotted a bug? Have an idea for a new feature? Drop an issue in the **Issues tab** — I’ll try to respond quickly.

---

## 🎉 Thanks!

Thanks for checking out **Newspaper-Scrape**! I hope this project saves you time and sparks ideas for your own experiments with **web scraping + NLP**.

