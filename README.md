# 🧠 Debunked: A Blog About Misconceptions

This is a personal blog project where I explore and debunk common myths and misconceptions — one topic at a time. The first post tackles the classic "Do we only use 10% of our brains?" myth.

This project is built with **React** and uses **Firebase** for future data storage and hosting.

---

## 🛠 Tech Stack

- Frontend: React (Create React App or Vite), JavaScript, CSS or Tailwind CSS

- Backend: Node.js, Express.js

- Database: MongoDB (Atlas or local) with Mongoose

- Hosting: Vercel / Render / Heroku for backend, Netlify or Vercel for frontend

- Analytics & SEO: Google Analytics, meta tags for SEO

---

## 📁 Folder Structure (WIP)

misconception-blog/
├─ backend/
│ ├─ server.js // Express server entry point
│ ├─ routes/
│ │ └─ posts.js // API routes for CRUD operations on blog posts
│ ├─ models/
│ │ └─ Post.js // Mongoose schema for blog posts
│ └─ config/
│ └─ db.js // MongoDB connection setup
├─ frontend/
│ ├─ public/
│ │ └─ index.html
│ ├─ src/
│ │ ├─ components/
│ │ │ ├─ Navbar.js
│ │ │ ├─ BlogPostCard.js // For listing posts
│ │ │ └─ BlogPostPage.js // For displaying full post
│ │ ├─ pages/
│ │ │ ├─ Home.js
│ │ │ └─ Blog.js // First blog post content
│ │ ├─ App.js
│ │ └─ index.js
│ └─ package.json
├─ .gitignore
└─ README.md

> This structure will evolve as the project grows (e.g., when routing or dynamic content is added).

---

## 🔍 Features (Phase 1)

- [x] Static blog layout
- [x] First blog post page
- [ ] Firebase setup (Firestore for content storage)
- [ ] Routing (react-router-dom)
- [ ] SEO basics with `react-helmet`
- [ ] Responsive styling

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/debunked-blog.git
cd debunked-blog
npm install
npm start
```

---

## 🚀 Live Demo

Coming soon...
