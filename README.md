# AthleticPerformancePlatform
# Athletic Performance Platform

## Overview
This platform helps athletes enhance their performance through AI-driven insights, interactive dashboards, and robust backend services.

## Directory Structure
- `backend/`: Handles API and database logic.
- `frontend/`: React.js-based user interface.
- `ai/`: AI models and predictions.

## Features
- PostgreSQL database for athlete and training data.
- Django REST APIs for workshops, skill tracking, and feedback.
- React.js frontend with interactive dashboards.
- TensorFlow-based AI models for performance prediction.

## Setup Instructions
1. **Backend**:
    - Navigate to the `backend` directory:
      ```bash
      cd backend
      pip install -r requirements.txt
      python manage.py runserver
      ```

2. **Frontend**:
    - Navigate to the `frontend` directory:
      ```bash
      cd frontend
      npm install
      npm start
      ```

3. **AI**:
    - Train the AI model:
      ```bash
      cd ai
      python train.py
      ```

4. **Integrate and Test**:
    - Access the platform at `http://localhost:3000`.
