# ⌨️ Typing Speed Game

Welcome to the **Typing Speed Game**, a fun and interactive way to improve your typing speed and accuracy! This Java-based game, built using **Swing**, provides a creative graphical user interface (GUI) for a smooth and enjoyable typing experience. Compete with yourself or others by recording your scores on the leaderboard!

---

## 🎮 Game Features

- **Random Sentence Generation**: Type a random sentence each round.
- **WPM Calculation**: Track your typing speed in Words Per Minute (WPM).
- **Accuracy Feedback**: See your typing accuracy as a percentage.
- **Error Counter**: Get immediate feedback on how many typing errors you make.
- **Leaderboard**: Compete to achieve the best WPM, with sorted leaderboard entries.
- **Restart Option**: Play again with the click of a button, without restarting the entire game.

---

## 💻 Installation & Setup

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/radhikaaa25/TypingSpeedGame.git

2. Navigate to the project directory:

  ```bash
  cd typing-speed-game
  ```

3. Compile the Java file using javac:

  ```bash
  javac TypingSpeedGame.java
  ```
4. Run the game:
  ```bash
  java TypingSpeedGame
  ```
---

## 🛠️ How to Play

- **Start the game:** Click the Start button.
- **Type the given sentence:** A random sentence will appear in the "Text to Type" area.

---

## Track your progress:

- **WPM (Words Per Minute):**  Your speed is calculated based on the time taken to type the sentence.
- **Accuracy:** Calculated as the ratio of correct characters typed to the total characters in the sentence.
- **Errors:** The number of incorrect keystrokes made while typing.
- **Finish typing:** Once you finish typing the sentence, your stats will be calculated.
- **Submit your score:** Enter your name to record your WPM and accuracy in the leaderboard.
- **Restart:** You can click Restart to try again with a new sentence!

---

## 🚀 Game Mechanics

- **WPM Calculation:**  Words are counted based on the number of space-separated segments.
WPM is calculated as:
WPM= (Number of words / Time in minutes)

- **Accuracy:**  Accuracy is determined by comparing the typed text with the given text.
Accuracy (%) = (Correct Characters / Total Characters) * 100

- **Errors:** The error count increases whenever the user types an incorrect character.

---

## 📊 Leaderboard

The game keeps a leaderboard that displays players' names and their WPM scores along with accuracy. After each round, players can enter their name and submit their score.

- The leaderboard is sorted by WPM in descending order.
- The leaderboard is saved in a file named leaderboard.txt which is created in the project directory.

---

## 🖌️ Aesthetics & UI
The game's UI is designed to be simple yet visually engaging:

- Serif fonts for a clean and professional look.
- Color highlights on important game elements (text, stats, etc.).
- Error feedback in real time while typing, with stat updates on WPM and accuracy.
