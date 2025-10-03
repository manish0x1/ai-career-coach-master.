

```markdown
# 🧠 AI Career Coach

An intelligent, full-stack web application that helps users navigate career decisions using Gemini AI. Built with Next.js, Tailwind CSS, Prisma ORM, and Shadcn UI for a modern, responsive experience.

## 🚀 Tech Stack

| Technology     | Purpose                                      |
|----------------|----------------------------------------------|
| Next.js        | React-based framework for SSR & routing      |
| Tailwind CSS   | Utility-first styling                        |
| Gemini AI      | Conversational AI for career guidance        |
| Prisma         | ORM for PostgreSQL database management       |
| Shadcn UI      | Accessible, customizable UI components       |

## 📦 Features

- ✨ AI-powered career advice using Gemini
- 🧭 Dynamic questionnaire for career profiling
- 📊 Personalized dashboard with insights
- 🔍 Job role suggestions based on user input
- 🗂️ Saved recommendations and history tracking
- 🎨 Responsive design with Tailwind & Shadcn UI

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/ai-career-coach.git
cd ai-career-coach
npm install
```

## 🧪 Development

```bash
npm run dev
```

Visit `http://localhost:3000` to view the app.

## 🗃️ Database Setup

Ensure PostgreSQL is running locally or remotely.

```bash
npx prisma init
# Configure DATABASE_URL in .env
npx prisma migrate dev --name init
```

## 🔑 Environment Variables

Create a `.env` file with:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/yourdb
GEMINI_API_KEY=your_gemini_api_key
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

## 🧩 Folder Structure

```
├── prisma/             # Prisma schema & migrations
├── src/
│   ├── app/            # Next.js routing
│   ├── components/     # Reusable UI components
│   ├── lib/            # Utility functions
│   ├── pages/          # Page-level components
│   └── styles/         # Tailwind config
```

## 🧠 AI Integration

Gemini AI is used to:

- Interpret user responses
- Generate career suggestions
- Provide motivational feedback

## 📐 UI/UX

- Built with Shadcn UI for accessibility
- Tailwind CSS ensures mobile-first responsiveness
- Dark mode support (optional)

## 📈 Future Enhancements

- 🔐 Auth with NextAuth.js
- 🧭 Career roadmap generator
- 📬 Email notifications
- 🌐 Multi-language support

## 🤝 Contributing




