# Math GPT Bot

A powerful Math GPT Bot built using LangChain and GroqAI to solve mathematical expressions, process queries, and provide accurate responses. The bot leverages GroqAI's LLM models, LangChain for conversational AI, and SQLite3 for storing chat history.

## Features

- **Mathematical Expression Solving:** The bot can solve a wide variety of mathematical expressions, including algebraic, arithmetic, and calculus problems.
- **Custom Tools Integration:** Uses custom tools like Wikipedia and LLMathChain to gather and enhance mathematical knowledge.
- **Chat History:** The bot maintains conversation context with a feature that stores chat history using session IDs.
- **Interactive User Interface:** Built with Streamlit to provide a smooth and interactive user experience for querying and getting responses.

## Tech Stack

- **LangChain:** For building conversational AI pipelines.
- **GroqAI:** For utilizing large language models (LLMs) to generate responses.
- **SQLite3:** For storing and retrieving chat history.
- **Streamlit:** For building the interactive web interface.
- **Python:** Main programming language for development.

## Setup Instructions

### Prerequisites

Before running the project, ensure you have the following:

- Python 3.7 or higher
- GroqAI API Key
- SQLite3 database (`student.db` for local testing)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/math-gpt-bot.git
