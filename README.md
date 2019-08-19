# Rock-Paper-Scissors_OpenCV-Python
A rock-paper-scissors game project against computer via computer camera.

Computer can understand that which rock, paper or scissors gesture/move the player makes by detecting player's hand gestures and it can choose one of the rock, paper or scissors moves as a counter move. The instant score is visible on the screen and the computer always tries to win the game by using its special algorithm.

Template matching method is used as gesture detection algorithm. So it's always calibrating moves at the beginning of the each game in order to get to know the environment, background, lightning conditions and player's unique ways of doing the gestures.

# Algorithm

**Important:** The algorithm selects a counter move without knowing that which move the opponent made when the space button is pressed because this is how we play in reality. The algorithm doesn't cheat. It uses the data like which moves the opponent made earlier and tries the guess which move the opponent is going to make next by using probability and statistics then finally it produces a counter move.

# Screenshots

![screenshot](https://github.com/TolgaGolet/Rock-Paper-Scissors_OpenCV-Python/blob/master/Screenshots/Screenshot.png)
![screenshot](https://github.com/TolgaGolet/Rock-Paper-Scissors_OpenCV-Python/blob/master/Screenshots/Screenshot2.png)
![screenshot](https://github.com/TolgaGolet/Rock-Paper-Scissors_OpenCV-Python/blob/master/Screenshots/Screenshot3.png)
![screenshot](https://github.com/TolgaGolet/Rock-Paper-Scissors_OpenCV-Python/blob/master/Screenshots/Screenshot4.png)

# Requirements

OpenCV <br/>
Computer Camera
