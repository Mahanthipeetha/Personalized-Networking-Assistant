# Personalized Networking Assistant

## 🎥 Project Demo

A short demonstration of the **Personalized Networking Assistant** is available here:

▶ **Demo Video:** *Add your Google Drive or YouTube demo link here.*

---

## About the Project

The **Personalized Networking Assistant** is an AI-powered web application designed to help users start meaningful and engaging conversations during networking events, conferences, workshops, and professional meetups.

The application analyzes an event description and the user's interests to identify key discussion topics using **DistilBERT**. It then generates personalized conversation starters with **GPT-2** and verifies important topics using the **Wikipedia API** to provide accurate and relevant information.

The main objective of this project is to demonstrate how Natural Language Processing (NLP) and transformer models can be combined to create an intelligent assistant that helps users network more confidently.

---

## Features

* Analyze event descriptions using AI
* Extract key discussion themes
* Generate personalized conversation starters
* Fact-check topics using the Wikipedia API
* FastAPI-based REST API services
* Interactive Streamlit dashboard
* Conversation history management
* User feedback logging
* Local JSON-based data storage
* Modular and scalable project architecture

---

## Technologies Used

### Frontend

* Streamlit

### Backend

* FastAPI
* Python 3.11+

### Artificial Intelligence

* Hugging Face Transformers
* DistilBERT
* GPT-2

### Data & APIs

* Wikipedia API
* JSON (history.json & feedback.json)

### Testing

* Pytest
* Httpx

### Version Control

* Git

---

## Project Structure

```text
Personalized-Networking-Assistant/
│
├── app.py                  # Streamlit application and user interface
├── event_analyzer.py       # Event theme extraction using DistilBERT
├── topic_generator.py      # Conversation starter generation using GPT-2
├── fact_checker.py         # Wikipedia fact verification service
├── test_services.py        # Unit tests for application services
├── history.json            # Conversation history storage
├── feedback.json           # User feedback storage
├── requirements.txt        # Python dependencies
├── package.json            # Project configuration (if applicable)
└── README.md               # Project documentation
```

---

## How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Personalized-Networking-Assistant.git
```

### Navigate to the project directory

```bash
cd Personalized-Networking-Assistant
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Start the FastAPI backend

```bash
uvicorn backend.main:app --reload
```

### Start the Streamlit application

```bash
streamlit run app.py
```

### Open in your browser

**Streamlit UI**

```
http://localhost:8501
```

**FastAPI Swagger Documentation**

```
http://localhost:8000/docs
```

---

## What I Learned

Working on this project helped me improve my understanding of:

* Natural Language Processing (NLP)
* Hugging Face Transformers
* DistilBERT and GPT-2 integration
* FastAPI backend development
* Streamlit application development
* REST API design
* Wikipedia API integration
* JSON-based data persistence
* Unit testing with Pytest
* Building modular AI applications

It also gave me practical experience in integrating multiple AI technologies into a real-world application that supports professional networking.

---

## Future Improvements

Some features that can be added in future versions include:

* User authentication and profiles
* Integration with LinkedIn events
* Multi-language conversation generation
* Voice-based interaction
* Cloud database integration
* Conversation quality feedback analytics
* Personalized networking recommendations
* Event calendar integration
* Docker deployment
* Mobile application support

---

## Author

**Mahanthi Peetha**

B.Tech Computer Science and Engineering

Seshadri Rao Gudlavalleru Engineering College

Graduation Year: **2027**

This project was developed as an academic project to explore the application of Artificial Intelligence and Natural Language Processing in enhancing professional networking experiences.
