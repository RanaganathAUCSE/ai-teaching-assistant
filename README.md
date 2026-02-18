# AI Teaching Assistant

## Overview
This project implements an AI-powered teaching assistant that can:
1. Understand student queries using NLP.
2. Recommend adaptive learning paths based on performance.

This system was built as part of the AI/ML Engineer technical assessment.



## Features
- Student query intent classification
- Topic identification
- Difficulty level prediction
- Personalized learning path recommendation
- Interactive command-line input



## System Architecture

### Module 1: Query Understanding
- Sentence embeddings using MiniLM
- Logistic regression classifiers
- Outputs:
  - Intent
  - Topic
  - Difficulty

### Module 2: Adaptive Learning Path
- Rule-based personalization
- Inputs:
  - Quiz score
  - Attempts
  - Time spent
- Outputs:
  - Next topic
  - Action (Revision / Practice / Advance)
  - Difficulty adjustment



## Technologies Used
- Python
- Sentence Transformers
- Scikit-learn
- Pandas
- Google Colab



## How to Run
1. Open the notebook in Google Colab.
2. Run all cells step by step.
3. Use the interactive input cell.
4. Enter:
   - Student query
   - Quiz score
   - Attempts
   - Time spent
5. View the system output.



## Example Output
Query: I don’t understand gradient descent
Score: 45

Output:
Intent: Doubt
Topic: Optimization
Difficulty: Beginner
Recommendation: Revision
Next Topic: Previous fundamentals
Difficulty Adjustment: Decrease




## Dataset
A small synthetic dataset of labeled student queries was created to simulate real interactions, as allowed by the assessment guidelines.

---

## Assumptions
- Student performance is represented using score, attempts, and time spent.
- Small dataset used due to time constraints.

---

## Limitations
- Small synthetic dataset.
- Rule-based recommendation instead of full reinforcement learning.
- No graphical user interface.

---

## Author
Ranganath  
AI/ML Engineer Candidate – AU Campus Recruitment 2026
