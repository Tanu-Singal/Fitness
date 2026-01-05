# Smart Fitness App

A smart fitness application that generates personalized workout plans based on user data and predicts calories burned for exercises using Machine Learning models.

The application integrates multiple APIs and ML components to deliver data-driven fitness recommendations.

---
## Tech Stack
- Node.js
- Express.js
- MongoDB
- Machine Learning (Python, scikit-learn)
- Gemini API (personalized workout generation)
- Rapid API (exercise search)
- REST APIs

---
## Features
- Personalized workout plan generation using user data
- Integration with Gemini API for intelligent workout recommendations
- Calorie burn prediction for exercises using an ML model
- Query-based exercise search via Rapid API
- User profile management
- Backend-driven architecture with clean APIs

---
## System Architecture
- User data is collected and stored securely
- Gemini API generates personalized workout plans
- ML model predicts calories burned per exercise
- Rapid API is used for dynamic exercise search
- All components are connected through RESTful APIs

---
---

## Setup Instructions
1. Clone the repository
git clone https://github.com/Tanu-Singal/Fitness.git

2. Install backend dependencies
npm install

3. Set up environment variables in `.env`
MONGO_URI=your_mongodb_url
GEMINI_API_KEY=your_gemini_api_key
RAPID_API_KEY=your_rapid_api_key

4. Start the backend server

---

## ML Model Overview
- Input features: exercise type, duration, user weight, intensity
- Output: estimated calories burned
- Model trained using supervised learning techniques
- Model integrated with backend via API endpoints

---

## API Endpoints
- POST `/api/exercises`
- POST `/api/calorie/user/:id`
- POST `/getworkout/:id`
- GET `/api/exercises/bodyPart/:bodyPart`
- POST `/api/chat`

---

## Security Considerations
- Secure handling of API keys using environment variables
- Protected user routes

---

## ML Integration (Highlights)
- ML model used for real-time calorie prediction
- AI-powered workout plan generation using Gemini API
- Scalable design for adding future ML models

---

## Future Improvements
- Model retraining using real user activity data
- Nutrition recommendation system
- Progress tracking and analytics dashboard
- Wearable device integration

---

## Disclaimer
This project is for educational purposes only and should not be considered professional fitness or medical advice.
