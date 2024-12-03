# SQL Chat Assistant

A Streamlit application that enables natural language queries to PostgreSQL databases using GPT-4.

## Requirements

- Python 3.8+
- PostgreSQL database
- OpenAI API key

## Setup

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
source venv/bin/activate  # Unix/MacOS
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```

## Configuration

Create a `.env` file:

```env
OPENAI_API_KEY=your-openai-api-key
DATABASE_URL=your-postgresql-connection-string
```

## Running the App

```bash
streamlit run app.py
```

## Features

- Natural language to SQL conversion
- Query learning and optimization
- Interactive chat interface
- Error handling
- Schema analysis
- Usage pattern tracking

## Project Structure

```
.
├── .env
├── requirements.txt
├── app.py
└── database/
    ├── __init__.py
    ├── db_utils.py
    └── usage_patterns.json
```
