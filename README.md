# 🔤 Spot the Same Symbol Game (Python)

A fun terminal-based game where two cards are shown, each containing 5 random letters. Only **one symbol is common** between the two — your job is to spot and guess that symbol!

---

## 🎮 How to Play

1. Two "cards" (lists) are generated with 5 random symbols each.
2. Exactly one symbol appears in **both cards**.
3. The rest of the symbols are all unique.
4. You have to guess the common symbol and type it in.
5. If correct → 🎉 you win. Otherwise → try again!

---

## 🧠 Game Logic

- Symbols are picked from uppercase and lowercase English letters (A–Z, a–z).
- A single matching symbol is chosen and placed randomly in both cards.
- Remaining positions are filled with **non-overlapping** symbols.
- Ensures there's **only one correct answer**.

---

## 🛠 Features

- Simple command-line gameplay.
- Uses Python's built-in `random` and `string` modules.
- Guarantees exactly one matching symbol.
- Encourages attention and pattern spotting.

---

## 🚀 How to Run

1. Save the script as `spot_the_symbol.py`
2. Run it from your terminal:

```bash
python spot_the_symbol.py
['k', 'W', 'q', 'r', 'H']
['L', 'W', 'x', 'a', 'j']
Spot the same symbols: W
Hurray!! Right answer

---
### ✅ To Make This Work as a README File:

1. Create a new file named `README.md`
2. Paste the text above into it.
3. Open it in a Markdown viewer (like GitHub, VS Code, or any Markdown editor) to see the formatting.

Let me know if you’d like me to save it as a `.md` file and provide it for download.
