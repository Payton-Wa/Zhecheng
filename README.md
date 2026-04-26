# Zhecheng
Snake Game
Core Features

Responsive Gameplay: The game operates on a 20×20 grid, rendered on a <canvas> element. Players control the snake using either Arrow keys or WASD, with built-in logic to prevent "self-reversal" (e.g., you cannot move directly down while moving up).

Visual Polish: The styling uses a deep navy and emerald color palette (#1a1a2e and #4ecca3). The snake features a gradient opacity effect for its body and includes dynamic eye positioning based on the direction of movement. Food is rendered as a vibrant red circular "cherry."

Game Mechanics: * Collision Detection: The game ends if the snake hits the canvas borders or its own tail.

Scoring System: A persistent scoreboard tracks the current session score and the "Best" high score.

State Management: An overlay system handles the transition between the start screen, active gameplay, and the "Game Over" state.
