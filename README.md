# 🚀 Resume Scan AI

<p align="center">
  <b>📄 Scan • 🤖 Analyze • 📊 Improve</b><br/>
  AI-powered resume analyzer to boost your job chances
</p>

---

## 📌 Overview

✨ **Resume Scan AI** is a smart web application that helps users improve their resumes using **AI-driven insights**.

With this tool, you can:

* 🔐 Securely sign up & sign in
* 📄 Upload your resume
* 🤖 Scan resumes using AI
* 📊 Get detailed analysis & feedback
* 🗑️ Manage and delete past scans

---

## ✨ Features

* 🔑 Authentication system (Sign Up / Sign In)
* 📄 Resume upload & processing
* 🤖 AI-powered resume analysis
* 📊 ATS-style insights & feedback
* 🗂️ Manage scan history
* ⚡ Fast, clean, and responsive UI

---

## 🧩 Tech Architecture

| 🏗️ Component      | ⚙️ Technology Used      | 📌 Purpose                          |
| ------------------ | ----------------------- | ----------------------------------- |
| 🎨 Frontend        | Next.js 15, React       | Build UI & handle user interactions |
| 🎨 Styling         | Tailwind CSS, Shadcn/ui | Modern, responsive design           |
| 🔗 API Layer       | Next.js API Routes      | Handle client-server communication  |
| 🔐 Authentication  | BetterAuth              | Secure user authentication          |
| 🤖 AI Engine       | OpenAI API              | Resume analysis & insights          |
| ⚙️ Background Jobs | Inngest                 | Async resume processing             |
| 🗄️ Database       | PostgreSQL              | Store user data & results           |
| 🔄 ORM             | Prisma ORM              | Database query management           |

---

## 📸 Screenshots

### 🏠 Dashboard
![Dashboard](Screenshot(18).png)

### 📄 Resume Upload
![Upload](Screenshot(19).png)

### 📊 Analysis Result
![Analysis](Screenshot(21).png)

### 🧠 AI Feedback
![Feedback](Screenshot(23).png)

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash id="c9r2gs"
git clone https://github.com/saidMounaim/resume-scan-AI.git
cd resume-scan-AI
```

### 2️⃣ Install Dependencies

```bash id="3opx8j"
npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file:

```env id="m21c0c"
DATABASE_URL=""
BETTER_AUTH_BASE_URL=""
OPENAI_API_KEY=""
INNGEST_EVENT_KEY=""
```

---

## 🚀 Run the App

```bash id="m8pztz"
npm run dev
```

🌐 Open in browser:
👉 http://localhost:3000

---

## 🏗️ Application Flow

1️⃣ 🔐 User signs in
2️⃣ 📄 Uploads resume
3️⃣ ⚙️ Processed via Inngest
4️⃣ 🤖 AI analyzes content
5️⃣ 📊 Results stored in database
6️⃣ 📈 Display insights on dashboard

---

## 🛠️ Built With

* ⚡ Next.js
* 🎨 Tailwind CSS
* 🟦 TypeScript
* 🧩 Shadcn/ui
* 🔐 BetterAuth
* 🤖 OpenAI
* ⚙️ Inngest
  
---

## ⭐ Support

If you like this project:

👉 Give it a ⭐ on GitHub
👉 Share it with others

---

<p align="center">
  💬 <i>"Your resume is your first impression. Make it powerful with AI."</i>
</p>
