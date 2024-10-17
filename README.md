
# Loan Manager Application

A full-stack application for managing loan applications with a form and dashboard. The frontend is built with **React & TypeScript**, and the backend uses **Node.js, TypeScript, and MongoDB**.

---

## Features
- Users can submit loan applications.
- Dashboard displays real-time statistics.
- Supports multiple user inputs.
- MongoDB for data management.

---

## Tech Stack
- **Frontend**: React, TypeScript  
- **Backend**: Node.js, Express, TypeScript  
- **Database**: MongoDB  

---

## Installation

### Prerequisites
- Node.js  
- MongoDB (Atlas or Local)

### Clone the Repository
```bash
git clone https://github.com/chiru-13/creditsea_Assignment
cd loan-manager
```

### Install Dependencies
```bash
cd frontend && npm install
cd ../backend && npm install
```

### Configure Environment Variables

**Backend (.env)**:
```
MONGO_URI=your-mongo-uri
PORT=5000
SECRET_KEY=your-secret-key
```

**Frontend (.env)**:
```
REACT_APP_API_URL=http://localhost:5000
```

---

## Running the Project

**Backend**:
```bash
cd backend
npx tsc && npx nodemon dist/app.js
```

**Frontend**:
```bash
cd frontend
npm start
```

- Frontend: [http://localhost:3000](http://localhost:3000)  
- Backend: [http://localhost:5000](http://localhost:5000)

---

## API Endpoints
| Method | Endpoint         | Description                   |
|--------|------------------|-------------------------------|
| POST   | /api/loans       | Submit a loan application     |
| GET    | /api/loans       | Get all loan applications     |
| GET    | /api/statistics  | Retrieve dashboard statistics |

---
