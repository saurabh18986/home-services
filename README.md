# Home Services App

Welcome to the Home Services application! This project has a separate frontend (React/Vite) and backend (Node/Express).

## Prerequisites
- **Node.js** installed on your machine.

## How to Run the Project Locally

You will need to open **two separate terminal windows** (or two tabs in VS Code). One terminal will run your backend server, and the other will run your frontend website.

### Step 1: Run the Backend Server
The backend handles the database, API, and business logic. We have configured an in-memory database, so you don't even need to install MongoDB locally!

1. Open your first terminal.
2. Navigate to the `server` folder:
   ```bash
   cd "d:\Hey 100rbh\Project\home services\server"
   ```
3. Install dependencies (you only need to do this once):
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   npm run dev
   ```
> You should see a message saying `Server listening on port 5000` and `In-Memory MongoDB Connected`. Keep this terminal open!

---

### Step 2: Run the Frontend Client
The frontend is the React application the user interacts with in their browser.

1. Open a **second** terminal window (keep the first one running).
2. Navigate to the `client` folder:
   ```bash
   cd "d:\Hey 100rbh\Project\home services\client"
   ```
3. Install dependencies (you only need to do this once):
   ```bash
   npm install
   ```
4. Start the React app:
   ```bash
   npm run dev
   ```
> You should see a message saying `Local: http://localhost:5173/`. Keep this terminal open too!

---

### Step 3: View the App
Now that both the server and client are running, simply open your web browser (Chrome, Edge, Firefox, etc.) and go to:

👉 **http://localhost:5173**

### Stopping the App
When you are done testing, you can stop the servers by clicking inside each terminal window and pressing `Ctrl + C` on your keyboard.
"# home-services" 
"# home-services" 
