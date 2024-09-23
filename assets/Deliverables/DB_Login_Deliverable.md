# DB/Login Deliverable

## Overview
This deliverable focused on associating user progress with their login information, using MongoDB Atlas to store data securely.

## Key Components
- **MongoDB Atlas**: Set up a MongoDB Atlas database to manage user profiles, progress data, and credentials.
- **Data Storage**: Stored user data including profiles, progress, and login credentials securely.
- **User Registration**: Implemented functionality allowing new users to register and create accounts.
- **Existing User Handling**: Matched progress data with returning users based on stored credentials.
- **Secure Authentication**: Utilized MongoDB to store credentials securely, ensuring user authentication.
- **Access Restrictions**: Restricted access to learning content unless the user is logged in, enforced at both frontend and backend levels.

## Process
1. **Database Setup**: Configured MongoDB Atlas and connected it to the application.
2. **User Authentication**: Developed registration and login functionalities with password hashing and secure storage.
3. **Data Management**: Implemented CRUD operations for managing user progress and profiles.
4. **Access Control**: Enforced access restrictions, ensuring only authenticated users can access learning content.
