# UNO-GameAI
UNO Game AI using Minimax and Expectimax adversarial search algorithms. Features defensive Minimax (Player 1), offensive Expectimax (Player 2), and manual/simulation mode (Player 3).
# Features
**Adversarial Search:** Implements depth-limited Minimax and Expectimax (Depth 3).
**Dynamic Strategies:** Features "Defensive" and "Offensive" playstyles through weighted evaluation functions.
**Interactive GUI:** A custom Tkinter-based interface with authentic UNO card styling, animations, and a real-time game log.
**Dual Modes:** Support for full AI simulation or manual "User vs. AI" gameplay. 
# AI Agent strategies 
| Player | Algorithm | Strategy | Focus |
| :--- | :--- | :--- | :--- |
| **Player 1** | Minimax | Defensive | Prevents opponent wins and manages "Skip" cards effectively. |
| **Player 2** | Expectimax | Offensive | Aggressive card shedding; treats the draw deck as a probabilistic chance node. |
| **Player 3** | Minimax | User/Simulation | Can be controlled manually or run as an AI observer. |
# How to Run
1. Ensure you have Python 3.x and Tkinter installed.
2. Clone the repository:
git clone https://github.com/hasnain-afkar/UNO-GameAI.git
3. Open the .ipynb file in Jupyter Notebook or VS Code.
4. Run the cells to launch either the CLI simulation or the Tkinter GUI.
