# 🚀 HireHub - Full Stack Job Portal

A full-stack job portal application where **recruiters can post jobs** and **candidates can browse and apply**. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

---

## 🔗 Links

- **Frontend:** [Vercel Deployment](https://full-stack-job-portal-wtthfc261-musaibs-projects-5e2f747b.vercel.app)
- **Backend:** [Render Deployment](https://full-stack-jobportal-ct6o.onrender.com)
- **GitHub:** [MusaibRasheed/Full_Stack_JobPortal](https://github.com/MusaibRasheed/Full_Stack_JobPortal)

---

## ✨ Features

- 🔐 **JWT Authentication** — Secure login and signup with role-based access (Student / Recruiter)
- 👤 **Profile Management** — Users can upload profile pictures and manage their information
- 🏢 **Company Management** — Recruiters can create and manage their company profiles
- 💼 **Job Posting** — Recruiters can post, update, and delete job listings
- 🔍 **Job Search & Filtering** — Candidates can browse and filter jobs by keyword, location, and type
- 📩 **Job Applications** — Students can apply for jobs and track their application status
- 📊 **Recruiter Dashboard** — Recruiters can view and manage all applications for their posted jobs
- 📱 **Responsive UI** — Clean and responsive design built with React.js and Tailwind CSS

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React.js, Tailwind CSS, Redux |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Authentication | JWT (JSON Web Tokens) |
| File Upload | Multer / Cloudinary |
| Deployment | Vercel (Frontend), Render (Backend) |

---

## 📁 Project Structure

```
Full_Stack_JobPortal/
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── index.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── redux/
│   │   └── App.jsx
│   └── index.html
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js installed
- MongoDB Atlas account
- Git

### 1. Clone the repository
```bash
git clone https://github.com/MusaibRasheed/Full_Stack_JobPortal.git
cd Full_Stack_JobPortal
```

### 2. Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:
```env
MONGO_URI=your_mongodb_connection_string
SECRET_KEY=your_jwt_secret
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
PORT=3000
```

Start the backend:
```bash
npm run dev
```

### 3. Setup Frontend
```bash
cd frontend
npm install
```

Create a `.env` file in the `frontend` folder:
```env
VITE_API_URL=http://localhost:3000
```

Start the frontend:
```bash
npm run dev
```

---

## 👤 User Roles

### Student
- Register and create a profile
- Browse and search for jobs
- Apply for jobs
- Track application status

### Recruiter
- Register and create a company profile
- Post new job listings
- View all applicants for each job
- Accept or reject applications

---

## 📬 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/v1/user/register` | Register a new user |
| POST | `/api/v1/user/login` | Login user |
| GET | `/api/v1/job/get` | Get all jobs |
| POST | `/api/v1/job/post` | Post a new job |
| POST | `/api/v1/application/apply/:id` | Apply for a job |
| GET | `/api/v1/application/get` | Get user applications |

---

## 🙋‍♂️ Author

**Musaib Rasheed**
- GitHub: [@MusaibRasheed](https://github.com/MusaibRasheed)

---

⭐ If you found this project helpful, please give it a star!
