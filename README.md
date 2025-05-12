# ElderHub - Health Charity Web Application 🏥

## Project Overview
ElderHub is a modern web application designed for a health charity focused on supporting elderly populations. 
This project aims to enhance the well-being of elderly communities through accessible information, event management, and community engagement.
The platform allows users to view resources, participate in events, and access health-related content.
Administrators have access to a dedicated dashboard for managing users and content.

### Client Overview
The client is a renowned health charity focused on improving the health and well-being of elderly populations.
The organization leverages technology to expand its reach, enhance its services, and streamline operations to better serve its target audience.

---

## Features 🚀

### Core Features
- **Responsive Design:** Fully compatible with desktop, tablet, and mobile devices (Bootstrap 5).  
- **User Authentication:** Supports registration and login using Firebase Authentication.  
- **Role-Based Access:** Distinguishes between regular users and administrators.  
- **Event Management:** Users can view, join, and rate events. Administrators can create and manage events.  
- **Dynamic Data:** Real-time updates using Firestore as the database.  
- **Interactive UI:** Includes dashboards for both users and administrators.  
- **Accessibility:** Complies with WCAG 2.1 AA standards for improved usability.  
- **Deployment:** Hosted on Firebase with cloud functions and serverless architecture.  
- **External Authentication:** Uses Firebase Auth for secure login.  
- **Rating System:** Allows users to rate events and view average scores.  
- **Email Notifications:** Uses SendGrid API for email communication.  
- **Cloud Functions:** Utilizes Firebase Cloud Functions for serverless operations.  
- **Geo Location Features:** Integrates map functions using MapBox for event locations.  

---

## Technologies Used 💻
- **Frontend:**  
  - Vue.js 3 (with Vite)  
  - Bootstrap 5  
  - Pinia (state management)  
  - Firebase Authentication  
  - Firestore (real-time database)  
  - MapBox (geolocation features)  
  - SendGrid API (email notifications)  

- **Backend:**  
  - Firebase Cloud Functions  
  - Node.js  

- **Hosting:**  
  - Firebase Hosting  

- **Development Tools:**  
  - Vite (development server)  
  - ESLint & Prettier (code quality and formatting)  
  - GitHub (version control)  

---

## Project Structure 📂
```
ElderHub/
├── public/                  # Static assets (favicon, index.html)
├── src/                     # Vue components and application logic
│   ├── assets/              # Images and styles
│   ├── components/          # Reusable UI components
│   ├── views/               # Page components
│   ├── router/              # Vue Router configurations
│   ├── stores/              # State management (Pinia)
│   └── firebase/            # Firebase configuration
├── functions/               # Cloud functions (Node.js)
├── .vscode/                 # VSCode settings
├── .gitignore               # Git ignore file
├── package.json             # Project metadata and dependencies
├── firebase.json            # Firebase hosting and function config
├── README.md                # Project documentation
└── vite.config.js           # Vite configuration
```

---

## Installation and Setup ⚙️

### Prerequisites
- Node.js (v16.x or higher)  
- Firebase CLI  
- Vite  
- A Firebase project with Firestore and Authentication enabled  

### Step 1: Clone the Repository
```bash
git clone https://github.com/GaryDou/ElderHub.git
cd ElderHub
```

### Step 2: Install Dependencies
```bash
npm install
cd functions
npm install
cd ..
```

### Step 3: Firebase Configuration
1. Set up a Firebase project and update the configuration in `src/firebase/init.js`.  
2. Update `firebase.json` and `.firebaserc` with your Firebase project details.  

### Step 4: Run the Project Locally
```bash
npm run dev
```

### Step 5: Deploy to Firebase
```bash
firebase deploy
```

---

## Usage Instructions 📋

### User Access
- **Register an account:** Navigate to the Register page and fill out the form.  
- **Log in:** Use your credentials to log into the system.  
- **View Events:** Browse available events and join.  
- **Rate Events:** Leave a rating and see the aggregated score.  

### Admin Access
- **Create Events:** Use the dashboard to create new community events.  
- **Manage Users:** View and manage registered users.  
- **View Feedback:** Access ratings and event performance.  

---

## Testing 🧪

### Unit Tests
To run unit tests:
```bash
npm run test
```

### Deployment Testing
After deploying to Firebase, access the hosted site to test functionalities:  
```
xxx
```

---

## Contribution Guidelines 🤝
This project is primarily for educational purposes and is not open to public contributions.  
For feedback or suggestions, please contact the project owner.  

---

## License 📜
Paw Patrol for Penguins © 2025 by Zhenyao Dou is licensed under CC BY-NC-ND 4.0.  
For more information, visit the [Creative Commons License page](https://creativecommons.org/licenses/by-nc-nd/4.0/).

---

## Contact 📧
If you have any questions or feedback, feel free to reach out to me through GitHub or via email at [zdou2598@gmail.com].
