# Guess-the-word-game-with-react
we have created the guess the number game. In which the computer will select a random number between 1 and 20 and the player will get unlimited chances to guess the number. If the player makes an incorrect guess, the player will be notified whether the guess is is higher or lower than correct number until the correct guess is made.

To achieve this we have created two components App and Result. App components contain all the logic, it is stateful and the Result component only shows the appropriate message on the page according to the user’s guess. There is a default prop we set to the App component ‘secret’ that holds the required secret number and it is generated randomly.

