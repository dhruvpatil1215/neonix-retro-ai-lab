# 🖼️ NEONIX — Retro AI Image Lab v2.0

**NEONIX** is a **fully client-side Retro-Futuristic AI Image Generator** inspired by **80s/90s CRT computer systems**, powered by **Pollinations.ai**.  
It blends **cyberpunk visuals**, **advanced prompt controls**, **local galleries**, and **multi-method downloads** — all inside a **single HTML file**.

> *1984 aesthetics, powered by modern AI.*

---

## 🚀 Features

### 🎨 AI Image Generation
- Text-to-Image AI generation
- Multiple **art styles**  
  *(Cyberpunk, Pixel Art, Synthwave, Anime, Cinematic, Dark Fantasy, etc.)*
- Adjustable **Creativity Level**
- Multiple **Aspect Ratios**
- **Random Prompt** & **Remix Prompt** generator

---

### 🖥️ Retro UI / UX
- CRT scanlines & glitch animations
- Neon cyberpunk color palette
- Binary rain background
- Retro sliders, buttons & selectors
- Fully responsive layout

---

### 🖼️ Image Management
- Current image preview
- Local **Gallery (last 50 images)**
- **Saved Images** (persistent via `localStorage`)
- Thumbnail previews
- Image metadata (prompt, style, ratio, time)

---

### ⬇️ Download System (CORS-Safe)
- Direct download (Blob)
- Open image in new tab
- Copy image URL
- Canvas-based save (CORS fallback)

---

### ⚙️ Advanced Tools
- Regenerate image
- Create variations
- Simulated upscale
- Share image (Web Share API)
- Effects placeholder system

---

## 🧠 Tech Stack

| Technology | Purpose |
|----------|---------|
| **HTML5** | App structure |
| **CSS3** | Retro UI, animations |
| **JavaScript (Vanilla)** | Logic & state |
| **Pollinations.ai API** | AI image generation |
| **Font Awesome** | Icons |
| **LocalStorage** | Gallery & stats |

---

## 🔗 API Used

### Pollinations Image API
https://image.pollinations.ai/prompt/{PROMPT}


**Parameters**
- `width`
- `height`
- `seed`
- `nofeed=true`

---

## 📦 Installation

### 1️⃣ Clone or Download
```bash
git clone https://github.com/dhruvpatil1215/neonix-retro-ai-lab.git
