# ♟️ Chessify: Advanced Chess Engine

**Chessify** is a sleek, browser-based chess AI built with **Flask**, **JavaScript**, and **`python-chess`**.  
It features a **responsive UI**, **adjustable AI depth**, and **PGN move tracking** — delivering a gameplay experience that’s both **challenging** and **visually engaging**.

---

## ✨ Features

- 🧠 Adjustable AI depth (1–5 levels)
- ♟️ Legal move validation, check, and checkmate detection
- 🔄 Real-time PGN move recording
- 📱 Fully responsive on mobile & desktop
- 🎯 Undo, reset, and dynamic difficulty settings

---

## 🚀 Tech Stack

| Layer         | Technology Used |
|---------------|-----------------|
| Frontend      | HTML5, CSS3, Bootstrap, JavaScript, jQuery |
| Chess UI      | [chessboard.js](https://github.com/oakmac/chessboardjs) |
| Chess Engine  | [chess.js](https://github.com/jhlywa/chess.js), [python-chess](https://python-chess.readthedocs.io/) |
| Backend       | Python 3, Flask |

---

## 🧠 Algorithm & AI Logic

**Chessify** is powered by a layered AI strategy that balances intelligence with performance:

- 🔍 **Minimax Search**  
  Explores game states recursively to a fixed depth, simulating optimal play for both sides.

- ✂️ **Alpha-Beta Pruning**  
  Speeds up Minimax by pruning suboptimal branches — enabling deeper, faster searches.

- 📊 **Heuristic Evaluation**  
  Each position is scored based on:
  - Material values (e.g. queen > pawn)
  - Positional strength via piece-square tables

- ⏱️ **Iterative Deepening**  
  Gradually increases search depth (1 → N), refining move quality under time constraints.

  ---

## 🧑‍💻 Getting Started (Local Setup)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/chessify.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the App

```bash
python flask_app.py
```

Now visit your browser at:
➡️ **[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

## 🌍 Live Demo

> 🚀 Coming soon at:
> **[https://chessify.onrender.com](https://chessify.onrender.com)**

---

## 🖼️ Results / Output

```html
<video src="static/demo.mp4" width="100%" controls></video>
```
