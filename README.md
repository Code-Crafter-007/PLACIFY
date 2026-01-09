# Placify

Placify is a placement readiness platform built to help students prepare for internships and full-time placements through structured tools, analytics, and guided practice.

This is a group project developed as both a web application and a desktop application.

## Key Features

- AI Mock Interview system
- Placement readiness analytics
- Resume analysis
- Certifications and skill tracking
- Student dashboard
- Admin dashboard with full control
- Dynamic content management from admin panel
- User and admin authentication

## AI Mock Interview

- Designed and developed by me
- Simulates real placement interview scenarios
- Helps users practice and improve answers
- Focused on technical and HR interview rounds

## Platform Modules

- AI Mock Interviews
- Resume Evaluation
- Placement Analytics
- Certifications Management
- Student Progress Tracking
- Admin Content Management

## Tech Stack

Web Application
- MongoDB
- Express.js
- React
- Node.js

Desktop Application
- Electron.js

Additional Tools
- TypeScript
- REST APIs

Database
- MongoDB

Authentication
- JWT based authentication

Deployment
- Web version deployed separately
- Desktop version built using Electron

## Folder Structure

- client – React frontend
- server – Node and Express backend
- electron – Electron main process files
- routes – API routes
- controllers – Business logic
- models – Database schemas
- public – Static assets

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/placify.git
cd placify
````

### 2. Install Dependencies

```bash
npm install
cd client && npm install
cd ../server && npm install
```

### 3. Environment Variables

Create a `.env` file in the server directory.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Run the Project

Run backend

```bash
cd server
npm run dev
```

Run frontend

```bash
cd client
npm start
```

Run Electron app

```bash
npm run electron
```

## Admin Panel

* Manage students and content
* Control interview modules
* Add and update certifications
* Monitor analytics and performance data

## Project Status

Completed as a group project with scope for future expansion.

## Contributors

Group Project
AI Mock Interview module developed by Suraj




