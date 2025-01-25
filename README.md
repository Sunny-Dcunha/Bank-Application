Bank Application Frontend
This project is a React-based frontend for the Bank Application, developed using Material-UI (MUI) templates. The templates have been manually updated to customize the design and functionality. The frontend is fully integrated with the Spring Boot backend.

Features
Sign In / Sign Up: User authentication to access the application.
Account Management: Create account.
Money Transfer: Transfer funds between accounts.
Transaction History: View a detailed statement of account activities.
Responsive Design: Built with MUI for seamless performance across devices.
Prerequisites
Make sure the following are installed on your system:

Node.js (v16 or later recommended)
npm (comes with Node.js)
A running instance of the backend application on http://localhost:8080.
Getting Started
1. Clone the Repository
git clone <repository-url>
cd <project-directory>

2. Install Dependencies
Run the following command to install all required packages:
npm install
3. Start the Application
To launch the application on http://localhost:3000, run:
npm start

4. Access the Application
Open your browser and navigate to:
http://localhost:3000

Backend Integration
This React application is integrated with a Spring Boot backend running on:
http://localhost:8080
Ensure the backend is running before using the application to access all features.

Project Structure
bash
Copy
Edit
src/
├── components/       # Reusable React components
├── pages/            # Application pages (e.g., Login, Dashboard)
├── services/         # API calls and backend integration
├── styles/           # Custom styles
└── App.js            # Main application entry point

Key Dependencies

React: Frontend framework

MUI (Material-UI): UI library

Axios: HTTP client for API integration

React Router: Routing and navigation

Customization
You can modify the project as per your requirements by editing the following:

API Integration: Update endpoints or API logic in src/services/.

Troubleshooting
If npm start fails, ensure no other application is using port 3000.
If API calls fail, verify the backend is running on http://localhost:8080.


