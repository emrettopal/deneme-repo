# deneme-repo

# 💰 Full-Stack Expense Tracker (MERN Stack)

A comprehensive expense management web application built to help users seamlessly track their financial activities, manage incomes/expenses, and visualize budget metrics through a modern user interface.

## 🌟 Core Features
* **Full CRUD Operations:** Add, view, edit, and delete income and expense records.
* **Smart Dashboard:** Real-time calculation of total balance, total income, and total expenses.
* **Data Persistence:** Fully integrated with a secure cloud database to persist transaction history.
* **RESTful API Architecture:** Robust backend services handling structured data flow between client and server.

---

## 🛠️ Tech Stack & Architecture

### Frontend (Client)
* Framework: React.js
* State Management: Context API / Hooks
* Styling: CSS3 / Component-based UI

### Backend (Server)
* Runtime: Node.js
* Framework: Express.js
* Database: MongoDB (with Mongoose Object Modeling)

---

## 💻 Setup and Installation

### 1. Clone the Repository
git clone https://github.com/emrettopal/deneme-repo.git
cd deneme-repo

### 2. Backend Installation & Config
1. Navigate to the server folder: `cd server` (or your backend root).
2. Install packages: `npm install`
3. Create a `.env` file and add your MongoDB Connection URI and Port:
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
4. Start the server: `npm start` or `npm run dev`

### 3. Frontend Installation
1. Navigate to the client folder: `cd client` (or your frontend root).
2. Install packages: `npm install`
3. Start the UI: `npm start`

---

## 🔒 Security & Data Validation
* Implemented backend request body validation to ensure correct financial logging.
* CORS configured properly to allow secure communication between the frontend and backend origins.
