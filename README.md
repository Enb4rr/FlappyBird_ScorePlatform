# Flappy Bird - Game Portal + Telemetry System

---

### Made by Julian Rosero
### Last Updated 4/28/2026

---

A web-based game portal for Flappy Bird built with React, Firebase Authentication, and Firestore (This is a purely educational project).

## Features

- Email/password and Google authentication
- Role-based access (Player and Admin)
- User profile screen with stats
- Live leaderboard pulling from Firestore
- Admin dashboard with user management and role toggling
- Username edition
- Telemetry System in Admin's dashboard

---

## Setup

### 1. Clone the repository

Clone: https://github.com/Enb4rr/FlappyBird_ScorePlatform

### 2. Install dependencies

npm install

### 3. Create a `.env` file

Create a `.env` file in the root of the project with the following Firebase credentials:

VITE_FIREBASE_API_KEY=AIzaSyAc4jxOn7Dh6fVb0XGYDWTdWFXd0iLKKD4
VITE_FIREBASE_AUTH_DOMAIN=cloudcomputing-670d8.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=cloudcomputing-670d8
VITE_FIREBASE_STORAGE_BUCKET=cloudcomputing-670d8.firebasestorage.app
VITE_FIREBASE_MESSAGING_SENDER_ID=355101850896
VITE_FIREBASE_APP_ID=1:355101850896:web:f26506617f3bf4c7273995

VITE_GAME_URL=https://enb4rr.github.io/Pipelines_SponderBird/

### 4. Run the development server

npm run dev

---

## Test Accounts

| Role   | Email | Password       |
|--------|-------|----------------|
| Player | raf@ramenday.com | concussion1234 |
| Admin  | spencer@bettleball.com  | gonk1234 |

---

## Seeding Mock Data

To push mock users and scores to Firestore (you don't need to do this step for testing):

node scripts/ingestScores.js

To clear mock data:

node scripts/ingestScores.js --clear

---
