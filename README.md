# Stone-Paper-Scissors-Game-JS

## 🎮 Classic Rock, Paper, Scissors Game

This is a simple, browser-based implementation of the timeless **Rock, Paper, Scissors** hand game, built purely with fundamental web technologies. Play against a randomized computer opponent and see who can get the highest score!

## ✨ Key Features

* **Pure JavaScript Logic:** The entire game engine, including the winner determination and scorekeeping, is handled efficiently by vanilla JavaScript.
* **Randomized AI:** The computer's moves are generated using a random function, ensuring every round is unpredictable and fair.
* **Live Score Tracking:** The interface provides real-time updates for both the player's and the computer's scores.
* **Visual Feedback:** The result message dynamically changes text and color (green for win, red for loss, yellow for draw) to give immediate feedback.
* **Educational Project:** This project serves as a practical demonstration of **DOM Manipulation** and **Event Handling** in JavaScript.

## 🚀 How to Play

### Rules

1.  **Rock** beats Scissors.
2.  **Scissors** beats Paper.
3.  **Paper** beats Rock.
4.  If both players choose the same, it's a Draw.

### Running the Game

The game requires no installation or complex setup.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/AbhishekShukla7655/Stone-Paper-Scissors-Game-JS.git](https://github.com/AbhishekShukla7655/Stone-Paper-Scissors-Game-JS.git)
    ```
2.  **Open the Game:** Navigate to the cloned directory and simply open the **`index.html`** file in your web browser.

## 💻 Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML** | Structure and layout of the game elements. |
| **CSS** | Styling, visual design, and responsive layout. |
| **JavaScript** | Core game logic, event handling, score management, and DOM manipulation. |

## 💡 Code Structure (JS)

The JavaScript logic is modular and organized into clear functions for readability:

* `genCompChoice()`: Generates the computer's move.
* `drawGame()`: Handles tie scenarios.
* `showWinner()`: Updates the scores and displays the result message.
* `playGame()`: The main function that runs a round and determines the winner.
* **Event Listeners:** Attach click handlers to the choice elements to start the game.

---

## 🙋‍♂️ Contribution

Contributions are always welcome! Feel free to fork the repository, make changes, and open a pull request. This project is distributed under the **MIT License**.

## 📜 License

This project is licensed under the **MIT License**. See the **`LICENSE`** file for details.
