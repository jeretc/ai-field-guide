# AI Landscape Field Guide

A plain English reference guide to the AI landscape for beginners — creatives, business owners, students, and anyone trying to make sense of it all. No jargon, no fluff. Everything in one place.

**Live site:** [ai-field-guide.pages.dev](https://ai-field-guide.pages.dev)

---

## What it covers

- **Core Concepts** — What an LLM actually is, what a model is, open source vs closed, APIs explained simply
- **How It Works** — A plain English walkthrough of what happens between pressing Send and getting a response
- **Start Here** — Goal-based recommendations for beginners (just want to chat, generate images, run privately, etc.)
- **Terminology Decoder** — 16 terms you will encounter, decoded without the technical noise
- **Model Reference Table** — 58 AI models across 9 categories, filterable, with access and availability info
- **The Honest Takeaway** — What actually matters once you cut through all the hype

---

## Built with

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step.

- Apple-inspired design system with light and dark mode
- Fully responsive, mobile-first layout
- Filter and search across 58 models by category
- Zero external libraries

---

## Deploy

This is a single `index.html` file. Drop it anywhere that serves static files.

**Cloudflare Pages (recommended)**

1. Go to Cloudflare Pages dashboard
2. Create new project, choose Direct Upload
3. Upload `index.html`
4. Done — live at `your-project.pages.dev`

**Other options**

| Platform | Method |
|---|---|
| Vercel | Drag and drop or `vercel deploy` |
| Netlify | Drag and drop into Netlify dashboard |
| GitHub Pages | Push to repo, enable Pages in settings |

---

## Customising

All content is in the HTML file. The model data lives in a single `MODELS` array in the script section at the bottom — easy to add, remove, or update entries.

```js
{ 
  name: "Model Name", 
  maker: "Company", 
  cat: "Frontier LLM",     // see categories below
  desc: "What it does", 
  access: "Free + Paid API", 
  open: "No", 
  local: "No" 
}
```

**Categories:** `Frontier LLM`, `Open-Source LLM`, `Multimodal`, `Reasoning`, `Coding`, `Image Gen`, `Audio/Speech`, `Embedding`, `Local Runner`

---

## Project

Part of the personal portfolio of [Jeret Christopher](https://jeretchristopher.com) — web designer, musician, and author based in Malaysia.

- Portfolio: [jeretchristopher.com](https://jeretchristopher.com)
- Novella: [theheavyshadow.com](https://theheavyshadow.com)
- TikTok: [@paul_depuis](https://tiktok.com/@paul_depuis)
- Instagram: [@jeretc](https://instagram.com/jeretc)

---

*Snapshot: April 2026. This space moves fast.*
