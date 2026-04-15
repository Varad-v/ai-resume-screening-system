# AI Resume Screening System with Tracing

## Overview
This project is an AI-powered Resume Screening System built using LangChain and Groq API with LangSmith tracing enabled.

The system evaluates resumes against a job description and provides:
- Skill Extraction
- Resume Matching
- Candidate Fit Score
- Explainable Feedback

---

## Objective
To automate resume screening for recruiters by comparing candidate resumes with job requirements using LLM-based evaluation.

---

## Features
- Extracts candidate skills, tools, and experience
- Matches resume data with job description
- Assigns Fit Score (0–100)
- Provides reasoning for score
- Supports Strong / Average / Weak candidate evaluation
- Includes LangSmith tracing for debugging and monitoring

---

## Tech Stack
- Python
- LangChain
- Groq API
- LangSmith
- Google Colab / Jupyter Notebook

---

## Project Workflow
Resume → Skill Extraction → Matching → Scoring → Explanation

---

## Sample Inputs
### Job Description
Data Scientist Role requiring:
- Python
- SQL
- Machine Learning
- Deep Learning
- NLP
- Power BI

### Candidate Types
- Strong Candidate
- Average Candidate
- Weak Candidate

---

## LangSmith Tracing
Tracing is enabled using:

```python
LANGCHAIN_TRACING_V2=true
```

Used for:
- Monitoring pipeline execution
- Debugging outputs
- Visualizing chain steps

---

## Installation

```bash
pip install langchain langchain-groq langsmith
```

---

## Run Project

Execute all notebook cells in sequence.

---

## Learning Outcomes
This project demonstrates:
- LLM Pipeline Design
- Prompt Engineering
- Resume Evaluation Automation
- LangChain LCEL Usage
- LangSmith Monitoring

---

## Author
Varad Khatavkar
