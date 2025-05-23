# 🎓 Full-Stack Feedback App

## 📚 Tech Stack
- **Frontend:** Next.js + Tailwind CSS
- **Backend:** Express.js + Node.js
- **Communication:** REST API (GET, POST, PUT, DELETE)

---

## 📌 Objective

Build a full-stack web application with:
- A form to collect feedback
- Display all submitted entries
- Edit or delete entries
- Proper validation and styling
- Success confirmation screen after submission

---

## 📁 Project Structure

```
assignment-4-fullstack/
├── express-backend/
│   ├── server.js
│   └── package.json
└── nextjs-frontend/
    ├── app/
    │   ├── layout.tsx        # Navigation bar
    │   ├── page.tsx          # Feedback form (Home)
    │   ├── data/page.tsx     # Data display with edit/delete
    │   └── success/page.tsx  # Success message with submitted values
    ├── tailwind.config.js
    ├── postcss.config.js
    ├── package.json
    └── globals.css
```

---

## 🚀 How to Run

### 1️⃣ Backend (Express.js)

```bash
cd express-backend
npm install
node server.js
```

Runs on: `http://localhost:5000`

---

### 2️⃣ Frontend (Next.js)

```bash
cd nextjs-frontend
npm install
npm run dev
```

Runs on: `http://localhost:3000`

---

## ✨ Features

- ✅ Feedback form with validation
- ✅ Gender selection dropdown
- ✅ Success screen with submitted data
- ✅ View all submissions in table
- ✅ Edit or delete entries inline
- ✅ Responsive Tailwind styling

---

## 🔄 API Endpoints

### POST `/api/submit`
Submit form data.

### GET `/api/data`
Fetch all submitted entries.

### PUT `/api/data/:id`
Update entry by ID.

### DELETE `/api/data/:id`
Delete entry by ID.

---

## 🧪 Example Submission Flow

1. Fill the form on home page (`/`)
2. On submit, you'll see a confirmation screen with your info
3. View/edit/delete your submission on the `/data` page
