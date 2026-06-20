# EmoTrust

AI-powered trust recovery platform that analyzes emotional expression and sincerity in conversations to help users rebuild trust and improve communication.

## Overview

EmoTrust is a mobile and backend platform designed to support trust recovery in personal relationships.

Using GPT-based emotion analysis and sincerity evaluation, the system provides insights into emotional states, communication patterns, and trust-building opportunities.

Future versions will integrate blockchain-based reputation and token mechanisms to encourage positive interactions and transparent trust management.

## Features

### Emotion Analysis

* Emotion detection from text conversations
* Emotional trend monitoring
* Sentiment scoring

### Sincerity Assessment

* GPT-powered sincerity evaluation
* Communication quality analysis
* Trust-related feedback generation

### Trust Recovery Support

* Personalized recommendations
* Relationship improvement guidance
* Conversation reflection tools

### Future Roadmap

* Blockchain-based trust records
* Token reward system
* Decentralized reputation management

## Tech Stack

### Frontend

* React Native
* Expo

### Backend

* FastAPI
* Python

### AI

* OpenAI GPT-4
* KoBERT
* NLP-based sentiment analysis

### Future Technologies

* Blockchain
* Smart Contracts
* Token Economy

## Project Structure

emotrust-app/
├── frontend/      # Expo-based mobile application
├── backend/       # FastAPI backend server
└── data/          # AI models and resources

## Getting Started

### Backend

```bash
cd backend
uvicorn main:app --reload
```

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
```

### Model Download

Download the trained KoBERT model:

kobert_regression.pt

Place the file in:

backend/data/kobert_regression.pt

## System Architecture

User Conversation
↓
Emotion Analysis
↓
Sincerity Assessment
↓
Trust Score Generation
↓
Personalized Feedback
↓
Trust Recovery Support

## Key Contributions

* Designed emotion-based trust recovery workflow
* Integrated GPT-powered emotional reasoning
* Developed sincerity evaluation pipeline
* Built FastAPI backend and mobile application structure
* Planned blockchain-enabled trust management architecture

## Future Work

* Multi-modal emotion analysis
* Voice emotion recognition
* Relationship analytics dashboard
* Blockchain trust ledger
* Tokenized incentive system

## License

MIT License
