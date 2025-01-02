# Tetris Game in Java

This is a simple Tetris game implemented in Java using the Swing library for the graphical user interface (GUI).

## Features
- Classic Tetris gameplay
- Different Tetromino shapes (I, J, L, O, S, T, Z)
- Score tracking
- Keyboard controls for rotation, movement, and quick drop

## Prerequisites
To run this project, ensure you have the following installed:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) (version 8 or higher)
- [Visual Studio Code](https://code.visualstudio.com/) or any Java IDE

## How to Run

### Using Visual Studio Code

1. **Clone or Download the Project:**
   - Clone the repository or copy the `Tetris.java` file into a new folder (e.g., `TetrisProject`).

2. **Open in VS Code:**
   - Launch Visual Studio Code and open the folder containing the `Tetris.java` file.

3. **Install Java Extensions:**
   - Install the "Java Extension Pack" from the Extensions Marketplace in VS Code.

4. **Compile and Run:**
   - Open `Tetris.java` in the editor.
   - Right-click anywhere in the file and select **Run Java**.
   - Alternatively, use the terminal:
     ```bash
     javac Tetris.java
     java Tetris
     ```

### Using Command Line

1. Navigate to the directory containing `Tetris.java`:
   ```bash
   cd path/to/TetrisProject
   ```

2. Compile the file:
   ```bash
   javac Tetris.java
   ```

3. Run the program:
   ```bash
   java Tetris
   ```

## Controls

- **Up Arrow**: Rotate the piece counterclockwise
- **Down Arrow**: Rotate the piece clockwise
- **Left Arrow**: Move the piece left
- **Right Arrow**: Move the piece right
- **Spacebar**: Drop the piece instantly

## Gameplay

- The game starts with a random Tetromino.
- Use the arrow keys to move and rotate the pieces to complete rows.
- Completed rows are cleared, and your score increases based on the number of rows cleared at once:
  - 1 Row: +100 points
  - 2 Rows: +300 points
  - 3 Rows: +500 points
  - 4 Rows: +800 points

## License

This project is licensed under the MIT License.

## Acknowledgments

- This implementation is inspired by the classic Tetris game.
- Special thanks to the Java community for their resources and tutorials.
