# StreamBox

A modern movie and TV show discovery platform built with Next.js, Firebase, and TMDB API.

## Features

- 🎬 Browse popular, trending movies & TV shows
- 🔍 Advanced search across movies, TV shows, and actors
- 👤 User authentication with Firebase
- 📋 Personal watchlist
- 🤖 AI-powered watchlist analysis (Gemini)
- 🌙 Dark/Light theme toggle
- 📱 Fully responsive design

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Next.js 14 | React framework |
| Firebase | Auth & Database |
| TMDB API | Movie & TV data |
| Tailwind CSS | Styling |
| TanStack Query | Data fetching |
| Gemini AI | Watchlist insights |

## Quick Start

1. **Clone & install**
   ```bash
   git clone <your-repo>
   cd streambox-main
   npm install
   ```

2. **Environment setup**
   ```bash
   cp .env.example .env.local
   ```
   Fill in your API keys in `.env.local` (TMDB, Firebase, Gemini)

3. **Run development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000)

## Environment Variables

| Variable | Description |
|----------|-------------|
| `TMDB_API_KEY` | TMDB API key |
| `NEXT_PUBLIC_FIREBASE_*` | Firebase config keys |
| `GEMINI_API_KEY` | Gemini AI API key |
| `NEXT_PUBLIC_APP_URL` | App URL (default: localhost:3000) |

## Deployment

Deploy easily on [Vercel](https://vercel.com):
1. Push to GitHub
2. Import repo on Vercel
3. Add environment variables
4. Deploy!

---

Built with ❤️ using Next.js & Firebase
