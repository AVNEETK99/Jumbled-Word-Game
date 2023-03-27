# Jumbled-Word-Game

Jumbled words game is a word puzzle game where the letters of a word are scrambled, and the player has to unscramble the letters to form the correct word. The game involves choosing a random word from a list, scrambling the letters of the word, and then presenting the jumbled word to the player. The player then has to guess the correct word by unscrambling the letters. The game can be played individually or as a multiplayer game where players take turns to guess the jumbled word. The player who correctly guesses the word scores a point, and the game continues until the players decide to end it.


## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type python jumbled.py and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* First, the random module is imported to use its ```choice()``` and ```sample()``` functions.

* The ```choose()``` function chooses a random word from a pre-defined list of words using the ```choice()``` function from the random module.

* The ```jumble()``` function takes a word as input, uses the ```sample()``` function from the random module to shuffle its characters and then joins them together into a new string.

* The ```thank()``` function takes the names and scores of both players and prints their respective scores and declares the winner based on the higher score.

* The ```check_win()``` function compares the scores of both players and declares the winner or a draw.

* The ```play()``` function asks for the names of both players and starts a loop that keeps running until the game is over.

* In each iteration of the loop, the ```choose()``` function is called to get a random word and the ```jumble()``` function is called to scramble the letters of the word.

* The game then asks the player whose turn it is to unscramble the word and enter the correct word.

* If the correct word is entered, the player's score is incremented and the turn is passed to the other player.

* If the wrong word is entered, the game passes the turn to the other player and shows the correct word.

* The game then asks the player whether they want to continue playing or quit. If the player chooses to quit, the ```thank()``` function is called to display the final scores and declare the winner, and the loop is broken.

* The driver code calls the ```play()``` function to start the game.
