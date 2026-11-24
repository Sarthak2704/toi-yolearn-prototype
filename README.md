# TOI × YoLearn AI Student Learning Platform — Prototype & PRD

An interactive prototype and comprehensive Product Requirements Document (PRD) for the **The Times of India × YoLearn AI Student Learning Platform**.

---

## 🚀 Live Demo
- **Live Vercel URL:** [https://toi-yolearn-prototype.vercel.app](https://toi-yolearn-prototype.vercel.app)
- **Direct Local File:** Open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox). No build step required!

---

## 📦 What's Inside This Package

1. **`index.html`**
   - Self-contained, zero-dependency interactive web prototype.
   - Includes all 15 screens:
     - **Home / Dashboard (`#s-dashboard`):** Includes promotional enroll banner with live trial progress meter and CTA to Economic Times Masterclass.
     - **My Courses (`#s-courses`):** Dual course cards displaying the purchased *TOI AI for Students Masterclass (Batch 7)* alongside the legacy trial course.
     - **Course Detail (`#s-course`):** 6 dedicated tabs:
       1. `All`: Everything in it (all modules, pre-read PDFs, additional resources, safety & security, certificate status).
       2. `Class`: Only class video lectures & interactive AI tutor lessons (Modules 1–5).
       3. `Pre Read Material`: Only preparatory reading materials & architecture primers PDF list.
       4. `Additional Resource`: Supplementary developer kits, cheatsheets, and comparison matrices PDF list.
       5. `Safety and Security`: Responsible AI, hallucination guide, student PII privacy, and academic integrity policies.
       6. `Certificate`: Unlock criteria and interactive simulation toggle (`✨ Simulate 100% Completion`) for the co-branded certificate.
     - **Unified PDF Reader with Grounded AI Chat (`#s-prereading`):** Split-view document viewer with interactive Pragya AI chat.
     - **Live AI Tutor with Canvas Sketchpad (`#s-tutor`):** Interactive multimodal tutor with HTML5 canvas drawing tools.
     - **16 AI Tools Sandbox (`#s-tools`):** Visual generator, quiz maker, flashcard builder, flowchart generator, etc.
     - **AI BootCamp Practice Engine (`#s-practice`):** Dedicated adaptive testing for AI BootCamp topics.
     - **Billing & Token Management (`#s-billing`):** 20-token exploration mode, paywall triggers, and upgrade flows.
2. **`PRD_TOI_YoLearn_AI_Learning_Platform.md`**
   - Full Product Requirements Document covering architectural flow, token gating, scheduled course unlocking, data schemas, API contracts, security & ethics guidelines, and QA acceptance criteria.
3. **`server.js` & `package.json`**
   - Optional local Node.js static server (`npm install && npm start`).
4. **`vercel.json`**
   - One-click deployment configuration for Vercel.

---

## 💻 How to Run Locally

### Option 1: Direct Browser (Instant)
Double-click `index.html` or drag it into any web browser.

### Option 2: Local HTTP Server (Node.js)
```bash
npm start
# Opens at http://localhost:3000
```

### Option 3: Python Simple Server
```bash
python -m http.server 3000
# Opens at http://localhost:3000
```
