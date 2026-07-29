# Zecpath AI

## Overview

Zecpath AI is an AI-powered recruitment system designed to automate different stages of the hiring process.

### Features

- Resume Parsing
- ATS Score Calculation
- AI Candidate Screening
- Interview Assistance
- Candidate Scoring
- Logging & Testing

---

## Project Structure

```
Zecpath-AI/
│
├── data/
├── parsers/
├── ats_engine/
├── screening_ai/
├── interview_ai/
├── scoring/
├── utils/
├── tests/
├── logs/
├── main.py
├── requirements.txt
├── libraries.txt
├── README.md
└── .gitignore
```

---

## Setup

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run

```bash
python main.py
```

---

## Run Tests

```bash
pytest
```

---

## Logging

Run the logger

```bash
python utils/logger.py
```

Logs will be stored inside the `logs/` directory.

---

## Author

**Anaswara Rajesh**