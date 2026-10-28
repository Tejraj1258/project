# LearnEase — Interactive & Accessible Learning Platform

> **Live Production Website:** [https://learnease-smoky.vercel.app](https://learnease-smoky.vercel.app)  
> **Direct Vercel Deployment:** [https://learnease-661fc54vo-sailors3.vercel.app](https://learnease-661fc54vo-sailors3.vercel.app)  
> **Vercel Project Dashboard:** [https://vercel.com/sailors3/learnease](https://vercel.com/sailors3/learnease/37L5jqVxQNnw5zpYCEmYsLSW9h61)

---

## 🌟 About LearnEase

**LearnEase** is a competition-ready educational web platform built to help students develop reading skills, master phonics, understand educational materials, and study independently at their own pace.

It is designed with two distinct, equal journeys:
- **Journey A (Learn to Read):** 7 progressive levels from A-Z letter recognition, phonics digraphs, animated CVC sound blending, syllable reading, sentence building, paragraph karaoke read-along, and comprehension quizzes.
- **Journey B (Help Me Study):** Converts study notes, homework text, and presets into simplified plain-language explanations, audio lessons, visual concept mind-maps, retention quizzes, and flashcards.

---

## 🚀 Quick Start (Running Locally)

The project is built with **100% Vanilla HTML5, CSS3, and JavaScript** with zero external runtime build tools or dependencies.

```powershell
# Navigate to the project directory
cd d:/Learnease

# Start local server with Python
python -m http.server 8080

# Or start with Node / npx
npx serve .
```

Open your browser at `http://localhost:8080/index.html`.

---

## 📖 Developer & Code Documentation

A comprehensive, line-by-line developer guide has been prepared for the team:

👉 **[Read the Full Developer & Architecture Guide (DEVELOPER_GUIDE.md)](./DEVELOPER_GUIDE.md)**

It covers:
- Data models (`ALPHABET_DATA`, `PHONICS_PATTERNS`, `BLEND_WORDS`, `STORIES_DATA`, `STUDY_PRESETS`)
- Audio synthesizer engine (`SoundEngine` with Web Audio API + SpeechSynthesis)
- State management and `localStorage` persistence
- SPA view routing and tab switching
- Step-by-step recipes on how to add new words, new stories, new study presets, and customize themes.

---

## 🚢 Deploying Updates to Vercel

To deploy future updates to the live Vercel production URL:

```powershell
npx vercel --prod --yes
```

---

*© LearnEase EdTech Platform. Built for inclusive, accessible, and joyful learning.*
