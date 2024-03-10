# Tic Tac Toe

<h3> How To Play</h3>
Tic Tac Toe is a classic game played by two players.
Here are the basic rules:

<dl>
<dt>Game Board:</dt> 
Tic Tac Toe is played on a 3x3 grid. Players take turns to mark a space in the grid with their respective symbol: one player uses <strong>'X'</strong> and the other uses <strong>'O'</strong>.

<dt>Objective:</dt>  
The main goal is to get three of your own symbols in a row, that can occur <strong><i>horizontally</i></strong>, <strong><i>vertically</i></strong>, or <strong><i>diagonally</i></strong>.

<dt>How to Play:</dt> 
Players decide who goes first. Traditionally, one player is 'X' and the other is 'O'.
Players take turns placing their symbol in an empty square on the grid.
The first player to align three of their symbols vertically, horizontally, or diagonally wins the game.
<i>If all nine squares are filled and neither player has three symbols in a row, the game is considered a <strong>draw or tie</strong></i>.

<dt>Strategy and Tactics:</dt>
Players should attempt to block their opponent from creating a line of three while working to create their own line. Strategic placement of symbols is key to winning.

<dt>End of Game:</dt> 
The game ends when one player wins by connecting three of their symbols in a row or when all squares are filled, leading to a tie.
</dl>

<h3> Requirements </h3>

<dl>
<dt>Beginner:</dt> 
<strong>Game Board Representation:</strong> Implement a 3x3 grid using a suitable data structure (e.g., a two-dimensional array) to represent the game board.<br/>
<strong>Player Turns:</strong> The game should alternately allow two players to take turns, with one player assigned 'X' and the other 'O'. The system must track whose turn it is and switch turns after each valid move.<br/>
<strong>Move Input:</strong> Implement a user input mechanism for players to enter their moves. The input must be validated to ensure it targets an empty cell within the board's bounds.<br/>
<strong>Win Condition Check:</strong> After each move, the game must check for a win condition: three of the same symbols ('X' or 'O') aligned horizontally, vertically, or diagonally.<br/>
<strong>Draw Condition Check:</strong> The game should also check for a draw condition, where all cells are filled without reaching a win condition.
  
<dt>Intermediate:</dt>  
<strong>Game End and Restart:</strong> Upon reaching a win or draw condition, the game should display an appropriate message to the players and offer an option to restart the game or exit.<br/>
<strong>Info and Alerts:</strong>  Capture players names, indicate whose turn it is, and show messages for invalid moves, game outcomes (win/draw), and instructions on how to play.

<dt>Advanced:</dt> 
<strong>Graphical User Interface:</strong> Transition from a console-based to a graphical user interface using frameworks like Tkinter for Python, Swing for Java, or utilizing web technologies for a browser-based game. This enhances user interaction and visual appeal.<br/>
<strong>Error Handling:</strong> The game should gracefully handle invalid inputs and unexpected situations without crashing.<br/>
<strong>Code Modularity and Documentation:</strong> The game's code should be well-organized, modular, and documented, making it easy to maintain and extend (e.g., adding AI opponents).<br/>
<strong>Testing:</strong> Include unit tests to cover critical functionalities, ensuring the game logic works as expected under various scenarios.

<dt>Extras:</dt>
<strong>Single Player Mode with AI Opponent:</strong> Implement an AI opponent for single-player mode. The AI can range from basic (random moves) to advanced (using algorithms like Minimax to make strategic decisions).<br/>
<strong>Difficulty Levels:</strong> Offer multiple difficulty levels for the AI opponent, from easy to hard, by adjusting its strategy and predictiveness.<br/>
<strong>Online Multiplayer:</strong> Enable two players to play over the internet by implementing network code using WebSockets for real-time gameplay or RESTful APIs for turn-based games.<br/>
<strong>Leaderboards and Player Stats:</strong> Track player wins, losses, and draws, and display them in a leaderboard to add a competitive element.<br/>
<strong>Customizable Themes and Symbols:</strong> Allow players to customize the game board, background, and player symbols (instead of just 'X' and 'O') through various themes or uploading custom designs.<br/>
<strong>Undo/Redo Functionality:</strong> Implement an undo/redo feature that allows players to correct mistakes or review game moves, enhancing the learning experience.<br/>
<strong>Replay and Save Game</strong>: Give players the option to save their game progress or replay completed games to analyze or enjoy past matches.<br/>
<strong>Adaptive Game AI:</strong> For AI opponents, implement machine learning techniques to adapt and improve strategy based on past games against the player, increasing the challenge over time.<br/>
<strong>Sound Effects and Music:</strong> Add sound effects for game actions (like placing a mark or winning the game) and background music to improve immersion.<br/>
<strong>Cross-Platform Compatibility:</strong> Ensure the game runs on multiple platforms (Windows, macOS, Linux, iOS, Android) by using cross-platform frameworks like Unity or React Native.<br/>
<strong>Accessibility Features:</strong> Include options for colorblind modes, text-to-speech for visually impaired players, and keyboard navigation to make the game more accessible to a wider audience.<br/>
<strong>Localization and Internationalization:</strong> Support multiple languages to make the game accessible to a global audience.
