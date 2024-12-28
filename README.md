# Mentorship Matching Platform

## Overview
The **Mentorship Matching Platform** allows users to connect with mentors or mentees based on shared skills and interests. Users can create accounts, set up profiles, and discover potential mentorship opportunities. The platform is designed with simplicity and usability in mind, using vanilla JavaScript, HTML, and CSS.

## Features
### User Interface
- **User Registration and Login**: Secure user authentication with form validation.
- **Profile Setup**: Create and update profiles with details like role (mentor/mentee), skills, interests, and bio.
- **User Discovery**: Browse and filter profiles to find mentorship matches.

### Functionalities
- **User Authentication**: Secure signup, login, and logout.
- **Profile Management**: Add, edit, or delete profiles seamlessly.
- **Connection Requests**: Send, accept, or decline mentorship requests, and manage ongoing connections.

### Database Integration
- **Database Setup**: Relational database (e.g., PostgreSQL) for storing user data, profiles, and connections.
- **Data Security**: Secure handling of sensitive information, preventing vulnerabilities like SQL injection.
- **Relationships**: Proper mapping between users, profiles, and mentorship requests.

### Deployment
- Hosted on [Heroku](https://heroku.com) (or a similar free platform).
- Environment variables managed securely.

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/mentorship-matching-platform.git
   cd mentorship-matching-platform
   ```

2. **Install Dependencies**:
   Set up the database and configure environment variables as needed.

3. **Run the Application**:
   Open `index.html` in a browser for the frontend. Set up a local server for backend/database interaction.

4. **Database Setup**:
   - Use the provided SQL script (`database/schema.sql`) to initialize the database.
   - Update the database connection details in the backend configuration.

5. **Deployment**:
   - Deploy the frontend on platforms like Vercel or Netlify.
   - Deploy the backend and database on platforms like Heroku.

## Technologies Used
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Node.js with Express.js (optional)
- **Database**: PostgreSQL (or MySQL)
- **Deployment**: Heroku, Netlify

## Challenges and Solutions
### Challenges
1. **Implementing Responsive UI**:
   Ensured compatibility across devices with a mobile-first design approach.
2. **Secure User Authentication**:
   Implemented strong password hashing and form validation.
3. **Database Relationships**:
   Designed normalized tables to manage user profiles and mentorship connections efficiently.

### Solutions
- Used matrix layouts and CSS grid for responsive design.
- Incorporated bcrypt for password security.
- Designed robust SQL queries for efficient data retrieval and manipulation.

## Deployed Application
- **Live URL**: [Mentorship Matching Platform](https://stackblitz.com/~/github.com/FingNaresh/sb1-cqvfbbkc)

## Repository
- **GitHub Repository**: [Mentorship Matching Platform Repo](https://github.com/your-username/mentorship-matching-platform)

## Contribution
Feel free to fork this repository, create new branches, and submit pull requests with improvements. For inquiries or feedback, contact me at [fingNaresh2911@gmail.com](mailto:fingNaresh2911@gmail.com).

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
Thank you for using the Mentorship Matching Platform! If you have any feedback or suggestions, please reach out via the contact information in the deployed application.
