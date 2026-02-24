# Noor — Quran Knowledge Explorer

An interactive, visual explorer of the Holy Quran built as a single HTML file.

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Option A — Deploy via GitHub (Recommended)

1. **Create a GitHub account** at github.com if you don't have one

2. **Create a new repository**
   - Click the `+` icon → "New repository"
   - Name it `noor` or `quran-explorer`
   - Set it to Public
   - Click "Create repository"

3. **Upload your files**
   - Click "uploading an existing file"
   - Drag and drop both `index.html` and `vercel.json`
   - Click "Commit changes"

4. **Connect to Vercel**
   - Go to vercel.com → Sign up with your GitHub account
   - Click "Add New Project"
   - Import your `noor` repository
   - Click "Deploy" — no settings need to change!

5. **Your site is live** at `your-project.vercel.app` 🎉

---

### Option B — Deploy via Vercel CLI (Advanced)

```bash
npm install -g vercel
vercel login
vercel --prod
```

---

## 🌐 Add a Custom Domain on Vercel

1. In your Vercel dashboard → select your project
2. Go to **Settings → Domains**
3. Type your domain (e.g. `noorilm.com`) → Add
4. Vercel will show you DNS records to add
5. Go to your domain registrar (GoDaddy, Namecheap, etc.)
6. Add the DNS records Vercel provides
7. Wait 10–30 minutes → your domain is live with HTTPS ✅

---

## 📊 Set Up Google Analytics (Free)

1. Go to analytics.google.com → Create account
2. Create a new Property → get your **Measurement ID** (looks like `G-XXXXXXXXXX`)
3. Open `index.html` → find `G-XXXXXXXXXX` (appears twice)
4. Replace both with your real Measurement ID
5. Redeploy

---

## 📁 File Structure

```
noor/
├── index.html      ← The entire website (all-in-one)
└── vercel.json     ← Vercel deployment config
```

---

## ✨ Features

- 114 Surahs with Arabic names, verse counts, Makki/Madani tags + live search
- 30 Juzz with start and end references
- 25 Prophets mentioned in the Quran
- 5 Pillars of Islam
- 12 animated overview statistics
- Mobile responsive
- Dark Islamic aesthetic with gold accents

---

Built with HTML, CSS & vanilla JavaScript. No frameworks, no dependencies.
