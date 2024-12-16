# Combined_Assignment
1. Create a README.md file if it doesn't exist already.
bash
Copy code
touch README.md
2. Open README.md and add the following content to provide installation instructions:
markdown
Copy code
# Project Title

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sourav7274/Combined_Assignment.git
   cd Combined_Assignment
Initialize submodules:


git submodule update --init --recursive
Install required dependencies for backend and frontend:


cd assignment_backend
cd assignment_backend  # Navigate to the backend directory
npm install cors dotenv express mongoose



cd assignmentfrontend  # Navigate to the frontend directory
npm install bootstrap@5.3.3 cra-template jspdf@2.5.2 react@19.0.0 react-dom@19.0.0 react-router-dom@7.0.2 react-scripts@5.0.1 react-to-pdf@1.0.1



Run the application:

Backend -> node index.js
Frontend -> npm start
