# MCQ Generator

A FastAPI application that generates multiple-choice questions from uploaded documents.

## Features

- Supports PDF, DOCX, and TXT files
- Generates questions using AI (via OpenRouter)
- Provides downloadable PDF and text versions
- Ready for deployment with Docker

## Setup

1. Clone the repository
2. Create a `.env` file (use `.env.example` as template)
3. Install dependencies: `pip install -r requirements.txt`
4. Run: `uvicorn main:app --reload`

## Deployment

### Docker