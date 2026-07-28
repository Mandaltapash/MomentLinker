# MomentLinker 💌🍿✨

> **Create ultra-cute, interactive date & proposal invitations for your friends, partner, or crush with evasive NO button physics, GSAP animations, and instant shareable links!**

![MomentLinker Banner](https://img.shields.io/badge/Status-Live-ff477e?style=for-the-badge&logo=github)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-10b981?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/License-MIT-8b5cf6?style=for-the-badge)

---

## 🌐 Live Demo & Studio

- 🚀 **Live Web App**: [https://mandaltapash.github.io/MomentLinker/](https://mandaltapash.github.io/MomentLinker/)
- ☕ **Sample Shared Card Demo**: [Coffee Date for Simran from Rahul](https://mandaltapash.github.io/MomentLinker/index.html?type=coffee&to=Simran&from=Rahul&note=Coffee+and+treat+on+me!&theme=pink)

---

## ✨ Features

- 💌 **5 Interactive Occasion Categories**:
  - 🍿 **Movie Date**: *"Will you go on a Movie Date with me?"*
  - ☕ **Coffee & Snacks Date**: *"Will you grab Coffee & Snacks with me?"*
  - 💖 **Valentine / Proposal**: *"Will you be my Valentine?"*
  - 🍝 **Dinner Date**: *"Will you go out for Dinner with me?"*
  - 🥳 **Weekend Hangout**: *"Will you hang out with me this weekend?"*

- 😜 **GSAP Evasive NO Button Physics**:
  - Proximity cursor detection (< 90px).
  - The NO button smoothly teleports, jumps, rotates, bounces, shrinks, and dodges away using GSAP 3.x with cubic-bezier fallback engine.

- 💬 **Dynamic Sender Name Meme Popups**:
  - Toasts display personalized fun messages like `"[Sender Name] is crying 😭"` and `"[Sender Name]'s heart is breaking 💔"`.

- 🎭 **7 Progressive Reaction Screens**:
  - Cycles through cute vector SVG stickers: *Puss-in-Boots Kitten 🥺, Sad Panda 😭, Crying Teddy Bear 💔, Popcorn Puppy 🥹, Quacking Duck 🦆, Grumpy Cat 😾, and Hugging Ghost 🥺*.

- 🎉 **YES Celebration & VIP Date Pass Generator**:
  - Full-screen confetti burst, fireworks, floating heart shower, and happy synthesized melody via Web Audio API.
  - Interactive Date Selector (Date picker, time slot, popcorn/snack combo) personalized with the sender & recipient names.

- 🎨 **4 iOS Glassmorphic Themes**:
  - 🌸 *Soft Pink Romance*
  - 🌌 *Midnight Neon*
  - 🌅 *Pastel Sunset*
  - 🪻 *Lavender Dreams*

- 🔗 **Zero-Backend Shareable Link System**:
  - Pure client-side URL query parameter encoding (`URLSearchParams`).
  - 1-Click Copy Link and direct WhatsApp sharing integration.

---

## 🚀 How to Deploy

### Deploying to Vercel (1-Click)
1. Go to [Vercel Dashboard](https://vercel.com/new).
2. Select **Import Git Repository** and choose `Mandaltapash/MomentLinker`.
3. Click **Deploy**! (No build settings or commands required).

### Deploying to Render
1. Go to [Render Dashboard](https://dashboard.render.com/).
2. Create a new **Static Site**.
3. Connect `Mandaltapash/MomentLinker` and set Publish Directory to `./`.

---

## 🛠️ Tech Stack

- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Animations**: GSAP 3.12.5 (with pure CSS3 fallback engine)
- **Visuals**: Vector Animated SVGs, HTML5 Canvas Particle System
- **Audio**: Web Audio API Synthesizer (No external audio file dependencies)

---

## 📄 License

Distributed under the MIT License. Built with ❤️ for fun interactions between friends & partners.
