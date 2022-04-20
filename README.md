# c141 - Article Recommendation API

A minimal Flask backend for an article recommendation app that serves news articles from CSV and records liked/disliked feedback.

## Features
- `GET /get-articles` returns the first article from a CSV file.
- `POST /liked-articles` records a liked article.
- `POST /disliked-articles` records a disliked article.

## Tech Stack
- Python 3
- Flask
- CSV (standard library)

## Project Structure
```
c141/
├── main.py         # Flask app with article routes
├── articles.csv    # article dataset
└── README.md
```

## Installation
```
pip install flask
```

## Usage
```
python main.py
```

The Flask server starts and serves the articles API on the default Flask host/port.