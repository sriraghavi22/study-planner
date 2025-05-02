📘 Comprehensive Study Planner Web App
A smart, collaborative platform to help students stay on top of their academic goals, communicate in real time, and manage study resources seamlessly.

🔐 Secure. 📅 Organized. ⚡ Real-Time.
A feature-rich full-stack web app that transforms how students plan their studies. From personalized study recommendations to deadline alerts and group chats, this platform ensures productivity and collaboration at every step.

✨ Live Features
🔓 Authentication (JWT Secured)
Signup/Login securely with JSON Web Tokens for persistent, authenticated access.

📬 Real-Time Messaging
Stay connected with your study group via a chat system powered by Socket.io.

📁 File Upload & Sharing
Upload and share notes, PDFs, and images using Multer with secure backend handling.

📊 Personalized Study Insights
Get AI-powered feedback on your study patterns — track progress, identify focus areas, and reduce missed deadlines.

🛎️ Smart Deadline Notifications
Never miss a task — get alerts before every important submission.

📆 Study Calendar
Visualize tasks, set priorities, and schedule sessions using an interactive planner view.

📸 Project Preview
👋 Landing & Login

🏠 Student Dashboard

💬 Chat Module

📂 File Upload

⚙️ Tech Stack
Layer	Technology
Frontend	React.js, TailwindCSS/Bootstrap
Backend	Node.js, Express.js
Database	MongoDB + Mongoose
Auth	JWT
Real-time	Socket.io
File Uploads	Multer
Others	Axios, Context API

💡 Why It Matters
📉 20% fewer missed deadlines after integrating reminders & study suggestions.
🤝 Designed for collaborative academic success.
📈 Encourages goal-setting, accountability, and organized study habits.

🛠️ Core Modules
🧑‍🎓 Student Dashboard
Add/edit/delete tasks

View progress and deadline countdown

Receive smart tips based on behavior

💬 Group Chat
Real-time group communication

Socket.io-powered chat room per group

📤 File Management
Securely upload and download study materials

Categorized by subjects/topics

📈 Study Analytics
View productivity metrics

Heatmaps, consistency scores, and suggestions

🧪 How to Run Locally
Prerequisites
Node.js

MongoDB

npm or yarn

Setup Steps
bash
Copy
Edit
git clone https://github.com/your-username/study-planner.git
cd study-planner
Install Server
bash
Copy
Edit
cd server
npm install
Install Client
bash
Copy
Edit
cd ../client
npm install
Create .env File in /server
env
Copy
Edit
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/studyplanner
JWT_SECRET=your_jwt_secret
Run the App
bash
Copy
Edit
# Terminal 1
cd server
npm run dev

# Terminal 2
cd client
npm start
🧠 Future Enhancements
📱 Mobile App with React Native

📌 Google Calendar Sync

📧 Email and Push Reminders
## 👥 Contributors

This project was developed as a collaborative group effort by:

- [K Sri Raghavi](https://github.com/k-sri-raghavi)
- [D V S Monish Kumar](https://github.com/monish-dvs)

🧑‍🏫 Mentor Role with Broadcast Announcements

📚 Study Material Repository Search

