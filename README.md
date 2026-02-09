💰 FinMate – Smart Student Expense Tracker

FinMate is a full-stack web application designed to help students track, manage, and analyze their daily expenses efficiently.
It provides budgeting tools, transaction tracking, and insightful dashboards to improve financial habits.

🚀 Features

🔐 User Authentication (JWT based)

📊 Dashboard with expense insights

💸 Add / Edit / Delete Transactions

📁 Expense Categories

📅 Recurring Transactions

🎯 Budget Management

📜 Transaction History

📤 CSV Import & Export

💱 Currency Converter

📱 Responsive UI

🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
JavaScript
Axios
Backend
Node.js
Express.js
MongoDB
JWT Authentication
Tools
Git & GitHub
Postman
VS Code
Project Structure
FinMate/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/finmate.git
cd finmate

2️⃣ Setup Backend
cd backend
npm install


Create .env file:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key


Run backend:

npm start

3️⃣ Setup Frontend
cd frontend
npm install
npm run dev

🧪 Usage

Register a new account

Login securely

Add income & expenses

Set budgets

Track financial habits through dashboard

🔐 Environment Variables

The following variables are required in .env:

MONGO_URI=
JWT_SECRET=
PORT=
