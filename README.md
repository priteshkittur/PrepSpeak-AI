# Prepwise – AI Interview Preparation Platform

Prepwise is a web application that helps users practise job interviews with an AI voice assistant. Users can create mock interviews based on a job role, experience level and tech stack, attend the interview by speaking with the AI, and get feedback on their answers.

I built this project to learn how to work with Next.js, Firebase and AI APIs, and to understand how voice-based AI features can be added to a web application.

## Features

- **User authentication:** Sign up and sign in using email and password.
- **Create mock interviews:** Generate interview questions based on the selected role, experience level and technologies.
- **AI voice interviews:** Practise answering questions through a voice assistant powered by Vapi.
- **AI-generated feedback:** Get feedback on communication, technical knowledge, problem-solving and other interview skills.
- **Interview dashboard:** View and manage your interviews.
- **Responsive design:** Use the application on different screen sizes.

## Tech Stack

- **Frontend and backend:** Next.js
- **Styling:** Tailwind CSS
- **Authentication and database:** Firebase
- **Voice AI:** Vapi
- **AI question generation and feedback:** Google Gemini
- **UI components:** shadcn/ui
- **Validation:** Zod

## Getting Started

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)
- npm (comes with Node.js)

### 1. Clone the repository

```bash
git clone https://github.com/adrianhajdin/ai_mock_interviews.git
cd ai_mock_interviews
```

### 2. Install dependencies

```bash
npm install
```

### 3. Add environment variables

Create a file named `.env.local` in the root directory and add the following variables:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```

Add your own credentials from [Firebase](https://firebase.google.com/), [Vapi](https://vapi.ai/) and Google AI Studio.

**Important:** Do not upload your `.env.local` file or private credentials to GitHub.

### 4. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## What I Learned

While working on this project, I got practical experience with:

- Building pages and application features using Next.js.
- Connecting Firebase for authentication and data storage.
- Integrating third-party AI services into a web application.
- Using a voice assistant for an interactive interview experience.
- Working with API routes, environment variables and reusable UI components.
- Building a responsive interface with Tailwind CSS.

## Project Structure

The project is organised into pages, reusable components, API routes, and utility files. Some important areas include:

- `app/` – application pages and API routes.
- `components/` – reusable UI components.
- `lib/` – helper functions and application actions.
- `constants/` – shared constants and configuration data.

## Future Improvements

Some things I would like to improve or add:

- More interview categories and job roles.
- Better tracking of interview progress over time.
- More detailed feedback with suggestions for improvement.
- Additional UI improvements based on user feedback.

---

_This is a learning project, and I plan to keep improving it as I learn more about full-stack development and AI integration._
