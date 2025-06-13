# 🚀 Full Stack Job Portal — Role-Based Platform for Recruiters & Applicants

A modern, full-stack Job Portal that empowers **Recruiters to post and manage jobs**, and **Applicants to apply with resumes and track their applications**. Built using industry-grade technologies like **React JS**, **Supabase**, **Clerk**, and **Shadcn UI**, with clean design powered by **Tailwind CSS**.

Designed with **real-world product architecture** in mind — perfect for showcasing full-stack capabilities.

---

## 🛠 Tech Stack

- **Frontend**: React JS, Tailwind CSS, Shadcn UI
- **Authentication & Role Management**: Clerk
- **Backend-as-a-Service**: Supabase (PostgreSQL)
- **Authorization**: Role-Based Access Control (RBAC)
- **Deployment**: Vercel (or other modern hosts)

---

## 🎯 Key Features

### 👥 User Roles:
- **Recruiter**
  - Create, update, and delete job postings
  - View list of applicants per job
  - Access uploaded resumes
  - Shortlist or mark status for each applicant

- **Applicant**
  - Register/Login via Clerk
  - View and apply to available jobs
  - Upload and manage resume
  - Track application status in real-time

---

### 📦 Core Functionalities:
- ✅ Authentication with Clerk (OAuth, Email-based login)
- ✅ Post, View, Apply to Jobs (Real-time)
- ✅ Role-Based Access (Recruiter vs Applicant)
- ✅ Resume Upload Integration (with Supabase Storage or custom logic)
- ✅ Realtime sync with Supabase
- ✅ Clean & responsive UI with Tailwind + Shadcn UI components

---

## 📄 Environment Variables

Before running the project locally, create a `.env` file in the **root directory** and add the following keys:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
