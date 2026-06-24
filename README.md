# OTO Flashcards - Otolaryngology Board Review

An interactive flashcard app for **Otolaryngology–Head and Neck Surgery: Rapid Clinical and Board Review**. Features **spaced repetition** (SM-2 algorithm) to maximize retention — works offline on **iPhone, iPad, Mac, and any browser**.

## Features

- ✅ **3,821 Q&A flashcards** covering all 13 chapters of the board review book
- ✅ **SM-2 Spaced Repetition** — the same algorithm used by Anki
- ✅ **Organized by chapters**: Pediatric ENT, Rhinology, Laryngology, Otology, Head & Neck Oncology, Facial Plastics, Trauma, Salivary, Endocrine, etc.
- ✅ **PWA (Progressive Web App)** — install on your iPhone/iPad/Mac home screen
- ✅ **Works offline** — study anywhere, no internet needed
- ✅ **Dark mode** for comfortable night studying
- ✅ **Search** through all 3,800+ questions instantly
- ✅ **Study statistics** to track your progress
- ✅ **Keyboard shortcuts** (Space/Enter to reveal, 1-4 to rate)

## 🌐 Live App
**https://drducphan148-svg.github.io/oto-flashcards/**

## Quick Start

### Option 1: Use directly (no install needed)
Open **[https://drducphan148-svg.github.io/oto-flashcards/](https://drducphan148-svg.github.io/oto-flashcards/)** in any browser.

### Option 2: Install as PWA (recommended for iPhone/iPad/Mac)

**On iPhone/iPad (Safari):**
1. Open the app in Safari
2. Tap the **Share** button (bottom toolbar)
3. Scroll down and tap **Add to Home Screen**
4. Name it "OTO Flashcards" and tap **Add**
5. Open from your home screen — it works offline!

**On Mac (Chrome/Safari):**
- Chrome: Click the install icon (➕) in the URL bar
- Safari: File → Add to Dock

### Option 3: Local development
```bash
python3 -m http.server 8080
# Open http://localhost:8080
```

## Spaced Repetition System

The app uses the **SM-2 algorithm** (SuperMemo 2), the same proven algorithm behind Anki:

| Rating | Meaning | Effect |
|--------|---------|--------|
| 😵 Again | Complete forget | Reset interval |
| 🤔 Hard | Recalled with difficulty | Smaller interval increase |
| ✅ Good | Correct recall | Standard interval |
| ⭐ Easy | Instant recall | Max interval increase |

Cards you struggle with appear more frequently; cards you know well appear less often.

## Book Reference

Carlson ML, Van Abel KM, Archibald DJ, Price DL. *Otolaryngology–Head and Neck Surgery: Rapid Clinical and Board Review*. Thieme; 2015.

## Tech Stack

- Pure HTML/CSS/JavaScript (zero dependencies)
- PWA with Service Worker for offline support
- SM-2 spaced repetition algorithm
- localStorage for progress persistence
- GitHub Pages ready

## License

Educational use. The flashcard content is derived from the referenced textbook — all rights to the original content belong to the authors and publisher.
