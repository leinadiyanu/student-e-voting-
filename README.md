# 🗳️ University Electronic Voting System

A secure, role-based backend system for managing university student elections.

## 📌 Overview

This project is designed for campus elections, allowing students to vote securely using their **matriculation number** and **surname**. There is no public registration—**only preloaded student records** can access the system.

Elections are managed by an **electoral committee**, not admins. The committee can:
- Create and schedule elections
- Add, edit, and remove candidates
- Set voting periods and result release times
- Release results manually (locking further votes)

Admins are only responsible for managing student and committee accounts. They cannot vote, alter elections, or view results.

## 🧱 Tech Stack

- **Backend**: Node.js (Express)
- **Database**: PostgreSQL
- **Authentication**: JWT
- **ORM/Query**: Prisma or Sequelize (optional)
- **Validation**: Joi / Zod
- **Deployment**: Render, Railway, or VPS

## 🔐 Core Features

- Student login with matric number and surname
- One vote per user per election
- Time-based access control (start, end, and result release)
- Role-based access: Admin, Electoral Committee, Student
- Enforced vote integrity and privacy

## 📂 Project Structure (MVC-style)

## 🚀 Getting Started

1. Clone the repo  
   `git clone https://github.com/your-username/university-voting-system.git`

2. Install dependencies  
   `npm install`

3. Set up your `.env`  


## 📂 Project Structure (MVC-style)

```
PORT=5000
DB_URL=postgresql://...
JWT_SECRET=your_jwt_secret
```
