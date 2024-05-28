**Skin Disease Diagnosis Project**


**Overview**


_This project is a web-based application designed for diagnosing skin diseases. The application leverages Angular for the frontend and Flask for the backend. The diagnostic model is built using fuzzy logic to provide accurate and reliable results. The backend is deployed using Render, and Firebase is utilized for the frontend, including Firebase Authentication for secure user management._

**Features**

Skin Disease Diagnosis: Users can input symptoms to get a diagnosis based on a fuzzy logic model.

User Authentication: Secure login and registration using Firebase Authentication.

Frontend: Built with Angular for a responsive and dynamic user experience.

Backend: Developed with Flask, providing robust and scalable server-side logic.

Deployment: Backend deployed on Render for reliable and scalable hosting.






->**Technology Stack**


**Frontend:**

Angular

Firebase (Hosting and Authentication)


**Backend:**

Flask

Fuzzy Logic Model


**Deployment:**

Render (Backend)

Firebase Hosting (Frontend)



->****Installation****

**Prerequisites**
Node.js and npm installed
Python and pip installed
Firebase CLI installed
Backend (Flask)
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/skindisease-diagnosis.git
cd skindisease-diagnosis/backend
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Flask server:

bash
Copy code
flask run
Frontend (Angular)
Navigate to the frontend directory:

bash
Copy code
cd ../frontend
Install the required dependencies:

bash
Copy code
npm install
Serve the Angular application:

bash
Copy code
ng serve
Firebase Authentication
Set up Firebase Authentication by creating a Firebase project and enabling Authentication.

Add your Firebase configuration to the Angular environment files.

Usage
Open your browser and navigate to http://localhost:4200 to access the frontend.
Register or log in using Firebase Authentication.
Input your symptoms to receive a skin disease diagnosis based on the fuzzy logic model.
Deployment
Backend (Render)
Create a new web service on Render and connect it to your GitHub repository.
Follow Render's instructions to deploy your Flask application.
Frontend (Firebase Hosting)
Build the Angular project:

bash
Copy code
ng build --prod
Deploy to Firebase Hosting:

bash
Copy code
firebase deploy
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License.

Contact
For any inquiries or issues, please contact thakerparth12@gmail.com.
