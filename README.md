# summarizer-ai 

This project implements a text summarization application using Facebook's pre-trained BART model. It consists of two main components: a FastAPI service for handling the summarization inference and a Streamlit user interface for user interaction.

## Technologies Used

- **FastAPI**: A modern, fast web framework for building APIs with Python 3.6+ based on standard Python type hints.
- **Streamlit**: An open-source app framework for Machine Learning and Data Science projects.
- **Transformers**: A library by Hugging Face for state-of-the-art Natural Language Processing (NLP).
- **Docker**: To containerize the application for consistent deployment and execution.

## Features

- Text summarization using the BART model.
- User-friendly interface for inputting text and displaying the summary.
- Containerized environment for easy deployment and scalability.

## Getting Started

### Prerequisites

- Docker and Docker Compose installed on your machine.

### Running the Application

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/JadaMohamed/summarizer-ai
   cd summarizer-ai

2. Build and run the Docker containers using Docker Compose:
   ```bash
   docker-compose up --build
3. Access the application in your web browser:
    Streamlit UI: http://localhost:8501
