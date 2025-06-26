🏈 Integer Programming Optimization: Fantasy Handegg

This project applies integer programming techniques using Pyomo to solve a fantasy sports team selection problem. The goal is to select a team of American football players that maximizes total expected points, while satisfying strict budget and positional constraints.

📌 Problem Statement
You're tasked with selecting a 10-player fantasy handegg (American football) team that:

Maximizes total points scored in real matches.

Stays within a salary cap of $50,000.

Respects position constraints:

1 QB (Quarterback)

2 FB (Fullback)

2 RB (Running Back)

3 WR (Wide Receiver)

2 TE (Tight End)

Player data (position, salary, expected points) is loaded from a dataset hosted on Google Drive.

🛠 Technologies Used
Python

Pyomo (for mathematical optimization modeling)

CBC Solver (CoinOR)

Google Colab for execution

NumPy & Pandas for data handling

Matplotlib for optional plotting

🚀 How to Run
Mount your Google Drive in Colab.

Install required packages (Pyomo, CBC solver).

Load the dataset from a shared Google Drive link.

Define the integer programming model using Pyomo.

Solve the model and retrieve the optimal fantasy lineup.

📁 File Structure
Integer Programming Fantasy Handegg.ipynb: Main notebook containing the full optimization model and analysis.

README.md: Project overview and instructions.

📜 License
Licensed under the GNU General Public License v3.0.

📬 Contact

Created by Luis Pazmino Alvarez, consultant in finance, economics, and predictive modeling. 
Connect with me on LinkedIn https://www.linkedin.com/in/luis-pazmino-702838248/.
