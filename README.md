Job Hunt Site Project
This project is a simple job hunting site that includes a signup, login page, and a basic assessment test. It is implemented using pure HTML, CSS, and JavaScript, and it stores user data locally using localStorage.

Features
Signup: Users can create an account by entering a username and password.
Login: Users can log in with the same credentials used during signup.
Assessment Test: After logging in, users are directed to an assessment test page, where they answer a few questions.
How It Works
User credentials are stored locally in the browser's localStorage.
No real backend or server is required; all functionality happens in real-time within the browser.
User data, including assessment answers, is stored temporarily until the page is refreshed or closed.
Technologies Used
HTML: Structure and layout of the web pages.
CSS: Styling for the login, signup, and assessment pages.
JavaScript: Handles user signup, login, form validation, and storing data in localStorage.
How to Run the Project
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/job-hunt-site.git
cd job-hunt-site
Open the project:

Open index.html in your preferred web browser to start the site.

Use the Signup/Login functionality:

Go to index.html to either signup for a new account or login with an existing one.
After a successful login, you will be redirected to the assessment.html page where you can take the test.
Submit the assessment:

After filling out the assessment test, your answers will be stored locally, and you will receive a success message.

Project Structure
bash
Copy code
job-hunt-site/
├── README.md               # Project documentation
├── index.html              # Signup and login page
├── assessment.html         # Assessment test page
└── styles.css              # Common styles (optional if separated)
Future Improvements
Add grading logic for the assessment test.
Implement a real backend to store user data securely.
Enhance the UI with additional CSS styling.
License
This project is open-source and available under the Rohit Luitel.

