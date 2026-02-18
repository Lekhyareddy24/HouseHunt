HouseHunt: Finding Your Perfect Rental Home

HouseHunt is a full-stack web application that helps users easily search, compare, and discover rental homes based on their preferences. The platform provides a smooth, user-friendly experience for browsing properties, filtering results, and managing listings in real time.

This project is designed with a modern MERN-style architecture and focuses on performance, usability, and responsive design.

🚀 Features

✅ User registration and login
✅ Browse rental properties with images and details
✅ Advanced search and filtering (price, location, type, amenities)
✅ Property listing management
✅ Responsive UI with modern design
✅ Real-time data handling
✅ Secure backend API
✅ Date and time handling using Moment.js

🛠️ Tech Stack
Frontend

React.js

Ant Design (Antd UI Components)

HTML5

CSS3

JavaScript

Backend

Node.js

Express.js

Database

MongoDB

Utilities

Moment.js

📁 Project Structure
HouseHunt/
│
├── client/                # React frontend
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
│
├── server/                # Node + Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── package.json
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/househunt.git
cd househunt

2️⃣ Install backend dependencies
cd server
npm install

3️⃣ Install frontend dependencies
cd ../client
npm install

4️⃣ Configure environment variables

Create a .env file inside the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string

5️⃣ Run the application

Start backend:

cd server
npm start


Start frontend:

cd client
npm start


The app will run at:

http://localhost:3000

🎯 Project Objectives

Simplify the rental home search process

Provide accurate and filtered property results

Deliver a clean and intuitive user interface

Enable efficient property management

Build a scalable full-stack web platform

🔮 Future Enhancements

⭐ Map-based property search
⭐ Recommendation system for users
⭐ Chat between owner and tenant
⭐ Image upload for listings
⭐ Payment integration
⭐ Mobile app version
