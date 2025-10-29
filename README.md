# 📰 College Journalism Platform

> Where storytelling meets technology — a full-stack web platform that brings campus journalism to life.

The **College Journalism Platform** is a modern digital newsroom built for and by students.  
Powered by **Next.js** on the frontend and **Sanity CMS** on the backend, it gives student journalists a fast, elegant, and dynamic space to publish stories, share events, and showcase creativity.

This project transforms a traditional college club into a living, collaborative media hub — one that celebrates the power of words, visuals, and technology.

---

## ✨ Features

- 🧾 **Dynamic Articles:** Create, edit, and publish stories in real time  
- 👥 **Author Profiles:** Highlight student writers and editors  
- 🗂️ **Categories & Tags:** Organize content by topic or section  
- 🖼️ **Media Library:** Upload and manage images directly from Sanity Studio  
- ⚡ **Modern Frontend:** Built with Next.js for speed, SEO, and accessibility  
- 🔄 **Instant Sync:** Real-time content updates through Sanity’s API  
- 🌐 **Fully Responsive:** Optimized for mobile, tablet, and desktop  
- 🔒 **Secure & Scalable:** Headless architecture ready for deployment on Vercel  

---

## 🧱 Tech Stack

| Layer | Technology | Purpose |
|-------|-------------|----------|
| **Frontend** | [Next.js 15](https://nextjs.org) | UI framework and routing |
|  | [Tailwind CSS](https://tailwindcss.com) | Styling and responsive design |
|  | [TypeScript](https://www.typescriptlang.org/) | Type safety and maintainability |
| **Backend** | [Sanity CMS](https://www.sanity.io/) | Content management and real-time data |
| **Deployment** | [Vercel](https://vercel.com) | Hosting and CI/CD |
| **Database** | Sanity’s managed datastore | Fast, cloud-based storage |

---

## ⚙️ Setup

### 1. Clone the repositories
```bash
git clone https://github.com/your-username/journalism-frontend.git
git clone https://github.com/your-username/journalism-sanity-backend.git
```

### 2. Install dependencies
Navigate into each folder and install the required packages:
```bash
cd journalism-frontend
npm install
# then
cd ../journalism-sanity-backend
npm install
```

### 3. Configure environment variables
Create a .env.local file in your frontend directory:
```bash
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=production
NEXT_PUBLIC_SANITY_API_VERSION=2025-01-01
SANITY_READ_TOKEN=your_sanity_token
```

### 4. Run development servers
Start both projects:
```bash
# In one terminal (Sanity)
cd journalism-sanity-backend
npm run dev
```
```bash
# In another terminal (Frontend)
cd journalism-frontend
npm run dev
```

Your project will be live at:

Frontend → http://localhost:3000

Sanity Studio → http://localhost:3333

---

## 🧑‍💻 Development Highlights
Built with Next.js App Router and Server Components

Custom Sanity schemas for articles, authors, and categories

GROQ queries for fast and flexible data fetching

Optimized images with next/image

Accessible design using Tailwind utilities

Deployed via Vercel’s Git integration

---

## 🎯 Goals
Empower student journalists with digital publishing tools

Showcase writing, photography, and creative projects

Teach members web development through real-world collaboration

Build a scalable, long-term digital home for the Journalism Club

---

## 🧩 Future Improvements
🔍 Article search and filtering

💬 Comments and community interaction

🗞️ Newsletter integration

📊 Analytics dashboard for editors

🌙 Dark mode

---

## 🏫 Credits
Developed by Erden Rayev

Built with ❤️ using Next.js, Sanity, and Vercel

“Good journalism is about truth — good code is about clarity. This project celebrates both.”

---

## 📜 License
This project is licensed under the MIT License.

---
