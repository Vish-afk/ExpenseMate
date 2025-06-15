## Overview:

This is a full-stack web application designed to help users efficiently track and manage their daily expenses. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), the app provides an intuitive interface to log, categorize, and analyze personal or business expenses.

## Key Features:

    Secure User Authentication:
    Users can sign up and log in to their accounts. The system supports role-based permissions for admins to manage user data.

    Expense and Category Management:
    Users can easily add, modify, and delete expense records. They can also create categories to better organize spending, track amounts, and attach supporting documents like receipts.

    Analytics Dashboard:
    A dynamic dashboard displays key financial metrics such as total spending, category-wise expenses, and the most recent transactions. Visual charts and graphs offer clear insights into spending habits.

    Responsive Design:
    The UI is fully responsive, designed for a smooth experience on desktops, tablets, and mobile devices. Built using React and styled with Bootstrap and Material-Icons for a sleek, modern look.

## Tech Stack:

    Frontend:

        React.js (for building dynamic UI)
        Bootstrap (for responsive design)
        Material-Icons (for UI elements)

    Backend:

        Node.js & Express.js (for RESTful API services)
        JSON Web Tokens (JWT) for secure authentication

    Database:

        MongoDB (NoSQL database for flexible data storage)
        Mongoose (for schema definition and validation)

## Run Locally

Clone the project

```bash
  git clone https://github.com/Vish-afk/ExpenseMate.git
```

Go to the project directory

```bash
  cd Expense-Tracker-App
```

Go to the frontend directory and Install dependencies

```bash
  cd frontend
```

```bash
  npm install
```

Go to the backend directory and Install dependencies

```bash
  cd backend
```

```bash
  npm install
```

Start the frontend server

```bash
  npm start
```

Start the backend server

```bash
  npm run dev
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in backend folder

create config folder and add config.env file in it and all all env variables there.

`MONGO_URL` : Your MongoDB Connection String

`PORT`: PORT number
