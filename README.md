# Predicting Price Moves Using News Sentiment

This project explores the relationship between financial news sentiment and stock price movements. The goal is to analyze how news sentiment correlates with stock returns using quantitative and sentiment analysis techniques.

---

## Project Structure

- **data/**: Contains historical stock price data and financial news datasets.
- **notebooks/**: Jupyter notebooks for each task:
  - `task_1_news_sentiment_analysis.ipynb`
  - `task_2_technical_analysis.ipynb`
  - `task_3_correlation_analysis.ipynb`
- **src/** (optional): Python scripts for reusable code.
- **reports/**: Interim and final reports summarizing findings.

---

## Tasks Overview

### Task 1: News Sentiment Analysis
- Preprocessed financial news data.
- Applied sentiment analysis on headlines using NLTK's VADER.
- Visualized sentiment distributions.

### Task 2: Quantitative Analysis Using TA-Lib and PyNance
- Loaded stock price data.
- Calculated technical indicators (moving averages, RSI, MACD).
- Visualized stock price with indicators.

### Task 3: Correlation Between News and Stock Movement
- Aligned news and stock price data by date.
- Computed daily returns and average daily sentiment scores.
- Calculated correlation between news sentiment and stock returns.
- Visualized correlation results.

---

## Setup and Installation

1. Clone the repo:

```bash
git clone https://github.com/saron03/predicting-price-moves-news-sentiment.git
cd predicting-price-moves-news-sentiment
```

2. Create a virtual environment and activate it (optional but recommended):

```bash
python -m venv env
# Windows
.\env\Scripts\activate
# macOS/Linux
source env/bin/activate
```

3. Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

- Open the notebooks in the notebooks/ folder in Jupyter.

- Run each notebook step-by-step for the corresponding task.

