# Mental Health Counseling ChatGPT Clone

A Django-based chatbot application designed to provide mental health counseling and support. This project replicates the functionality of ChatGPT, tailored specifically for mental health advice and conversational guidance.

## Features

- **Mental Health Support**: Offers empathetic responses and counseling advice.
- **Customizable**: Extend functionality to include more specialized counseling services.

## Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript (jQuery)
- **AI Integration**: OpenAI GPT-3.5-turbo
- **Database**: SQLite (default)

## Demo
<img width="1306" alt="image" src="https://github.com/user-attachments/assets/601542b9-2652-485f-936a-956159590cc6">

## Prerequisites

Ensure you have the following installed on your system:

- Python 3.12.7
- Django 5.1.3
- OpenAI Python SDK (`openai`) 1.54.4
- Git (optional)
- python-dotenv 1.0.1
- datasets 3.1.0

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/JkShaw/chatbot-ai.git
   cd chatbot-ai
2. Add OPENAI_API_KEY in .env
3. python manage.py migrate
4. python manage.py runserver
5. Go to http://localhost:8000/
