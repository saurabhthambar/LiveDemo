
---

# 🧀 Chess | The Game of India

A fully playable chess game built with **HTML, CSS, and JavaScript** — featuring smooth animations, clean minimal UI, and complete piece movement logic including castling, pawn promotion, and captures.

This is a front-end only chess project rendered directly in the browser.

---

## 🚀 Features

### ✔ Fully Playable Chess

* All standard moves implemented
* Pawn movement + diagonal captures
* Pawn promotion (auto-queen)
* Rook, Bishop, Knight, Queen, King logic
* Castling (both sides for both colors)
* Turn-based play (White → Black → White …)

### ✔ Clean Modern UI

* Minimal dark theme
* Smooth hover animations
* Subtle tile glow
* Drop-shadowed chess piece icons
* Responsive board for mobile screens

### ✔ Image-Based Pieces

Pieces are rendered using PNG images stored inside the `/images` folder.

---

## 📁 Project Structure

```
paneer-chess/
│
├── index.html      # Chess board layout and DOM structure
├── style.css       # Modern minimal UI styles
├── app.js          # Entire chess logic + rendering
├── images/         # Chess piece PNGs (Wpawn.png, Bking.png, etc.)
└── README.md       # Project documentation
```

---

## 🛠️ Technologies Used

* **HTML5** – board structure
* **CSS3** – minimal black aesthetic, responsive design
* **JavaScript (Vanilla)** – all game logic, move validation, rendering

No libraries. No frameworks. 100% pure front-end logic.

---

## 🎮 How to Play

1. Open `index.html` in your browser.
2. Click a piece → valid moves highlight automatically.
3. Click a highlighted square to move.
4. Game ends when one king is captured.

---

## 🔧 Setup Instructions

Just clone and run. No build tools required.

```bash
git clone https://github.com/yourusername/paneer-chess.git
cd paneer-chess
open index.html
```

Or simply drag-drop `index.html` into Chrome.

---

## 🧩 Known Limitations

* No check/checkmate detection
* No en-passant
* Game ends on king capture instead

These can be added later if you want a fully competitive engine.

---

## 🚧 Future Improvements (optional)

* Highlight last move
* Check / Checkmate detection
* Undo button
* Move history sidebar
* AI opponent (minimax)

---

## 📸 Screenshots

*(Add later once you have screenshots)*

---

## 🤝 Contributing

Feel free to open issues or PRs if you want to refine movement logic or add new UI themes.

---

## 📄 License

This project is open-source and free to modify.

---
