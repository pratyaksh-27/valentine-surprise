# 🌹 Valentine's Day Surprise Webpage

A personalized, interactive, and mobile-responsive webpage created to surprise my wife on **Propose Day**. This project uses modern web technologies to create a storytelling experience that leads up to the big question: *"Will you be my Valentine?"*

## ✨ Features

### 1. 🎵 Immersive Intro
- **Music Overlay:** A "Click to Open" overlay ensures audio plays automatically (bypassing browser autoplay policies).
- **Audio:** Plays a romantic background track (`song.mp3`) continuously.

### 2. ⏳ "Together Forever" Timer
- A real-time JavaScript counter that calculates the exact duration of the relationship (Years, Days, Hours, Minutes, Seconds) starting from a specific date.

### 3. 📸 Memory Lane (Scroll Experience)
- **Polaroid Style Gallery:** Photos are styled like realistic Polaroids with a "tape" effect and drop shadows.
- **Scroll Animations:** Uses [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) for smooth fade-in and slide-in effects as the user scrolls.
- **Mobile Responsive:** Stacks vertically on mobile devices for better readability.

### 4. 💌 The "Runaway" Button Logic
- **Gamification:** The "No" button is unclickable.
- **Phase 1 (Guilt Trip):** Hovering over "No" changes the text to playful messages ("Are you sure?", "Don't break my heart!").
- **Phase 2 (The Chase):** After 5 attempts, the button actively runs away from the cursor using random coordinate math, making it impossible to click.

### 5. ☁️ Floating Photo Flashback
- When the user reaches the final question, a script dynamically spawns floating, semi-transparent photos in the background to create a dreamy atmosphere.

### 6. 🎉 The Grand Finale (Success State)
- **Typewriter Effect:** The final question is typed out character-by-character.
- **Heart Explosion:** Uses [Canvas Confetti](https://github.com/catdad/canvas-confetti) to blast custom heart-shaped SVG confetti upon clicking "Yes".
- **The Golden Ticket:** A premium-styled "Date Night Ticket" slides up from the bottom as the final reward, customized with the date and destination.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structure.
- **CSS3:** Glassmorphism UI, CSS Variables, Flexbox, Keyframe Animations.
- **JavaScript (ES6):** Logic for the timer, interactive buttons, typewriter effect, and confetti rendering.
- **Libraries:**
  - `AOS.js` (Scroll Animations)
  - `canvas-confetti` (Confetti Effects)

---

## 📂 Project Structure

```text
/
├── index.html          # The main application code (Single File)
├── song.mp3            # Background music file (Required)
├── README.md           # Documentation
└── /images             # (Optional) Folder for local images