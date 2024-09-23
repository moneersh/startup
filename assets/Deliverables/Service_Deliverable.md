# Service Deliverable

## Overview
For this deliverable, backend endpoints were developed to manage user exercises and progress tracking, utilizing Node.js and Express.

## Key Components
- **Node.js/Express Service**: Established a server using Node.js and Express to handle requests and serve data.
- **Static Middleware**: Configured middleware to serve static React assets, connecting the backend with the frontend.
- **Third-Party Integrations**: Set up calls to Google Maps API and OpenAI API for real-world language practice scenarios.
- **Backend Endpoints**: Created functional endpoints for:
  - `login`: Handles user authentication and session management.
  - `retrieveExercises`: Fetches personalized language exercises.
  - `submitProgress`: Submits user progress data for tracking and feedback.
- **Frontend Integration**: Utilized `fetch` for asynchronous calls to backend endpoints, ensuring seamless data flow.

## Process
1. **Server Setup**: Initialized an Express server to manage HTTP requests.
2. **Endpoint Development**: Created endpoints for key functionalities, handling CRUD operations for exercises and progress.
3. **Middleware Configuration**: Added middleware to serve React frontend and handle JSON requests.
4. **API Integration**: Integrated external APIs to enhance language learning with real-world scenarios.
