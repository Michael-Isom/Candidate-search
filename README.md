# Candidate-search

Description

The Candidate Search Application is a web application designed to streamline the hiring process by enabling recruiters and hiring managers to search, filter, and manage candidate profiles efficiently. This app provides an easy-to-use interface where users can view candidate details, filter candidates based on skills, experience, and location, and save profiles for future reference.

Features

	•	Search and Filter Candidates: Quickly find candidates by name, location, skills, and experience level.
	•	View Candidate Profiles: Access detailed information on each candidate, including contact info, professional summary, and work history.
	•	Responsive Design: The application is fully responsive, allowing smooth usage on desktops, tablets, and mobile devices.
	•	Bookmarking: Save candidate profiles to a shortlist for easy access later.
	•	User Authentication: Secure access for authorized users, ensuring data privacy.

Technologies Used

	•	Frontend: React, React Router
	•	Backend: Node.js, Express.js, GraphQL
	•	Database: MongoDB, Mongoose ODM
	•	Authentication: JSON Web Tokens (JWT)
	•	Styling: CSS, possibly Material UI or Bootstrap for UI components
	•	Deployment: Render
	•	Automation and CI/CD: GitHub Actions for continuous integration

Installation and Setup

Prerequisites

	•	Node.js and npm installed
	•	MongoDB Atlas or local MongoDB instance for data storage
	•	Render account for deployment (optional)

 git clone https://github.com/yourusername/candidate-search-app.git
cd candidate-search-app

npm install 

	Set up environment variables:
	•	Create a .env file in the root directory.
	•	Add necessary environment variables for database connection, JWT secret, and any API keys if required.

 MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret

npm start
