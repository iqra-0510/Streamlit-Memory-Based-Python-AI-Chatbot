# StudyBuddy AI 📚

A student-focused AI chatbot built using Python, Streamlit, and the Groq API.

## Features
- Academic questions and concept explanations
- Beginner-friendly study assistance
- Topic validation to restrict unrelated questions
- Conversation history for follow-up questions
- Interactive chat interface
- Clear conversation functionality

## Technologies
- Python
- Streamlit
- Groq API
- python-dotenv

## Installation

1. Clone this repository.
2. Install the dependencies:

   `pip install -r requirements.txt`

3. Create a `.env` file in the project root.
4. Add your own Groq API key:

   `GROQ_API_KEY=your_api_key_here`

   `GROQ_MODEL=openai/gpt-oss-20b`

5. Run the application:

   `python -m streamlit run app.py`

## Security
Never upload your `.env` file or expose your API key.

## Purpose
Developed as an educational chatbot project to explore AI integration, Python application development, and topic validation.