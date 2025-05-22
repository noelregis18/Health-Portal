# Med First Health Portal

A comprehensive web application for healthcare management that connects patients and doctors through a digital platform. This system allows patients to register, manage their health information, and connect with doctors, while enabling doctors to manage their accounts and access patient information.

## Features

### For Patients
- Account registration and login
- Personal health information management
- View doctor information
- Update personal details
- Delete account functionality

### For Doctors
- Professional account registration and login
- Patient information access
- Account management
- Professional profile management (department, post, qualifications)
- Delete account functionality

## Technology Stack

- **Frontend**: HTML, CSS, Bootstrap 4
- **Backend**: Node.js, Express.js
- **Template Engine**: Handlebars (HBS)
- **Database**: MySQL
- **Authentication**: Session-based authentication

## Project Structure

```
HealthPortal/
├── database/             # Database files
├── routes/
│   ├── doctor.js        # Doctor-related routes and logic
│   └── patient.js       # Patient-related routes and logic
├── views/
│   ├── doctor.hbs       # Doctor dashboard template
│   ├── doctors.html     # Doctor registration/login page
│   ├── mainpage.html    # Application landing page
│   ├── patient.hbs      # Patient dashboard template
│   └── patients.html    # Patient registration/login page
├── server.js            # Main application entry point
└── package.json         # Project dependencies
```

## Setup Instructions

### Prerequisites

- Node.js (v10 or higher)
- MySQL Server

### Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/HealthPortal.git
   cd HealthPortal
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Configure the database
   - Create a MySQL database named `healthcare`
   - Update the database connection settings in `server.js` and route files with your credentials

4. Start the application
   ```
   npm start
   ```

5. Access the application
   - Open your browser and navigate to `http://localhost:8080`

## Usage

### For Patients
1. Navigate to the Patients section from the main page
2. Register with your personal details
3. Login with your assigned User ID and password
4. Manage your health information and view doctor details

### For Doctors
1. Navigate to the Doctors section from the main page
2. Register with your professional details
3. Login with your assigned User ID and password
4. Access patient information and manage your account

## License

ISC License

## Contributors

- Original repository: https://github.com/ashkush21/DBMS-project