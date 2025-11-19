# Fullstack Project Setup

This guide will walk you through setting up and running both the backend (Node.js with Express) and frontend (Angular) parts of this fullstack project.

## Cloning the Repository

First, you need to clone the repository to your local machine.

```bash
git clone https://github.com/candra-dev/backend_frontend_paw_2.git
cd https://github.com/candra-dev/backend_frontend_paw_2.git
```

## Backend Setup (Node.js with Express)

The backend is built using Node.js and Express.

1.   **Navigate to the backend directory:**

     ```bash
     cd backend
     ```

     (Assuming your backend code is in a folder named `backend`. Adjust if your folder structure is different.)

2.   **Install dependencies:**

     ```bash
     npm install
     ```

     This command reads the `package.json` file and installs all the necessary Node.js modules.

3.   **Run the backend server:**

     ```bash
     npm run dev
     ```

     The backend server should now be running, usually on `http://localhost:3000` or a port specified in your configuration.

## Frontend Setup (Angular)

The frontend is built using Angular.

**Important:** Open a new terminal for the frontend setup.

1.   **Navigate to the frontend directory:**

     ```bash
     cd frontend
     ```

     (Assuming your backend code is in a folder named `frontend`. Adjust if your folder structure is different.)

2.   **Install dependencies:**

     ```bash
     npm install

     ```

     This command reads the `package.json` file and installs all the necessary Node.js modules.

3.   **Run the frontend server:**

     ```bash
     ng serve
     ```

     The frontend server should now be running, usually on `http://localhost:4200` or a port specified in your configuration.
