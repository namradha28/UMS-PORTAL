# 🎓 UMS Portal - University Management System

A premium, interactive, and high-performance University Management System built with a modern **Glow-UI** aesthetic. This portal features a robust Node.js/Express backend and a dynamic React frontend with seamless API integration.

![Banner](https://img.shields.io/badge/UI-Interactive_Dark_Theme-blueviolet?style=for-the-badge)
![Tech](https://img.shields.io/badge/Stack-MERN-green?style=for-the-badge)

## ✨ Key Features

-   **🌟 Neon Glow UI**: Immersive dark theme with glassmorphism and animated neon effects.
-   **📊 Dynamic Dashboard**: Role-based views for Students, Faculty, and Admin.
-   **📚 Course Management**: Track progress, view instructors, and manage enrollments.
-   **📃 Syllabus & Queries**: Interactive sections for downloading materials and submitting support queries.
-   **🔐 Secure Auth**: JWT-based authentication with role-based access control (RBAC).
-   **⚡ Live Updates**: Real-time feedback and smooth transitions using Framer Motion.

## 🛠️ Tech Stack

-   **Frontend**: React.js, Vite, Framer Motion, Lucide Icons, CSS3 (Vanilla).
-   **Backend**: Node.js, Express.js, MongoDB (Mongoose), JWT, Bcrypt.
-   **Deployment**: Docker-ready for Hugging Face Spaces or any cloud provider.

## 🚀 Getting Started

### Prerequisites

-   Node.js (v18+)
-   MongoDB (Local instance or Atlas URI)

### Local Setup

1.  **Clone the Repository**:
    ```bash
    git clone <your-repo-url>
    cd ums-portal
    ```

2.  **Backend Configuration**:
    Create a `backend/.env` file:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key
    PORT=5000
    ```

3.  **Run the App (Windows/PowerShell)**:
    If you encounter security restrictions, use the following:
    ```powershell
    # Start Backend
    cd backend
    powershell -ExecutionPolicy ByPass -Command "npm install"
    powershell -ExecutionPolicy ByPass -Command "npm start"

    # Start Frontend (in a new terminal)
    cd ../frontend
    powershell -ExecutionPolicy ByPass -Command "npm install"
    powershell -ExecutionPolicy ByPass -Command "npm run dev"
    ```

## ☁️ Deployment (Hugging Face)

This project is pre-configured for **Hugging Face Spaces** using Docker.

1.  Create a new **Docker Space** on Hugging Face.
2.  Add `MONGO_URI` and `JWT_SECRET` to the Space **Secrets**.
3.  Push this repository. The `Dockerfile` in the root will handle the build automatically.

## 🎨 UI Preview

| Dashboard | Login Page |
| :--- | :--- |
| ![Dashboard](https://placehold.co/600x400/0f172a/f8fafc?text=Interactive+Dashboard+with+Glow) | ![Login](https://placehold.co/600x400/0f172a/f8fafc?text=Premium+Glassmorphism+Login) |

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Developed with ❤️ for a seamless university experience.*
