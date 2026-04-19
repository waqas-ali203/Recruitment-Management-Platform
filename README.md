# 💼 HirePulse - Enterprise Job Board & Applicant Tracking Platform

A modern, full-stack recruitment and talent acquisition platform designed for candidates, employers, and administrators. Provides complete vacancy posting lifecycles, automated applicant tracking, and interview coordination.

---

### 📸 Application Interface

![HirePulse Platform Dashboard Preview](/frontend/src/assets/demo.png)

---

## 🌟 Core Features

- **Candidate Discovery & Job Search:** Keyword, location, and role-category filtering for job vacancies.
- **Recruiter Job Management:** End-to-end posting lifecycle, editing, and closing active job roles.
- **Applicant Tracking System (ATS):** Centralized dashboard to screen resumes, advance candidates, or decline submissions.
- **Automated Communication:** Automated email triggers for application confirmation, screening updates, and interview schedules.
- **Comprehensive Admin Panel:** Global supervision of registered firms, posted vacancies, platform user metrics, and role queries.
- **Secure Authentication:** JWT-driven sessions with Bcrypt salted password encryption.

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| **Frontend Client** | React.js (Vite), Tailwind CSS, Lucide Icons |
| **Recruiter Admin** | React.js Dashboard, State Management, Responsive Analytics |
| **Backend API** | Node.js, Express.js (REST Architecture) |
| **Database** | MongoDB Atlas, Mongoose ODM |
| **Email Service** | NodeMailer / External SMTP Integration |
| **Tooling & Config** | ESLint, Vite, Git Version Control |

---

## 📁 System Architecture

```text
Job_Portal/
├── admin/                    # Admin management portal
│   ├── src/components/       # Job & recruiter dashboard components
│   └── package.json
├── backend/                  # RESTful API server
│   ├── controllers/          # Job, interview, and user logic
│   ├── models/               # MongoDB document schemas
│   ├── utils/                # Helper utilities & email dispatcher
│   └── server.js
├── frontend/                 # Public job board client
│   ├── src/assets/           # Graphics, branding, and hero imagery
│   └── package.json
└── README.md