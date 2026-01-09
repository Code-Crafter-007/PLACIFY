# Placify

Placify is a desktop-first placement readiness platform built to help students prepare for internships and full-time roles in a structured and measurable way.

The platform brings resume evaluation, coding performance tracking, AI-based interview practice, and role readiness into a single system, reducing scattered preparation and giving students a clear picture of where they stand.

Placify is built as a group project and packaged as a desktop application using Electron.

---

## Purpose

Placify is designed with one clear objective:

Help students evaluate their current placement readiness, identify gaps, and improve step by step before facing real recruitment processes.

---

## Core Capabilities

- Resume evaluation using AI
- Coding and development performance tracking
- AI-driven mock interviews
- Role readiness scoring
- Placement workflow management
- Admin-controlled verification system
- Desktop application experience

---

## Student Features

### Resume Evaluation

Students can analyze and improve their resumes based on target job roles.

- Upload resume file
- Select intended role
- Resume is evaluated using an ATS-style AI model
- Role-specific scoring is generated
- Detailed feedback includes
  - Missing and present keywords
  - Skill gaps
  - Role expectations
- Actionable suggestions to improve resume quality

This allows continuous resume refinement during placement preparation.

---

### Performance Tracking

Placify consolidates coding and development performance from multiple platforms.

Supported platforms include:
- LeetCode
- Codeforces
- CodeChef
- AtCoder
- GitHub

Process:
- Students enter their platform usernames
- Performance data is fetched automatically
- A combined performance score is calculated
- Progress can be tracked from a single dashboard

This removes the need to manually monitor multiple platforms.

---

### AI Mock Interview

The AI Mock Interview module provides realistic interview practice.

- Built using Gemini API
- Supports text and voice interaction
- Speech recognition enabled
- Audio responses supported
- Interview flow includes
  - Introduction questions
  - Technical questions
  - HR and soft-skill questions
- AI evaluates responses and identifies weak areas

This helps students build confidence and interview familiarity.

---

### Role Exploration and Applications

Placify connects readiness with real job opportunities.

- Readiness score is calculated using
  - Resume score
  - Coding performance
  - Certifications
  - CGPA
- Students can view eligible roles
- Admin shortlists students based on readiness
- Notifications sent for shortlisted roles
- Students can apply directly
- Offer letters can be uploaded
- Offers are verified by admin
- Approved offers are added to placement records

This creates a structured and verified placement workflow.

---

## Admin Features

The admin panel controls placement operations and data integrity.

- Manage companies and job roles
- Define eligibility criteria
- View and manage student profiles
- Shortlist candidates using readiness scores
- Notify shortlisted students
- Verify uploaded offer letters
- Approve or reject offers
- Publish verified placement statistics

This ensures transparency and accuracy in placement data.

---

## Placement Dashboard

- Displays verified placement offers
- Shows overall placement statistics
- Provides a clear view of placement outcomes

---

## Technology Stack

Web and Backend:
- MongoDB
- Express.js
- React
- Node.js

Desktop Application:
- Electron.js

Other Tools:
- JavaScript and TypeScript
- REST APIs
- AI APIs for analysis and interviews

Authentication:
- JWT based authentication

---

## Application Structure

- client – React frontend
- backend – Node and Express backend
- electron – Desktop application configuration
- routes – API routing
- controllers – Business logic
- models – Database schemas

---

## Project Status

Completed as a group project with scope for future enhancement.



MIT License
