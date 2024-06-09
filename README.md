News Analysis and Company Relevance Matching

This project leverages The Guardian's API to gather news articles, processes them using natural language processing (NLP) techniques, and matches them with company descriptions to assess relevance and risk. The project demonstrates the use of machine learning models like BERT and RoBERTa for sentiment analysis and similarity matching.

Table of Contents
1) Introduction
2) Features
3) Installation
4) Usage
   a) Data Collection
   b) Data Cleaning and Preparation
   c) Sentiment Analysis
   d) Relevance Matching
   e) Project Structure

Introduction
The goal of this project is to collect and analyze news articles, calculate their sentiment-based risk percentages, and match them with company descriptions to find the most relevant articles for each company. This helps in understanding the impact of news on companies and identifying potential risks.

Features
1) Collects news articles from The Guardian's API.
2) Cleans and preprocesses the data for analysis.
3) Performs sentiment analysis using BERT.
4) Calculates risk percentages based on sentiment scores.
5) Matches news articles with company descriptions using RoBERTa for embeddings and cosine similarity for relevance.
