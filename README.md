 # 🎯 FitFusion

**FitFusion** is a modern, dynamic fitness tracking web app that allows users to monitor their progress, set goals, and connect with friends. With dark and light modes, smooth animations, and real-time email notifications, FitFusion brings your fitness journey to life.

![FitFusion Banner](https://github.com/user-attachments/assets/1fd0e5ff-a22f-4fa5-ae91-594d7c3d297a)  
-- 

---

## 📂 Project Structure

FitFusion is structured into two main directories for a well-organized codebase: `client` for the frontend and `server` for the backend.

<details>
<summary><strong>📁 Folder Overview (Click to Expand)</strong></summary>

```plaintext
FitFusion/
├── client/                     # Frontend code
│   ├── public/                 # Static public files
│   ├── src/                    # React app source code
│   │   ├── components/         # Reusable components (e.g., Dashboard, Activity)
│   │   ├── pages/              # Main pages (e.g., Home, Goal, Challenge)
│   │   └── utils/              # Utility functions and helpers
│   └── .env                    # Frontend environment variables
└── server/                     # Backend code
    ├── config/                 # Database config
    ├── controllers/            # API controllers
    ├── models/                 # Mongoose models
    ├── routes/                 # API routes
    ├── middleware/             # Authentication and other middlewares
    └── .env                    # Backend environment variables
```
</details>
🚀 Features
🌞 Dark & Light Mode
Enjoy a seamless switch between dark and light modes, optimized for both readability and style. FitFusion remembers your preference, offering a consistent experience.

Light Mode	Dark Mode
📊 Personalized Dashboard
Get an interactive and visually appealing overview of your daily, weekly, and monthly fitness stats.


🧑‍🤝‍🧑 Social Connectivity
Engage with friends, share achievements, and cheer each other on for more motivation.

🎨 Tech Stack
Frontend
React: Component-based user interface.
Tailwind CSS: Utility-first styling.
Framer Motion: Fluid animations.
EmailJS: Real-time email notifications.
Backend
Node.js & Express: Backend server and routing.
MongoDB & Mongoose: Database to store user data.
JWT: Secure authentication.
Nodemailer: (Optional) For backend email notifications
🛠️ Getting Started
Follow these steps to set up the project locally.

Prerequisites
Make sure you have Node.js installed on your machine.

Installation
Clone the Repository:
```
git clone https://github.com/your-username/FitFusion.git
cd FitFusion
```
Install Dependencies for Client and Server:
```
cd client
npm install
cd ../server
npm install
```
Setup Environment Variables:

Create a .env file in both client and server directories with necessary variables


Run the Application:
```
cd client
npm startcd ../server
```


🌈 Dark and Light Mode
FitFusion is optimized for both dark and light modes, allowing users to seamlessly switch based on their preference.



📱 Responsive Design
Using Tailwind CSS and custom styling, the app is fully responsive, ensuring a consistent experience across devices.



📧 Email Notifications
Real-time notifications using EmailJS for contact form submissions, enhancing user interaction and communication.



📋 API Endpoints
The backend provides RESTful APIs for managing users, activities, and goals. Here’s a quick overview:



User Routes:
```
POST /api/users/register: Register a new user.
POST /api/users/login: User login.
GET /api/users/profile: Fetch user profile.
Activity Routes:

POST /api/activities: Add a new activity.
GET /api/activities: Retrieve user activities.
Goal Routes:

POST /api/goals: Set a new fitness goal.
GET /api/goals: View user goals.
```

 
👥 Contributing
We welcome contributions! Please follow these steps:

Fork the project.
Create a new branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add new feature'.
Push to the branch: git push origin feature-name.
Create a Pull Request for review.


📜 License
This project is licensed under the MIT License. See LICENSE for more information.


❤️ Acknowledgments
React: Frontend library.
Framer Motion: For smooth animations.
Tailwind CSS: CSS framework for styling.
EmailJS: For email integration.
MongoDB: Database solution for user data.
npm start

📸 Screenshots & Animations
![Screenshot (666)](https://github.com/user-attachments/assets/70a47fe3-c955-459f-94ab-e0402b64ef30)
![Screenshot (667)](https://github.com/user-attachments/assets/e897b604-6399-450e-8f97-8e0f7942d6b4)
![Screenshot (668)](https://github.com/user-attachments/assets/8c46ed97-7f39-4c60-ad3f-cd0c4baea1d3)
![Screenshot (669)](https://github.com/user-attachments/assets/97ae6345-6d80-45c0-8a37-df82cd2ec3ec)
![Screenshot (670)](https://github.com/user-attachments/assets/cafe85b6-9d81-4bc8-9c74-d1caba28a0ec)
![Screenshot (671)](https://github.com/user-attachments/assets/67576eb2-4fc3-4fbc-ae77-b22645c822ca)
![Screenshot (676)](https://github.com/user-attachments/assets/8a6fa9d5-d2e2-43fa-a950-a89e5d2a1cc7)
![Screenshot (678)](https://github.com/user-attachments/assets/ce2e9952-d827-4221-9110-0ab25dbb0fc4)
![Screenshot (680)](https://github.com/user-attachments/assets/f534e4f0-95dd-4a3f-a0cd-ffef1bc4d605)
![Screenshot (681)](https://github.com/user-attachments/assets/82bfcdb2-eac2-4be1-bbf3-32112c1a58ae)
![Screenshot (682)](https://github.com/user-attachments/assets/78264241-554d-40c1-b81d-097228c3f7a0)
![Screenshot (683)](https://github.com/user-attachments/assets/86d28af7-ba93-49ac-a584-857ebaeb8a9b)
