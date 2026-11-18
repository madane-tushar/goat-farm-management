# GoatFarm Pro 🐐

A full-stack Goat Farm Management web app built with React, Node.js, Express, and MySQL.

## Features
- Goat records (add, edit, delete)
- Groups and hitting cycle tracking
- Breeding and pregnancy management
- Vaccination schedule
- Finance: income, expenses, net profit
- Dashboard with monthly charts and breed distribution

## Pages
- `/login`: Login and register
- `/dashboard`: Stats, charts, recent goats
- `/goats`: Add, edit, delete goats
- `/finance`: Income and expense tracking
- `/vaccinations`: Vaccination tracker
- `/settings`: Profile and notification settings

## Tech Stack
- Frontend: React
- Backend: Node.js, Express
- Database: MySQL

## Setup

1. Clone the repository
   ```bash
   git clone https://github.com/madane-tushar/goat-farm-management.git
   cd goat-farm-management
   ```

2. Set up the backend
   ```bash
   cd server
   npm install
   cp .env.example .env
   ```
   Open `server/.env` and fill in your MySQL credentials.

3. Start MySQL (for example with XAMPP) and create the database.

4. Run the server
   ```bash
   node index.js
   ```

5. In a new terminal, start the frontend from the project root
   ```bash
   npm install
   npm start
   ```

The app runs at http://localhost:3000.

## Author
Tushar Madane
