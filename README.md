# AI Resume Screening System with Tracing

## Objective
Build an AI-based resume screening system using LangChain and LangSmith.

## Pipeline
Resume → Skill Extraction → Matching → Scoring → Explanation

## Approach
- Extract skills from resume using keyword matching
- Compare with job requirements
- Calculate fit score (0–100)
- Provide explanation for decision

## Results

| Candidate | Score | Category |
|----------|------|----------|
| Strong   | 90   | Strong Candidate |
| Average  | 50   | Average Candidate |
| Weak     | 10   | Weak Candidate |

## Tech Stack
- Python
- LangChain
- LangSmith

## Features
- Modular pipeline
- Explainable AI output
- LangSmith tracing for debugging

## Note
Due to API quota limitations, rule-based logic was used instead of OpenAI API.
