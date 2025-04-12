# AI-Powered Personalized Newsletter Generator

## Overview

This project generates personalized newsletters by fetching articles from RSS feeds and ranking them based on user interests using NLP techniques. Each user receives a Markdown file containing the most relevant articles.

## Objective

Build a system that:
- Retrieves news from RSS feeds
- Matches content to user interests using NLP
- Ranks articles by relevance
- Outputs structured newsletters in Markdown format

## Key AI Tools Used

- **TfidfVectorizer**: Converts text to vector format for comparison
- **Cosine Similarity**: Measures how closely articles match user interests

## User Profiles

Includes personas like:
- Tech enthusiast (AI, blockchain)
- Finance expert (cryptocurrency, markets)
- Sports journalist
- Entertainment buff
- Science/space enthusiast

## How It Works

1. Fetch RSS feed articles
2. Process article content with TF-IDF
3. Compare against user interests using cosine similarity
4. Select top articles
5. Generate `.md` newsletters

## Requirements

- Python 3.7+
- Libraries: `feedparser`, `scikit-learn`

Install with:
```bash
pip install feedparser scikit-learn
