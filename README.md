# 📚 Book Marketing Hub

A professional social media marketing calendar site for two book clients — built as a static HTML project, deployable on Vercel in one click.

---

## 📁 Project Structure

```
book-marketing-hub/
├── index.html           ← Home page (links to both clients)
├── pooja-and-phil.html  ← Client 1: Bansi Pattni (Pre-Launch)
├── drum-earth.html      ← Client 2: A.J. Hugo Parker (Published)
├── vercel.json          ← Vercel routing config (clean URLs)
└── README.md
```

---

## 🌐 Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Landing page with both client cards |
| Pooja & Phil | `pooja-and-phil.html` | Pre-launch social media calendar — Bansi Pattni |
| Drum Earth Trilogy | `drum-earth.html` | Published book marketing calendar — A.J. Hugo Parker |

---

## 🚀 Deploy to Vercel

### Option 1 — GitHub + Vercel (Recommended)

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your GitHub repository
4. Vercel auto-detects it as a static site — no configuration needed
5. Click **Deploy**

Your live URLs will be:
- `https://your-project.vercel.app/` → Home
- `https://your-project.vercel.app/pooja-and-phil` → Pooja & Phil
- `https://your-project.vercel.app/drum-earth` → Drum Earth Trilogy

### Option 2 — Drag & Drop on Vercel

1. Go to [vercel.com](https://vercel.com)
2. Drag this entire folder into the Vercel dashboard
3. Done — live in seconds

---

## 👥 Clients

### Client 1 — Pooja & Phil
- **Author:** Bansi Pattni
- **Status:** Pre-Launch
- **Strategy:** Build audience before launch — 12 posts over 4 weeks
- **Platforms:** Facebook, Instagram, BookTok
- **Goal:** Grow following, build anticipation, tease story and characters

### Client 2 — Drum Earth Trilogy
- **Author:** A.J. Hugo Parker
- **Publisher:** Drum Earth Publishing
- **Status:** Published — Live on Amazon
- **Strategy:** Drive sales, generate reviews, build community — 12 posts over 4 weeks
- **Platforms:** Facebook, Instagram, BookTok, Amazon, Goodreads
- **Goal:** Amazon reviews, discoverability, reader community

---

## ✏️ Editing Captions

All captions are inside the HTML files. To edit:
1. Open the relevant `.html` file in any text editor
2. Find the caption inside `<div class="caption-box">` tags
3. Edit and save
4. Re-upload / push to GitHub to update the live site

---

## 🛠 Tech Stack

- Pure HTML, CSS, JavaScript — no frameworks, no build step
- Google Fonts (Cormorant Garamond, Cinzel, DM Sans, Crimson Pro)
- Fully responsive — works on mobile and desktop
- Zero dependencies — works offline too

---

*Built for professional book marketing. All captions are drafts — review before publishing.*
