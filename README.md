# 🐍 Retro Snake Game World

Welcome to the **Retro Snake Game World**, a grid-based arena where your snake slithers, grows, and survives. Navigate the world, consume food, and avoid peril as you aim to dominate this pixelated domain!

---

## 🌍 Game World Overview

The game world is defined as a grid composed of square cells, creating a structured and intuitive play area. Here are its key aspects:

- **Grid Dimensions**:
  - Each cell is a `30x30` pixel square (`cellSize = 30`).
  - The grid is `25x25` cells in size (`cellCount = 25`).
- **Play Area**:
  - Offset of `75` pixels on all sides ensures a centered view (`offset = 75`).

---

## 🎨 World Aesthetics

- **Background Color**: A soothing green hue (`RGB: 173, 204, 96`).
- **Grid Lines**: A bold dark green to define the boundaries (`RGB: 43, 51, 24`).
- **Snake Appearance**:
  - Rounded rectangular segments, matching the grid’s dark green outline.
- **Food Icon**:
  - Customizable image (`food.png`) rendered seamlessly in the grid.

---

## 🕹️ World Interactions

- **Food Placement**:
  - Food spawns at random grid cells.
  - Each spawn avoids overlap with the snake's body.
- **Snake Movement**:
  - Moves one cell per step in a defined direction.
  - Wraps around the grid edges if boundaries are crossed (optional customization).

---

## 🔧 Customizing the World

- **Change Grid Size**:
  Modify `cellCount` and `cellSize` to adjust the number of cells and their dimensions.
- **Customize Appearance**:
  - Update the `green` and `darkGreen` variables for a different color palette.
  - Replace the `food.png` file with your preferred food icon.
- **Adjust Speed**:
  Change the interval for snake movement in the `EventTriggered()` function.

---

## 🛠️ Future Enhancements

Potential features to enhance the game world:

- **Obstacles**: Add walls or moving hazards.
- **Power-Ups**: Introduce temporary speed boosts or score multipliers.


---

## 🎮 Enter the World

Guide the snake, collect food, and strive for the highest score in this classic grid-based world of survival. Good luck!
## 🎮 Controls

- **Arrow Keys**: Control the snake's movement.
- **Start Game**: Press any arrow key to begin moving the snake.
- **Objective**: Eat the food to grow longer while avoiding collisions.

---

## 🎨 Customization

To modify the game's settings, update the following variables in the code:


## 💻 How to Compile and Run

### Linux/MacOS:

1. **Install Raylib**:
    ```bash
    sudo apt install libraylib-dev # For Ubuntu/Debian
    ```

2. **Compile the code**:
    ```bash
    g++ -std=c++17 snake_game.cpp -o snake_game -lraylib -lm
    ```

3. **Run the game**:
    ```bash
    ./snake_game
    ```

---

### Windows:

1. **Install Raylib for Windows**.

2. **Use a compatible IDE** (e.g., Visual Studio) or compile using:
    ```cmd
    g++ -std=c++17 snake_game.cpp -o snake_game.exe -lraylib
    ```

3. **Run the game**:
    ```cmd
    snake_game.exe
    ```



