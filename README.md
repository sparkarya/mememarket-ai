# 🎨 MemeMarket AI — Where Memes Meet AI & Cyberpunk ⚡

Welcome to MemeMarket AI — a futuristic platform where you don’t just view memes… you **create, trade, and trend** them. Built with a modern stack and powered by AI, this is a new kind of digital playground.

🌐 **Live Project:** [Visit MemeMarket AI](https://sparkarya.github.io/mememarket-ai/)

---

## 🧠 What It Does

MemeMarket AI is a **meme playground** for creators and viewers alike:
- ✨ AI Captioning: Let Gemini AI write meme captions for you.
- 🎭 Post Memes: Upload and share your creations.
- 📈 Vote System: Upvote your favorite ones.
- 🧾 Bidding Arena: Bid for meme ownership.
- 🏆 Live Leaderboard: Track top memes in real time.

---

## 🧰 Tools & Tech Behind the Scenes

| Layer        | Tech Used                  |
| ------------ | -------------------------- |
| Frontend     | React + Vite + TailwindCSS |
| Backend      | Node.js + Express          |
| Database     | Supabase (Postgres + Auth) |
| AI Power     | Google Gemini API          |
| Deployment   | GitHub Pages (Frontend)    |

---

## 🚀 Getting It Running (Local Setup)

```bash
# Clone this repo
git clone https://github.com/sparkarya/mememarket-ai.git
cd mememarket-ai

# Install frontend dependencies
cd frontend
npm install

# Create a `.env` file in frontend/ and backend/ with:
# VITE_SUPABASE_URL=
# VITE_SUPABASE_KEY=
# VITE_GEMINI_API_KEY=

# Run frontend
npm run dev
