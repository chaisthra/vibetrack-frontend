# VibeTrack Frontend

A Streamlit-based frontend for the VibeTrack activity tracking application.

## Environment Variables

The following environment variables are required:

```env
BACKEND_URL=https://chaithra2003-vibetrack-backend.hf.space
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```

## Features

- User authentication (signup/login)
- Activity logging through text and voice input
- Activity visualization with charts and timelines
- AI chat assistant for insights
- Voice assistant for interactive conversations

## Deployment

This application is designed to be deployed on Streamlit Cloud. Make sure to:

1. Set the required environment variables in your Streamlit deployment
2. Install dependencies from `requirements.txt`
3. Use Python 3.10 or later

## Local Development

To run locally:

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Create a `.env` file with required environment variables

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ``` 