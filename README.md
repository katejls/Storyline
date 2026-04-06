# Storyline — AI Novel Experience

Live the story. Chat the character. An AI novel experience written for you.

## What is this?

Storyline is a hybrid AI story + companion chat app. Users pick a scenario (Billionaire Romance, Revenge, Reborn, Mafia, etc.), and an AI writes them into a personalized novel — chapter by chapter. Between chapters, they can chat with the love interest character in real-time.

## Deploy to Vercel

### Option 1: Vercel Dashboard (easiest)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) and sign up / log in
3. Click "Add New Project" → Import your GitHub repo
4. Vercel auto-detects Vite — just click **Deploy**
5. Done! You'll get a `.vercel.app` URL

### Option 2: Vercel CLI
```bash
npm install -g vercel
cd storyline
vercel
# Follow prompts, then:
vercel --prod
```

## Tech Stack
- **Frontend**: React + Vite
- **AI**: Anthropic Claude API (called from client)
- **Hosting**: Vercel
- **Styling**: Inline CSS (no dependencies)

## Monetization Plan
- Free tier: 1 chapter + 5 chat messages/day
- $4.99/week subscription: unlimited
- Target: 800 weekly subs = ~$200K/year
