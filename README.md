# Twitter Sentiment Analysis and Word Cloud Generator

This project collects real-time Twitter data using the Tweepy API, performs sentiment analysis using TextBlob, and generates a word cloud based on popular terms in the tweets. The goal is to analyze Twitter trends and provide insights into public sentiment.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project uses the **Tweepy** library to access the Twitter API and gather tweets based on specified search terms. The **TextBlob** library is used for performing sentiment analysis on the tweets, classifying them as positive, negative, or neutral. Additionally, a **WordCloud** is generated to visualize the most frequently used words in the tweets.

### Technologies Used
- Python
- Tweepy (for accessing Twitter API)
- TextBlob (for sentiment analysis)
- WordCloud (for generating word clouds)
- Pandas (for data manipulation)
- NumPy (for array handling)
- Matplotlib (for visualizations)

## Features

- **Real-time Twitter Data Collection:** Fetch tweets from Twitter using the Tweepy API.
- **Sentiment Analysis:** Classify tweets into positive, negative, or neutral sentiments using TextBlob.
- **Word Cloud Generation:** Create a word cloud based on the most frequent words used in the collected tweets.
- **Visualization:** Display sentiment distributions and word cloud images using Matplotlib.

## Installation

### Prerequisites

- Python 3.6+
- Pip (Python package manager)
