# 💼 AI Career Coach

**AI Career Coach** is a web app designed to help users boost their careers by analyzing resumes, offering personalized guidance, and simulating interview practice — powered by **Next.js**, **Clerk**, and **Google Gemini**.

---

## 🚀 Features

- 📄 Resume upload & analysis  
- 💡 Career and job advice  
- 🎤 Interview Q&A practice  
- ⚡ Fast, responsive, and modern UI  

---

## 🛠️ Tech Stack

- **Frontend**: Next.js, Tailwind CSS  
- **Backend**: Node.js, Prisma, Google Gemini api
- **Auth**: Clerk  
- **Database**: PostgreSQL (Neon or Docker)  

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Ishita282/career-coach.git
cd ai-career-coach
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up the Database

Push the schema to your PostgreSQL database:

```bash
npx prisma db push
```

### 4. Create a `.env` File

```env
# PostgreSQL Database
DATABASE_URL="postgresql://<username>:<password>@<host>:<port>/career_coach?schema=public"

# Clerk Authentication (https://dashboard.clerk.com/)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
CLERK_SECRET_KEY=<your-clerk-secret-key>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

# Gemini API (https://makersuite.google.com/app/apikey)
GEMINI_API_KEY=<your-gemini-api-key>
```

### 5. Run in Development Mode

```bash
npm run dev
```

### 6. For Production

```bash
npm start
```

---

## 📄 License

MIT License. Feel free to use, modify, and share.

---

## ✨ Contributions

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---