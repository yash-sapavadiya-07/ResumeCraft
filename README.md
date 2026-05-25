# ResumeCraft

ResumeCraft is a full-stack resume web application that helps users create resumes and scan them against job descriptions for ATS-style feedback. It includes authentication, a resume creator, dashboard pages, and resume analysis features.

## Google Drive Link

Project files / demo video / screenshots:

[![Google Drive](https://www.vectorlogo.zone/logos/google_drive/google_drive-icon.svg)](https://drive.google.com/drive/folders/1DrsW7JVjVf-UQ7qyAWxzZzT8dE-PBekG?usp=sharing)

## Features

- User registration and login
- Resume creator page
- Resume scanner with ATS-style analysis
- Dashboard for authenticated users
- Resume parsing support for PDF and DOCX files
- Modern React frontend with responsive UI
- Express and MongoDB backend API

## Tech Stack

**Frontend**

- React
- Vite
- Tailwind CSS
- React Router
- Axios
- Recharts
- Lucide React

**Backend**

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT authentication
- Bcrypt password hashing
- Multer file upload
- PDF and DOCX parsing

## Project Structure

```text
resume web application/
|-- backend/
|   |-- routes/
|   |-- utils/
|   |-- package.json
|   `-- server.js
|-- frontend/
|   |-- public/
|   |-- src/
|   |-- package.json
|   `-- vite.config.js
`-- README.md
```

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
cd "resume web application"
```

Install frontend dependencies:

```bash
cd frontend
npm install
```

Install backend dependencies:

```bash
cd ../backend
npm install
```

## Environment Variables

Create a `.env` file inside the `backend` folder:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

## Run Locally

Start the backend server:

```bash
cd backend
npm start
```

Start the frontend development server:

```bash
cd frontend
npm run dev
```

Open the frontend URL shown in the terminal, usually:

```text
http://localhost:5173
```

## Important Notes

- Do not upload `node_modules` to GitHub.
- Add your Google Drive link in the section above.
- Add your MongoDB connection string and JWT secret in `backend/.env`.
- Make sure your Google Drive link is set to public or "Anyone with the link can view".

## Author

Yash
