# StudyMood – Capstone Project Plan

## Overview
StudyMood is a full-stack productivity web app designed to help students manage their study tasks and personal reflections in one place. It combines a **colorful, emoji-accented dashboard** with features for **task tracking**, **journaling**, and **progress monitoring**. The goal is to promote balance and motivation through both structured study planning and emotional awareness.

## Core Features
- **User Authentication:** Secure email and password login system.
- **Task Management (CRUD):** Create, read, update, and delete study tasks.
- **Journal Entries (CRUD):** Record, edit, and delete daily reflections.
- **Dynamic Dashboard:** Displays tasks, mood summaries, and motivational elements (emojis, color themes).
- **Responsive UI:** Optimized for both desktop and mobile.

## Architecture
StudyMood will use the **MERN stack**:
- **Frontend:** Vite + React for a fast, modern UI with component-based architecture and state management (via Context or a lightweight store).
- **Backend:** Node.js + Express for RESTful API endpoints handling authentication, tasks, and journals.
- **Database:** MongoDB Atlas for persistent cloud data storage.
- **Authentication:** Implemented with JWT (JSON Web Tokens) for secure user sessions.

## Data Model (Initial Draft)
**User**
```js
{
  _id,
  email,
  passwordHash,
  createdAt
}

# StudyMood Frontend

## Overview
This is the **frontend** of StudyMood — a productivity and mood-tracking web app for students. Built with **Vite + React**, it provides a colorful dashboard for managing study tasks and journaling.

## Tech Stack
- React (Vite)
- React Router
- Axios
- TailwindCSS or CSS Modules

## Getting Started
```bash
git clone https://github.com/shaay98/studymood-app-frontend-.git
cd studymood-frontend
npm install
npm run dev
