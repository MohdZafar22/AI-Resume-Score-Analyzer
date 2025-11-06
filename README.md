# 🧠 Resume Scan AI

### 🚀 AI-Powered Resume Analysis & Job Match Engine

> Analyze resumes in seconds using AI — extract key skills, experience insights, and match candidates to roles automatically.

![alt image](https://github.com/MohdZafar22/AI-Resume-Score-Analyzer/blob/a1a29742062a9ee19831df039e1973c3b704c70c/Screenshot%20(14).png)
![alt image](https://github.com/MohdZafar22/AI-Resume-Score-Analyzer/blob/3d4b062b267d0b5a66f8e0de4845d2f7307003b7/Screenshot%20(15).png)
![alt image](https://github.com/MohdZafar22/AI-Resume-Score-Analyzer/blob/3d4b062b267d0b5a66f8e0de4845d2f7307003b7/Screenshot%20(16).png)





---

## 🌟 Overview

**Resume Scan AI** is a full-stack web application that leverages **OpenAI's GPT models** and **Next.js 15** to intelligently scan and evaluate resumes.
It helps recruiters, HR professionals, and job seekers understand how well a resume matches a specific job description.

Built with scalability and modern best practices in mind, this project integrates:

* **Next.js (App Router)** for frontend + backend
* **OpenAI API** for AI-driven text processing
* **Prisma ORM + PostgreSQL** for database management
* **Inngest** for background job processing
* **BetterAuth** for secure authentication
* **Tailwind CSS + shadcn/ui** for beautiful UI components

---

## 🧩 Features

✅ **AI Resume Scanning** — Analyze resumes using GPT models for key skills, achievements, and experience relevance.
✅ **Job Match Scoring** — Get a match percentage between a resume and a job description.
✅ **User Authentication** — Secure sign-up/login via **BetterAuth**.
✅ **Background Processing** — Handles heavy tasks asynchronously using **Inngest**.
✅ **Real-time Feedback** — View AI insights and results instantly.
✅ **Responsive UI** — Sleek, accessible interface built with Tailwind + shadcn/ui.
✅ **Database Storage** — Store user profiles, resume data, and history with **Prisma + PostgreSQL**.

---

## 🧠 Tech Stack

| Layer              | Technology                                 | Description                           |
| ------------------ | ------------------------------------------ | ------------------------------------- |
| **Frontend**       | Next.js 15, React, Tailwind CSS, shadcn/ui | Modern, component-driven UI           |
| **Backend**        | Next.js API Routes, Node.js, Inngest       | Handles AI requests & async tasks     |
| **Database**       | PostgreSQL + Prisma ORM                    | Schema & data management              |
| **Authentication** | BetterAuth                                 | Secure user sessions                  |
| **AI Integration** | OpenAI GPT Models                          | Resume parsing, analysis, and scoring |
| **Deployment**     | Vercel                                     | Fast, serverless hosting              |
| **Dev Tools**      | TypeScript, ESLint, Prettier               | Clean & type-safe development         |

---

## 🦯 System Architecture

```
User → Next.js Frontend → API Route (/api/analyze)
    → Inngest Job Queue → OpenAI API → Resume Insights
    → Prisma ORM → PostgreSQL (store + retrieve data)
```

* **Frontend**: Renders UI, collects resumes & job descriptions.
* **Backend**: Processes text via OpenAI, stores results in DB.
* **Inngest**: Runs long or queued AI jobs in background.
* **Prisma + PostgreSQL**: Manages user and analysis data.

---

## 🛠️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/resume-scan-AI.git
cd resume-scan-AI
```

### 2️⃣ Install Dependencies

```bash
npm install
# or
pnpm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file in the root and add:

```env
OPENAI_API_KEY=your_openai_api_key
DATABASE_URL=your_postgres_url
NEXTAUTH_SECRET=your_secret
INNGEST_API_KEY=your_inngest_key
```

*(If using BetterAuth or Clerk, add relevant keys here.)*

### 4️⃣ Run the Development Server

```bash
npm run dev
```

Now open: **[http://localhost:3000](http://localhost:3000)**

---

## 📦 Folder Structure

```
resume-scan-AI/
├── app/                # Next.js App Router pages
├── components/         # Reusable UI components
├── lib/                # Configs (Prisma, Auth, API)
├── inngest/            # Background tasks setup
├── prisma/             # Database schema
├── public/             # Static assets
├── styles/             # Global CSS
└── package.json

## 👨‍💻 Author

**Mohd Zafar**
Full-Stack & AI Developer | Building future-ready web applications

* 🌐 [Portfolio](https://your-portfolio-link)
* 🐙 [GitHub](https://github.com/MohdZafar22)
* 💼 [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 🛡️ License

This project is licensed under the **MIT License**.
You’re free to use, modify, and distribute this project with attribution.

---

## ⭐ Support

If you like this project, don’t forget to ⭐ the repository and share your feedback!

---

### ✨ “Turning resumes into insights — powered by AI.”
