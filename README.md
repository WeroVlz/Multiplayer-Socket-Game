# Multiplayer-Socket-Game

The game to be built on top of a client-server architecture is a Four in a Line. The main programming language that will be used for the UI in the client side of the game is Python in Windows. On the other hand, the server side of the application will be programmed in C in Linux.

The game consists of a two-player strategy game in which the players take turns dropping colored discs into a vertical grid of seven columns and six rows. The objective of the game is to connect four of your own discs vertically, horizontally, or diagonally before your opponent does the same. Once a player has connected four discs in a row, they win the game. The game requires a combination of skill and strategy, as players must anticipate their opponent's moves while also setting up their own connections.


<!-- GETTING STARTED -->
## Requirements
 - The server side of this application can be hosted on a Linux machine or container. Docker is recommended.
 + For the client side, you must have the latest version of Python and Pygame installed. 

## Launching the game

  + You must compile the server script in bash first:
  
    ```bash
    cc tcpserver.c -lnsl -o server
    ```
    then to start the server:
    
    ```bash
    ./server
    ```
  + For the client side:
  
    ```bash
    python client.py
    ```
