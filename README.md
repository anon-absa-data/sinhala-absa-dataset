# SalAngaBhava Dataset

## Overview
The *SalAngaBhava* dataset is designed for research in Natural Language Processing (NLP), with a focus on Aspect-Based Sentiment Analysis (ABSA) for Sinhala language data. It supports reproducible research and enables fine-grained sentiment understanding at the aspect level.

## Dataset Structure
The dataset is provided in a machine-readable and researcher-friendly format. Each instance contains the following fields:

- **sentence id**: A unique identifier assigned to each sentence for reference and traceability.  
- **product name**: The name of the product being reviewed.  
- **rating**: The numerical rating assigned by the user to the product (e.g., on a 1–5 scale).  
- **price**: The listed price of the product at the time of review, when available.  
- **review**: The original review text written in Sinhala, which may include native Sinhala script or Romanized Sinhala.  
- **cleaned review**: The processed version of the review after cleaning and transliteration, where applicable.  
- **review type**: The classification of the review indicating whether it is pure Sinhala, Sinhala written in English script, or code-mixed.  
- **aspect–sentiment annotation**: Each annotation is represented as a sentiment quadruple *(t, a, o, s)*, where *t* denotes the target, *a* the aspect, *o* the opinion expression, and *s* the sentiment polarity.  
- **category**: The product category to which the reviewed item belongs.

## Dataset Usage
This dataset can be used for:
- Aspect extraction
- Opinion mining
- Sentiment classification
- Multi-task learning in ABSA
- Low-resource language NLP research (Sinhala)

## Format
The dataset is provided in CSV format:
