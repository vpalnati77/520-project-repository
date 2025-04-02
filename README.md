# Wellness App

## Overview
The **Wellness Platform** helps users manage health and wellness through features like user registration, profile management, health tracking, telehealth consultations, AI recommendations, and more.

## Key Features

### 1. User Authentication
- Secure sign-up, login, and password reset.
- Account temporarily locked after multiple failed login attempts.

### 2. Profile Management
- Users and wellness coaches can update health and professional details.
- Supports file uploads for patient medical records (restricted to specific formats).

### 3. Health Data Tracking
- Track and monitor health parameters like heart rate, activity levels, and sleep cycles.
- System prompts verification for unrealistic data entries (e.g., heart rate of 500 bpm).

### 4. EWR Access & Management
- Users can view their own wellness records, while wellness coaches can update them.
- Access to records is restricted to privacy standards.

### 5. Search & Filtering
- Quick search for patient history, medications, and diagnoses.

### 6. AI Recommendations
- Personalized wellness suggestions based on user data.
- Alerts if suggestions conflict with critical health conditions.

### 7. Telehealth Consultations
- Users can book and attend virtual consultations.
- Internet issues during consultations will prompt reconnection or rescheduling.

### 8. Secure Messaging
- Encrypted messaging for communication and session reminders.

### 9. Meal & Nutrition Planning
- Users manage meal plans, with professionals providing dietary adjustments.
- Alerts for allergenic content in meal recommendations.

### 10. Calm Studio
- Guided relaxation activities, including breathing exercises and mindfulness coaching.
- Alternative sessions offered if a session fails to load.

## Technologies
- **Backend**: Java, Spring Boot, PostgreSQL
- **Frontend**: React, Node.js
- **Authentication**: JWT
- **Database**: PostgreSQL
- **AI**: AI-powered wellness recommendations
- **Encryption**: AES

## Setup

### Prerequisites
- Install Node.js and Java (Spring Boot).
- Set up PostgreSQL for the database.

### Installation
1. Clone the repository.
2. Run `npm install` to install frontend dependencies.
3. Set up the backend using Spring Boot and connect it to the PostgreSQL database.
4. Configure JWT for secure authentication.

### Run the Application
- Frontend: `npm start`
- Backend: Run the Spring Boot application.