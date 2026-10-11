# 🚀 DoppelGuard AI - Deployment Guide (Folder: byte)

**Built by Team Fantastic Five**  
*AI-Powered Social & App Monitoring Platform*

---

## ⚡ Option 1: 1-Click Deployment on Vercel (Recommended & Free)

1. Sign up or log into [Vercel.com](https://vercel.com).
2. Install Vercel CLI (optional):
   ```bash
   npm install -g vercel
   vercel
   ```
   OR drag and drop this entire `byte` folder directly on [Vercel's Dashboard](https://vercel.com/new).
3. Vercel automatically detects `vercel.json` and `index.html`.
4. Your application will be live instantly on a high-speed global CDN (e.g. `https://doppelguard.vercel.app`).

---

## ⚡ Option 2: Drag & Drop Deployment on Netlify (Free & Zero Setup)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the **`byte`** folder directly into the browser window.
3. Your site deploys in under 10 seconds with an instant live `https://<your-site>.netlify.app` URL!

---

## ⚡ Option 3: GitHub Pages Deployment (Free)

1. Initialize git inside this `byte` directory:
   ```bash
   git init
   git add .
   git commit -m "Deploy DoppelGuard AI by Fantastic Five"
   ```
2. Push to a new GitHub repository:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<your-username>/doppelguard-drp.git
   git push -u origin main
   ```
3. Go to **Repository Settings -> Pages -> Source**: Select **main branch / root**.
4. Live in ~60 seconds at `https://<your-username>.github.io/doppelguard-drp/`.

---

## ⚡ Option 4: Render / Railway / Node.js Cloud Server

1. Connect your repository or folder to [Render.com](https://render.com) or [Railway.app](https://railway.app).
2. Build Command: *(leave empty or `npm install`)*
3. Start Command: `node server.js`
4. Set Environment Variable: `PORT=3000` (automatically handled by `process.env.PORT`).

---

## ⚡ Option 5: Docker Container Deployment

1. Build container:
   ```bash
   docker build -t doppelguard-app .
   ```
2. Run container:
   ```bash
   docker run -d -p 3000:3000 doppelguard-app
   ```
3. Access at `http://localhost:3000`.

---

## 📁 What is in this `byte` Folder?

- `index.html`: Complete self-contained single-page platform (Threat Feed, AI Triage, Scanner, Domain Shield, Pitch Pack, Developed Team modal).
- `server.js`: Node.js server configured for both local and cloud production hosts.
- `vercel.json`: Pre-configured routing for Vercel.
- `netlify.toml` & `_redirects`: Pre-configured routing for Netlify.
- `Dockerfile`: Ready for Docker / AWS ECS / Google Cloud Run.
- `data/`: Structured JSON feeds for `team.json`, `terms.json`, `incidents.json`, `scanner_apps.json`, and `analytics.json`.
- `audit_requirements.js`: Automated compliance check (19/19 requirements pass).
- `test_babel.js`: Babel compilation validator.
