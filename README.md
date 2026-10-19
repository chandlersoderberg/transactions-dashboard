# Transactions Dashboard

This is my submission for the project. The task was to create a MERN stack application that fetches product transaction data from a third-party API and displays various visualizations and tables based on that data.

---

## 🛠 Tech Stack

- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MySQL (used instead of PostgreSQL)
- Charting Library: Recharts
- HTTP Client: Axios

---


## 🚀 How to Run the Project Locally

### Backend (Node + MySQL)

1. Go to the backend directory:
   ```
   cd my-node-app
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your `.env` file:
   ```
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=yourpassword
   DB_NAME=transactions
   ```

4. Start the backend server:
   ```
   node app.js
   ```

---

### Frontend (React)

1. Go to the frontend directory:
   ```
   cd frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the frontend app:
   ```
   npm start
   ```

---

## 📊 Features Implemented

- ✅ Fetched and seeded DB with transactions from [Public Data API](https://s3.amazonaws.com/datasys.com/product_transaction.json)
- ✅ Transactions table with search and pagination
- ✅ Statistics section with:
  - Total Sale Amount
  - Total Sold Items
  - Total Not Sold Items
- ✅ Bar Chart showing number of items in price ranges
- ✅ Pie Chart showing unique category distribution
- ✅ Combined API returning data from all endpoints
- ✅ Month dropdown working across components

---

## 👨‍💻 Author

Open-source project maintained by the author.

