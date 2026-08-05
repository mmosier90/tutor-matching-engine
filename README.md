# Tutor Matching Engine

This project is an educational decision-support system to match students and tutors.
It uses NLP to rank potential tutor-student matches using information from student and tutor profiles.

The pipeline
combines student, tutor, and assignment data;
constructs text profiles;
converts those profiles into TF-IDF vectors; and
calculates cosine similarity between every student and tutor.
The resulting similarity scores are used to generate a ranked list of potential tutors for each student.

## Project Status

The current version is a similarity-based recommendation proof of concept. Future branches will explore supervised classification and unsupervised clustering.

## Privacy

The repository does not include proprietary student data, personally identifiable information, or spreadsheet credentials.
