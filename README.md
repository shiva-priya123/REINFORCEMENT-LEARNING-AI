This project implements various Reinforcement Learning (RL) algorithms in a Pacman environment, inspired by the UC Berkeley CS188 AI course. It simulates and evaluates intelligent agent behavior using techniques like:

Value Iteration

Q-Learning

Markov Decision Processes (MDPs)

Feature-based Approximate Q-Learning

📁 Project Structure
bash
Copy
Edit
reinforcement-1/
│
├── layouts/               # Map layout files for Gridworld and Pacman
├── test_cases/            # Test files and autograder inputs
├── qlearningAgents.py     # Q-Learning agent implementation
├── valueIterationAgents.py# Value Iteration agent logic
├── gridworld.py           # Gridworld environment and rules
├── pacman.py              # Main Pacman logic and game runner
├── util.py                # Utility functions
└── ...                    # Supporting files (display, graphics, etc.)
🧪 How to Run
Install requirements (if any, e.g., Python 3.x):

bash
Copy
Edit
pip install -r requirements.txt
Run Pacman with an agent:

bash
Copy
Edit
python pacman.py -p QLearningAgent -l mediumClassic -a epsilon=0.1,alpha=0.5,gamma=0.9
Run Gridworld:

bash
Copy
Edit
python gridworld.py -a value -i 100
📚 Learning Goals
Understand how RL agents learn from rewards and environment dynamics.

Explore tradeoffs in exploration vs. exploitation.

Compare model-based vs. model-free learning approaches.

📌 Credits
This project is a modified or extended version of the UC Berkeley CS188 Pacman Projects. It may contain test cases and grading tools adapted for educational use.
