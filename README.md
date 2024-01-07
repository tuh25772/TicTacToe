# TicTacToe

The implemented game is a classic Tic Tac Toe, developed using Java programming language with the Java Swing library for the graphical user interface (GUI). It features the following properties:

# 1. Language and Libraries Used: 
The game is written in Java, utilizing Swing for GUI components such as frames, panels, buttons, and labels.

# 2. GUI Components: 
The game window consists of a main JFrame containing a title panel with a large label displaying "Tic-Tac-Toe" and a button panel with 9 buttons arranged in a 3x3 grid, representing the game grid.

# 3. Player Input and Game Initialization: 
Upon launching the game, a separate JFrame prompts users to enter their names via text fields. After inputting the player names, a "Start Game" button initializes the game with the entered player names.

# 4. Game Logic Handling: 
Each button on the grid corresponds to a cell in the Tic Tac Toe game. Players take turns clicking the buttons to place their marks (X or O) on the grid. The game alternates turns between the two players, updating the display to indicate whose turn it is.

# 5. Win and Tie Conditions: 
The implemented code includes a placeholder method check() where you can add logic to determine the winner by checking for winning combinations or detecting a tie if the board gets filled without a win.

# 6. Dynamic UI Updates: 
The UI dynamically updates after each move, changing the button text to display X or O according to the player's turn. It also updates the title label to indicate which player's turn it is.

# 7. Event-Driven Programming: 
The game utilizes event-driven programming, where button clicks trigger the actionPerformed() method, allowing the game logic to respond to user actions.

# 8. Object-Oriented Approach: 
The implementation follows an object-oriented approach, utilizing classes, methods, and member variables to encapsulate game functionality and UI components.

# Overall
This game provides a basic framework for a two-player Tic Tac Toe game in a graphical interface, allowing players to take turns marking the grid until a player wins or the game ends in a tie.
