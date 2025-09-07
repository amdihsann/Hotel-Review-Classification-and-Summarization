# Analysis of Hotel Reviews: Transforming Feedback into Actionable Insights
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kYDVg4gwzbVx9lz-AW8v8Hw431ShcIYO?usp=sharing)

## Project Overview

This project develops a robust, automated data analysis workflow to transform unstructured hotel reviews into a structured business intelligence dashboard. The primary goal is to provide hotel management with precise, data-driven recommendations to enhance guest satisfaction and operational efficiency, ultimately turning raw feedback into a strategic asset.

## Key Features

This project is more than a simple script; it's an end-to-end analysis system built with professional practices in mind:

* Hybrid Analysis System: Combines high-precision Rule-Based Logic (for topic extraction) with the contextual power of **Large Language Models** (for sentiment and summarization).
* Robust Multi-Model Engine: Features a smart **fallback strategy**, automatically switching to a secondary model if the primary one fails, ensuring system stability.
* Encapsulated Workflow: A structured Python `Class` encapsulates the entire process, making the system modular and easy to understand.
* Strategic Visualization: The final output is a Priority Matrix Dashboard, a powerful tool for managers to instantly identify what's working, what's broken, and where the hidden opportunities lie.


### A Note on Dataset Sampling

To ensure efficiency during development and to demonstrate the system's full end-to-end functionality within a standard computing environment (like Google Colab), this analysis was performed on a **representative random sample of 200 reviews** from the full dataset. The system is designed to be fully scalable to the entire dataset given sufficient computational resources.


## Summary of Findings

The analysis of the 200 sample reviews provided the following strategic insights:

* Core Strengths: `Location`, `Hotel Facilities`, and `Cleanliness` are the hotel's most consistently praised assets.
* Critical Issues: `Room & Amenities` and `Staff & Service` are the most frequent drivers of guest complaints and require immediate attention.
* Hidden Risk: The `Check-in/Check-out Process`, despite low frequency, has the lowest sentiment score, marking it as a significant point of guest frustration.
* Opportunities: `Value for Money` and `Noise Level` are viewed favorably and could be developed into new strengths.


## Tech Stack

* Language: Python
* Core Libraries: Pandas, Matplotlib, Seaborn, adjustText
* NLP & Modeling: Hugging Face Transformers (`nlptown/bert-base-multilingual-uncased-sentiment`, `facebook/bart-large-cnn`), PyTorch

