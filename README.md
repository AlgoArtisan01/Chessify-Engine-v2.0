# ♟️ Chessify: Advanced Chess Engine

**Chessify** is a sleek, browser-based chess AI built with **`Flask`**, **`JavaScript`**, and **`python-chess`**. It features a **responsive UI**, **adjustable AI depth**, and **PGN move tracking** -- delivering a gameplay experience that’s both **challenging** and **visually engaging**.

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

| Component            | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 🔍 Minimax Search     | Explores the game tree to a fixed depth, simulating optimal player decisions |
| ✂️ Alpha-Beta Pruning | Prunes suboptimal branches, speeding up the minimax search dramatically       |
| 📊 Heuristic Evaluation | Scores positions based on material value and positional strength via square tables |
| ⏱️ Iterative Deepening | Searches from shallow to deeper depths (1 → N), refining move quality over time |

  ---

## 💻 Getting Started (Local Setup)

### 1. Clone the Repository

```bash
git clone https://github.com/AlgoArtisan01/Chessify-Engine-v2.0.git
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

> 🚀 Try It Yourself:
> **[https://chessify-engine-v2-0.onrender.com](https://chessify-engine-v2-0.onrender.com)**

---

## 🖼️ Results / Output

<p align="center">
  <img src="static/Demo.gif" alt="Chessify Demo" width="650"/>
</p>
