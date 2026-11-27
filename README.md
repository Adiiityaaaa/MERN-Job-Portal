# 💼 MERN Job Portal

### Full Stack Job Portal & Recruitment Management System

A full-stack job portal built using the MERN Stack (MongoDB, Express.js, React.js and Node.js). The platform connects job seekers with recruiters, allowing candidates to explore job opportunities, apply for positions and track applications, while recruiters can manage job listings and applicants.

---

## 🚀 Features

### 👨‍💼 Job Seeker
- User registration and secure login
- Browse and search job opportunities
- Filter jobs by categories
- Apply for jobs
- Upload resumes
- Track application status
- Save favourite jobs
- Manage personal profile

### 🏢 Recruiter
- Recruiter authentication
- Create and manage job listings
- View applications
- Review candidate resumes
- Manage recruitment status
- Track hiring analytics

### 🛡️ Admin Dashboard
- Manage users
- Monitor job listings
- Manage organizations
- Review platform activities

### ✨ Additional Features
- ATS Resume Prediction
- Resume compatibility analysis
- Real-time application tracking
- Secure JWT authentication
- Email notifications
- Responsive user interface
- Cloudinary file uploads

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend |
| Node.js | Backend Runtime |
| Express.js | Backend Framework |
| MongoDB | Database |
| Mongoose | Database Management |
| Redux Toolkit | State Management |
| Tailwind CSS | Styling |
| JWT | Authentication |
| Cloudinary | File Storage |
| Vite | Frontend Build Tool |

---

## 📂 Project Structure

```text
MERN-Job-Portal/
│
├── Backend/
│   ├── ats/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── scripts/
│   ├── tests/
│   ├── utils/
│   ├── index.js
│   └── package.json
│
├── Frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── packages/
├── docs/
├── wiki/
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Adiiityaaaa/MERN-Job-Portal.git
```

```bash
cd MERN-Job-Portal
```

### 2. Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file using `.env.example` and configure the required environment variables, including:

```env
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
FIELD_ENCRYPTION_KEY=your_encryption_key
```

Configure other required variables according to `Backend/.env.example`.

Start the backend:

```bash
npm run dev
```

Backend runs at:

`http://localhost:5001`

### 3. Frontend Setup

Open another terminal:

```bash
cd Frontend
npm install
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5001
```

Start the frontend:

```bash
npm run dev
```

Frontend runs at:

`http://localhost:5173`

---

## 🌐 Deployment

The application can be deployed using:

| Service | Purpose |
|---|---|
| Vercel | Frontend Hosting |
| Render | Backend Hosting |
| MongoDB Atlas | Database Hosting |
| Cloudinary | Media Storage |

Deployment configuration and environment variables must be updated before publishing.

---

## 🔐 Security

- JWT-based authentication
- Password and account security
- AES-256-GCM encryption for sensitive information
- Protected API routes
- Environment-based configuration
- CORS configuration

**Important:** Never upload `.env` files, passwords, API keys or database credentials to GitHub.

---

## 👨‍💻 Project Maintainer

**Aditya Sharma**

B.Tech Computer Science & Engineering

GitHub: [Adiiityaaaa](https://github.com/Adiiityaaaa)

Project Repository: [MERN-Job-Portal](https://github.com/Adiiityaaaa/MERN-Job-Portal)

---

## 📜 License & Attribution

This project is based on the original FOREWORK project by Jashanpreet Singh.

The original MIT License and applicable attribution are retained. This repository contains a customized version intended for learning and academic project purposes.

---

### ⭐ If you find this project useful, consider giving the repository a star!

**Developed and maintained by Aditya Sharma.**