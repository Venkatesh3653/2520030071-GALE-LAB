# Week 1: Introduction to Gemini AI

This practical demonstrates how to make a basic call to Google's Gemini API using the `google-genai` Python SDK.

## Files

- `main.py` - Loads an API key and asks Gemini to explain Artificial Intelligence in simple words.
- `requirements.txt` - Python packages required for this practical.

## Prerequisites

- Python 3.10 or later
- A Google Gemini API key

## Setup

1. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

2. Create a `.env` file in this directory:

   ```dotenv
   GEMINI_API_KEY=your_api_key_here
   ```

3. Run the script:

   ```bash
   python main.py
   ```

## Output

The program prints Gemini's explanation of Artificial Intelligence in simple words.

## Security

- Never commit or share your API key.
- Add `.env` to `.gitignore` if it is not already ignored.
