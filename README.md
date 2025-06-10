# Telegram Discourse as a Proxy for War-Related Event Detection in Israel

## Overview

This project investigates the potential of Telegram channels as open-source intelligence (OSINT) tools for detecting and analyzing war-related events in Israel. We focus on three major public Telegram channels:

- **Abu Ali Express** (Hebrew-language news)
- **Al Jazeera Arabic** (regional coverage)
- **Pikud HaOref (Home Front Command)** (civil defense alerts)

Using multilingual natural language processing (NLP), sentiment analysis, and geospatial visualization, we demonstrate that message activity and content trends from these channels closely align with real-world conflict events.

## Features

- 📅 **Temporal Analysis**  
  Detects spikes in message volume to identify key conflict dates from 2017 to 2025.

- 🗣️ **Multilingual Topic Modeling**  
  Uses Meta AI's NLLB and Helsinki-NLP models for translation, and KeyBERT for topic extraction and clustering in Hebrew and Arabic.

- 🌍 **Geopolitical Sentiment Mapping**  
  Applies Named Entity Recognition (NER) and sentiment classification (HeBERT) to analyze emotional tone and international co-mentions.

- 📍 **Rocket Alert Dashboard**  
  Extracts Red Alert data from Pikud HaOref and maps intensity and locations using a Folium-based interactive dashboard.

## Repository Contents

| File / Folder            | Description |
|--------------------------|-------------|
| `code.ipynb`             | Python notebook implementing scraping, processing, translation, topic modeling, sentiment analysis, and visualization. |
| `Article.pdf`            | Full academic write-up of the project including methods, results, and figures. |
| `interactive_dashboard.html` | Folium-powered map of Red Alerts in Israel (2019–2025), showing alert frequency by location and month. |
| `project_instructions.pdf` | Assignment guidelines provided by the course instructor. |

## How to Use

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
