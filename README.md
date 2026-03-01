<div align="center">

# 🎓 EduCare LMS — Full-Stack Learning Management System

Modern online learning platform built with **MERN** stack (MongoDB, Express, React + Vite, Node.js).  
Allows educators to create courses, upload videos, manage students, and lets learners enroll, track progress, and learn at their own pace.

</div>

## ✨ Features

### Student Side
- Browse & search courses by category/title
- View detailed course info (description, chapters, educator, price)
- Enroll in courses (free or paid)
- Watch chapter videos directly in platform
- Track enrolled courses & progress
- Profile with enrolled courses list
- Responsive design + dark mode support

### Educator / Admin Side
- Create & manage courses (title, description, price, discount, thumbnail)
- Add unlimited chapters with video links (YouTube embeds)
- View enrolled students per course
- Dashboard analytics (total courses, students, revenue)
- Secure authentication (email/password + Google OAuth)

### Tech Highlights
- Google OAuth for quick sign-up/login
- JWT authentication + role-based access (student/educator)
- Zod + React Hook Form for validation
- Tailwind CSS + shadcn/ui components
- Axios API calls with loading/error states
- Context API for global state (courses, user)

## 🛠 Tech Stack

**Frontend**  
- React 18 + Vite  
- React Router v6  
- Tailwind CSS + shadcn/ui  
- Axios / React Hook Form / Zod  
- Context API  

**Backend**  
- Node.js + Express  
- MongoDB + Mongoose  
- JWT + bcrypt  
- Google OAuth 2.0  
- Cloudinary (avatar uploads)  

**Deployment**  
- Vercel (frontend & backend serverless)  
- MongoDB Atlas  

## 🚀 Quick Setup (Local Development)

### Prerequisites
- Node.js ≥ 18
- MongoDB (local or Atlas)
- Google OAuth Client ID & Secret (for Google login)

### 1. Clone the repo
```bash
git clone https://github.com/tayyabodla-786/EDUCARELMSS.git
cd EDUCARELMSS
