# NSE Stock Analysis and Recommendation System

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-0.1.0-orange.svg)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT4.1-purple.svg)

An AI-powered pipeline for analyzing Indian NSE stocks and generating trading recommendations using multi-agent collaboration.

## Features

- **4-Stage Analysis Pipeline**:
  1. Stock Screening - Identifies promising NSE stocks
  2. Market Data Collection - Gathers price, volume, and technical indicators
  3. News Analysis - Summarizes recent news with sentiment analysis
  4. Recommendation Engine - Provides buy/sell/hold advice with target prices

- **Multi-Agent Architecture**:
  - Uses specialized LangChain agents for each analysis stage
  - Supervised workflow ensures sequential execution
  - Bright Data integration for web scraping capabilities

## Requirements

- Python 3.8+
- OpenAI API key
- Bright Data API credentials

## Installation

```bash
git clone https://github.com/yourusername/nse-stock-analysis.git
cd nse-stock-analysis
pip install -r requirements.txt
