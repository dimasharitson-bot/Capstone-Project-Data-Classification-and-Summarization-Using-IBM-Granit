# Capstone-Project-Data-Classification-and-Summarization-Using-IBM-Granit

Title: Mid-Range Smartphone Sentiment Analysis using IBM Granite

Project Overview
This project analyzes public sentiment towards three mid-range smartphones Samsung Galaxy A56, Xiaomi 14T, and Vivo V40 5G  using AI-powered natural language processing. YouTube comments from technology reviews were collected, cleaned, and processed with the IBM Granite 3.3-8B-Instruct model to extract sentiment (positive, negative, neutral) and feature-specific insights (e.g., design, battery, camera). The goal is to provide actionable recommendations for product development and marketing strategies.

Raw Dataset Link
The dataset consists of over 450 user comments scraped from YouTube (David GadgetIn channel).
File: youtube_comments_hp.csv
Columns:
- jenis_hp: Smartphone model (Samsung Galaxy A56, Xiaomi 14T, Vivo V40 5G)
- username: Comment author
- comment: The comment text
- likes: Number of likes on the comment

Insights & Findings
1. Executive Summary
- Total comments analyzed: 450
- Positive sentiment: 38.9%
- Negative sentiment: 13.8%

2. Performance Ranking
- Samsung Galaxy A56 – Sentiment Score: 27.3 (Market Leader)
- Xiaomi 14T – Sentiment Score: 24.0
- Vivo V40 5G – Sentiment Score: 24.0

3. Key Findings
- Samsung Galaxy A56 → Strength: Design (7 mentions); Weakness: Build quality
- Xiaomi 14T → Strength: Design (6 mentions); Weakness: Selfie camera quality
- Vivo V40 5G → Strength: Design (6 mentions); Weakness: Battery life

4. Business Recommendations
- Samsung Galaxy A56 → Improve build quality; highlight design in marketing.
- Xiaomi 14T → Enhance selfie camera quality; promote design appeal.
- Vivo V40 5G → Improve battery performance; leverage design in campaigns.

AI Support Explanation
The project leveraged IBM Granite 3.3-8B-Instruct to conduct sentiment classification and aspect-based analysis.
- Sentiment Classification: Classified comments into Positive, Negative, Neutral with confidence scores.
- Aspect Extraction: Identified key product features (battery, camera, performance, design, software, price).
- Parameter Tuning: Used top_k=10, top_p=0.9, max_tokens=200, and repetition_penalty=1.3 for better accuracy.
- Error Handling: Low-confidence results were flagged as uncertain, ensuring reliable insights.

AI support enabled the project to capture nuanced opinions (including sarcasm, mixed sentiment, and bilingual comments) more effectively than rule-based approaches.
