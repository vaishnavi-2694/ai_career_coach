# 🎓 AI Career Coach

An AI-powered career guidance application that helps users choose the right career path using Google Gemini AI, Clerk authentication, and a clean Next.js frontend. Users can interact with a chatbot to get tailored advice for their goals.

## 🚀 Features

- ✨ AI Career Coaching using Google Gemini API
- 🔐 User Authentication with Clerk
- 🧠 Chat-based interface for career Q&A
- 📊 Personalized dashboard and results
- 🌐 Built with Next.js, Tailwind CSS, Prisma, and PostgreSQL

---

## 🧩 Tech Stack

- **Frontend:** Next.js 14, Tailwind CSS
- **Backend:** API routes (Next.js)
- **Authentication:** Clerk
- **Database:** PostgreSQL with Prisma ORM
- **AI:** Google Gemini API (Generative AI)

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/vaishnavi-2694/ai-career-coach.git
cd ai-career-coach
```


### 2. Install Dependencies
npm install


### 3. Set Up Environment Variables

DATABASE_URL=your_postgresql_url
GEMINI_API_KEY=your_google_gemini_api_key
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP=/dashboard

### 4. Generate Prisma Client

npx prisma generate

### 5. Run the Server

npm run dev
The app will be running on http://localhost:3000


