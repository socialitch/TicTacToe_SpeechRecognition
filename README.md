# Tic Tac Toe Game With Speech Recgnition


## Description
This is a Single player Tic Tac Toe game implemented in python created with the help of speech recognition library.
On each prompt, the player has to either say a word or a number depending upon the move.
Using the speech recognition library and google's speech rocognition API, almost everytime the speech was recognized. The basic workflow of this simple game is that it's state is used to check how far the game is from completion. This state of the game is represented by a python list to store the occupied places on the board.
When one the two condition becomes true, state becomes false and the game is terminated. 
To mimic the computer's moves, implimentation of the MinMax algorithm is done.

----------------

#### Rcommend to check out the SpeechRecognition Library
[SpeechRecognition 3.8.1](https://pypi.org/project/SpeechRecognition/).
