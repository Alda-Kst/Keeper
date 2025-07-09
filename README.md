# 📒 Keeper App

A simple and elegant note-taking app built with **React**, **Vite**, and **Material UI**, inspired by Google Keep. Create, view, and delete notes in a responsive, fast UI.

![Keeper App Screenshot](https://user-images.githubusercontent.com/placeholder/keeper-screenshot.png)


---

## 🚀 Live Demo

🔗 [https://alda-kst.github.io/Keeper](https://alda-kst.github.io/Keeper)

---

## 🛠 Tech Stack

- ⚛️ React 18
- ⚡ Vite
- 🎨 Material UI (MUI v5)
- 💅 Emotion for styling
- 📄 GitHub Pages for deployment

---

## ✨ Features

- ✅ Add and delete notes
- 📝 Clean Material UI interface
- 💡 Responsive layout
- ⚡ Instant loading with Vite
- 🚀 Hosted with GitHub Pages

---

## 📦 Installation

1. **Clone the repo:**

```bash
git clone https://github.com/alda-kst/Keeper.git
cd Keeper
2. **Install dependencies:**
   npm install --legacy-peer-deps
3. **Run locally:**
   npm run dev
4. **Build for production:**
   npm run build
##  Deployment (GitHub Pages)
1. Make sure your vite.config.js has the correct base path:
  // vite.config.js
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
  base: '/Keeper/', // must match your repo name
});
2. Ensure your package.json contains this:
  "homepage": "https://alda-kst.github.io/Keeper"
3. **Deploy:**
   npm run deploy


 


