# Tutor Matching Engine

This project explores how machine learning can support tutor assignment and student success in an educational services setting.

The initial recommendation engine uses Natural Language Processing (NLP) to compare student and tutor profiles and generate ranked tutor recommendations. Additional branches explore unsupervised clustering of student profiles and future predictive models for student engagement and retention.

## Recommendation Engine

The recommendation pipeline:

- Combines student, tutor, and assignment data
- Constructs text profiles from structured and qualitative information
- Converts each profile into TF-IDF feature vectors
- Measures similarity using cosine similarity
- Generates ranked tutor recommendations for each student

The recommendation model is designed as a decision-support tool. Final tutor assignments remain a human decision.

## Repository Structure

### Main Branch

Develops the baseline recommendation engine using TF-IDF vectorization and cosine similarity.

### Unsupervised Clustering

Explores whether student profiles naturally group together based on shared characteristics. This branch evaluates K-Means clustering as an exploratory analysis and documents the feature engineering process used to improve cluster interpretation.

### Planned Work

Future development will explore supervised machine learning models to predict student outcomes such as disengagement, cancellation, and graduation, allowing historical assignment data to inform future tutor recommendations.

## Current Status

This project is under active development. The repository documents both successful models and exploratory analyses to illustrate the iterative process of building, evaluating, and improving machine learning solutions.

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Google Colab
- Google Sheets API
- Natural Language Processing (TF-IDF)
- Cosine Similarity
- K-Means Clustering

## Privacy

This repository contains only sanitized code and documentation. No proprietary student information, personally identifiable information, or production credentials are included.
