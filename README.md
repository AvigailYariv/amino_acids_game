
**📘 Amino Acid Structure Learning Game**
---
![opening_background](https://github.com/user-attachments/assets/2b37f2ec-3673-4cb0-91a9-10bdce6a49c3)

A fun, interactive Python/Tkinter game designed to help students learn and identify amino acids by their structural formulas.
The game displays amino acid images and prompts the user to guess their names, keeping track of the score.

*🎮 Game Features*
---
🖼️ Opening (Splash) Screen
Includes a welcome message, background image, and a Start Game button.

*🔍 Amino Acid Identification*
The game randomly selects an amino acid and shows its structural formula.

*💬 Interactive Answering*
Students type in the amino acid name and receive feedback:

✔️ Correct → score increases and next question appears

❌ Incorrect → retry or skip, score decreases

*📸 Image Handling*
---
Automatic loading of amino acid images from the images/ folder.
Accepts .png, .jpg, and .jpeg.

*🧠 Game Logic in a Separate Model*
All amino acid lists, scoring, and checking logic are inside
amino_acid_game_model.py.

⚠️ All amino acid images must be saved using their exact names
(e.g., alanine.png, lysine.jpg, etc.).

*🚀 How to Run the Game*
---
1️⃣ Install the dependencies

The game uses the Python Pillow library for image handling:

- pip install pillow

2️⃣ Run the game
python amino_acid_game.py

*🧩 How to Add Your Own Amino Acid Images*
---
Place the image in the images/ folder

Name the file using the amino acid name, for example:

serine.png
tryptophan.jpg

Make sure the spelling matches exactly

The game will automatically detect and resize the image

*📈 Scoring System*
---

Each correct answer → +1 point

Each wrong answer → -1 point

