# 🌸 Rakshita Jolad — Portfolio Website

A personal portfolio website built with HTML, CSS, and JavaScript.
Feedback form is powered by **Supabase**.
Hosted on **Render** (Static Site).

---

## 📁 Project Structure

```
portfolio/
├── index.html                        ← Main website file
├── README.md                         ← This file
│
├── images/                           ← PUT ALL YOUR IMAGES HERE
│   ├── Profile pic.png
│   ├── Front and web development.png
│   ├── Digital Nasscom.png
│   ├── AWS RJ.png
│   ├── SIH ideathin.jpeg
│   ├── SIH ideathin image.jpeg
│   ├── cloud innovators socity.jpeg
│   ├── Cloud innovators socity image.jpeg
│   ├── synchrotech.jpeg
│   └── rakshita.jpeg
│
└── .github/
    └── workflows/
        └── deploy.yml                ← GitHub Actions CI/CD pipeline
```

---

## 🚀 How to Deploy

### 1. Push to GitHub
Upload all files to a GitHub repository (Public).

### 2. Deploy on Render
- Go to render.com → New → Static Site
- Connect your GitHub repo
- Build Command: *(leave blank)*
- Publish Directory: `.`

### 3. Add GitHub Secret
- Render → Settings → Deploy Hook → Copy URL
- GitHub → Settings → Secrets → New secret
- Name: `RENDER_DEPLOY_HOOK_URL`
- Value: paste the Render deploy hook URL

### 4. Manual Deploy
- GitHub → Actions tab → "Deploy to Render" → Run workflow

---

## 🔗 Tech Stack
- HTML / CSS / JavaScript
- Supabase (feedback form)
- Render (hosting)
- GitHub Actions (manual CI/CD)
