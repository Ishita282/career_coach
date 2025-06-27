AI Career Coach

AI Career Coach is a web app that helps users improve their careers by analyzing resumes, giving personalized advice, and offering interview prep — powered by Next.js and OpenAI.
🚀 Features

    Resume upload & analysis

    Career and job advice

    Interview Q&A practice

    Fast and responsive UI

🛠️ Tech Stack

    Frontend: Next.js, Tailwind CSS

    Backend: Node.js, OpenAI API

📦 Setup

    git clone https://github.com/Ishita282/career-coach.git
    cd ai-career-coach
    npm install

Create a .env file:

```env
DATABASE_URL="postgresql://<db_usernanme>:<db_password>@<host>:<port>/career_coach?schema=public"


# get api kry from https://dashboard.clerk.com/last-active?path=api-keys
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<read above comment>
CLERK_SECRET_KEY=<read above comment>

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=<gemini api key>

# to be used in docker while development 
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres1111
```
Run the app:

npm start
