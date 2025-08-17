# 🐍 Snake Game (C++ with SFML)

A classic Snake Game implemented in C++ using SFML (Simple and Fast Multimedia Library) as a Data Structures & Algorithms project.
The game demonstrates the use of linked lists, queues, and collision detection in an interactive environment.

# 🎮 Game Features

Snake Movement: Implemented using a doubly linked list (each node represents a part of the snake’s body).

Direction Queue: Movement keystrokes are stored in a queue to ensure smooth directional turns.

Food Generation: Randomly generated food on the screen, avoiding collision with the snake’s body.

Score System: Updates dynamically whenever the snake eats food.

Collision Detection:

Snake vs. Wall

Snake vs. Itself

Game Over Screen with the final score.

Title Screen with game logo and credits.

# 🛠️ Data Structures Used

Doubly Linked List → For snake body growth and movement.

Queue → For storing movement directions.

Linked List (Simple) → For borders of the game arena.


# 🚀 How to Run
1. Install SFML

Download and install SFML:
👉 https://www.sfml-dev.org/download.php

2. Clone this repository
git clone https://github.com/your-username/Snake-Game-DSA.git
cd Snake-Game-DSA

3. Compile the code

If you’re using g++:

g++ SnakeGame.cpp -o SnakeGame -lsfml-graphics -lsfml-window -lsfml-system

4. Run the game
./SnakeGame

# 🎯 Controls

⬅️ Left Arrow → Move Left

➡️ Right Arrow → Move Right

⬆️ Up Arrow → Move Up

⬇️ Down Arrow → Move Down
