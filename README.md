# Spot-The-Error
🔤 Spot the Same Symbol Game (Python)
A fun little terminal-based game where two cards are generated with random symbols. Only one symbol is common between the two cards — your goal is to spot and guess that symbol!

🎮 How to Play
Two cards are displayed, each with 5 randomly chosen symbols.

Exactly one symbol is the same in both cards — either in the same or different position.

Your job is to spot the common symbol and type it in.

If your guess is correct, you win. Otherwise, try again later!

🧠 Game Logic
Uses Python's random and string modules.

Picks a random matching symbol for both cards.

Fills the rest with unique, non-overlapping random symbols.

Guarantees only one match between the two cards.

🛠 Features
Pure Python — no external libraries required.

Dynamic symbol selection from string.ascii_letters.

Only one common symbol between the two cards.

Simple terminal input/output interface.

🚀 How to Run
Make sure Python 3 is installed on your system.

Save the code in a file, for example: spot_the_symbol.py

Run it in your terminal or any IDE:

bash
Copy
Edit
python spot_the_symbol.py
📦 Sample Output
less
Copy
Edit
['q', 'A', 'g', 'x', 'K']
['v', 'A', 's', 'j', 'h']
Spot the same symbols: A
Hurray!! Right answer
💡 Possible Improvements
Allow replaying the game using a loop (see commented code).

Add a score system for correct/incorrect guesses.

Include a time limit for added challenge.

📚 License
This game is open-source and free to use for learning or personal enjoyment.
