# ♟️ NautilusChess - Screen-Based Python Chess Engine

**NautilusChess** is a Python chess bot that plays through screen recognition. It uses a simplified Minimax algorithm and supports GUI interaction, external engines, and online play (unofficially).

---

## 🐚 Why "Nautilus"?
Continuing the aquatic theme of famous chess engines like Stockfish and Rybka, "Nautilus" is a nod to a deep-sea creature known for its strategic shell structure — just like this bot’s positional logic.

---

## 🔍 How It Works

- Captures screen pixels to locate and track chessboards on websites like:
  - **Lichess**
  - **Chess.com**
  - **Chess24**
  - **ChessFriends**

- Detects move highlights to infer game state.
- Prevents board resizing or moving mid-game.
- GUI or CLI modes supported.

---

## 🧠 Chess Logic

- Uses a depth-3 **Minimax algorithm** (non-recursive loop-based for speed).
- Can integrate **external chess engines**.
- Optional **Polyglot opening books** for advanced play.

---

## 📂 Project Structure

- `krevetka.py` — core chess logic
- `main.py` — GUI runner
- `tools.py` — screen capture & automation tools
- `engines/` — external chess engines (.exe)
- `images/` — board highlight RGB values
- `polyglot/` — optional opening books

---

## 🎵 Endgame Feature
Includes a free-to-use NCS track: *Hard as Steel* by Abbynoise, played at game end.

---

## ⚠️ Disclaimer
**This bot does not use official APIs and may violate ToS on platforms like Lichess.** Use at your own risk.

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python main.py         # With GUI
python krevetka.py     # CLI Mode
````

For better performance, use **[PyPy](https://www.pypy.org/)**.

---

## 📌 Note

The project contains redundant code and can be optimized further. Contributions are welcome!

---

## 📜 License

MIT License – use, modify, and share freely.

