# Alcel Montecino — Portfolio

Organizational Web Developer Portfolio — PHP, WordPress, CMS, Events, Giving, Member Portals.

## Local Development

```bash
npm install
npm start
# Open http://localhost:3000
```

## Deploy to Render

1. Push this repo to GitHub
2. Go to [render.com](https://render.com) → New → Web Service
3. Connect your GitHub repo
4. Use these settings:
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
   - **Environment:** Node
5. Click **Deploy** — your site will be live in ~2 minutes

## Project Structure

```
portfolio-site/
├── public/
│   └── index.html      ← Your portfolio page
├── server.js           ← Express server (serves static files)
├── package.json
├── .gitignore
└── README.md
```
