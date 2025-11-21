📌 Hostel-Track – MERN-Based Hostel Attendance Management System
🔍 Overview

Hostel-Track is a MERN-based web application designed to automate hostel attendance records and real-time student tracking.
It provides administrators with a secure dashboard to log attendance, track student presence, and generate reports efficiently.

🛠 Tech Stack
Layer	Technology
Frontend	React.js
Backend	Node.js, Express.js
Database	MongoDB
Authentication	JWT
Other	CSV Export, RESTful APIs, Git

📌 Note: All project source code is available in the master branch (not main).

🚀 Features

✔ Secure admin login using JWT
✔ Student registration & real-time tracking
✔ Daily attendance recording
✔ CSV export functionality
✔ REST API-based architecture
✔ Responsive React dashboard

🔗 Branch Information

The default GitHub branch may show main, but the actual project source code is maintained in the master branch.

Clone using:

git clone -b master https://github.com/yourusername/hostel-track.git
cd hostel-track

📂 Folder Structure
hostel-track/
├── backend/
│   ├── server.js
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── config/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md

⚙️ Setup Instructions
1️⃣ Clone repository
git clone -b master https://github.com/yourusername/hostel-track.git
cd hostel-track

2️⃣ Install backend dependencies
cd backend
npm install

3️⃣ Install frontend dependencies
cd ../frontend
npm install

4️⃣ Configure environment variables (.env)
MONGODB_URI=mongodb+srv://your-db-url
JWT_SECRET=your-secret-key
PORT=5000

5️⃣ Run backend
cd backend
npm run start

6️⃣ Run frontend
cd ../frontend
npm start


App runs at:
➡ Frontend: http://localhost:3000
➡ Backend: http://localhost:5000

📊 Sample CSV Export
Date,Student Name,Roll No,Status
13-11-2025,Harsh Kumar,CS202104,Present
13-11-2025,Rohan Sharma,CS202122,Absent

🔒 Security Features

JWT-based authentication

API validation using middleware

Password hashing using bcrypt.js

Protected admin routes

🎯 Future Enhancements

Biometric-based attendance

Mobile app integration

Email/SMS notification to parents

Support for multiple hostels

👨‍💻 Developed By

Harsh Kumar
Junior Backend Developer | MERN Stack | API Specialist
📧 sinhaharsh029@gmail.com

🌟 Contribution & Feedback

Pull requests are welcome. For collaboration or suggestions, feel free to reach out.

⭐ Tip: Pin this repository and mention “MERN Stack | Attendance Management System” in repo description.
