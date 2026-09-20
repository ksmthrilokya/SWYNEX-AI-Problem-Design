# AI Problem Design
## SWYNEX Technologies - Artificial Intelligence Internship (Data & AI)
### Task 1: AI Problem Design

## Problem Statement
Build a sentiment classifier that automatically categorizes short product reviews as **Positive**, **Negative**, or **Neutral**.

## AI Use Case
**Text Classification** (Sentiment Analysis)

## User
Small e-commerce sellers and independent online store owners who receive customer reviews but don't have time to manually read through each one to gauge overall customer satisfaction.

## Problem It Solves
Small sellers often accumulate dozens of product reviews but lack the time or tools to analyze them at scale. A sentiment classifier lets them quickly understand whether feedback trends are positive or negative, without reading every single review manually.

## Data Source
A small custom dataset of 15-20 sample product reviews, written to reflect realistic customer feedback (e.g., "This product exceeded my expectations!", "Terrible quality, broke in two days", "It's okay, does the job but nothing special").

## Constraints
- English language text only
- Short reviews (1-3 sentences each)
- No support for sarcasm or mixed-language text in this first version
- Limited to 3 sentiment categories: Positive, Negative, Neutral

## Evaluation Approach
- Manually label the 15-20 reviews with their expected sentiment (ground truth)
- Run each review through the classifier and record its predicted sentiment
- Calculate accuracy: (number of correct predictions / total reviews) x 100
- Note down any misclassified reviews as failure cases for future improvement

## Success Criteria
The classifier should correctly identify sentiment for at least 80% of the sample reviews (12 out of 15, or equivalent).

## Author
Kolluru Sai Mani Thrilokya
