# Master Mind Project

Mastermind is a vintage family game from my childhood. It is a game that requires a player to use logic, speculation and reasoning skills to determine the sequence of coloured counters. The computer has secretly generated a sequence leaving players having 10 attempts to guess correctly, or the computer wins!

## Link

Can you beat the computer? Find out: [Mastermind](https://fordalex.github.io/master-mind-project/)

## UX

I have tried to build this project to be very simple for the user to navigate through the webpages. The first page starts explaining how to play mastermind and a screenshot to make it easyier for the user to understand on how to play. After this information the player will see a large 'play Mastermind' button taking them to the next page.

The first modal that the user is faced with they cannot remove, click off, or press 'esc' this information needs to be filled in so that mastermind knows what to do next. Generating 3, 5 or 7 different coloured counters to be later guessed by the player.

After this information has been entered the user will see that mastermind is generating diffrent coloured counters four times every second to show the user the multiple possibilities. The counters being genereated will depend on what level of difficulty that the user has selected.


Playing the game:

After the user has pressed 'Play Mastermind' on the first page. Then inputted their name and difficulty level, the user is shown the board and flashing arrows at the top of the board saying 'play' indicating on what the user has to press next.

I tested this game out on a few peple at work and didn't help them through testing it.

* As a older user and someone who doesn't play games on his phone he was struggling on what to do next, so i have added larger moving, flashing arrows to catch the users eye and show them what to do next.

* Also users with bigger hands were struggling with the size of the buttons so i have made sure to change the size of these making them easier to notice and press.



## Features

Choosing Colours - The user is able to select the colours of the pegs and put them in order on the virtual board to allow the user to guess the computers coloured pegs, and remove them if a mistake is made.

After a while the game doesn't seem to have a reason to keep playing, you can choose between two themes if you get bored. But the user doesn't get anything for doing better than the last round, I am implementing a feature where the player will receive coins. The faster you solve the masters counters and the few guesses it takes you, the more coins you will get. The coins will be used to buy different counters, if you lose the computer will take some coins back off you!

### Features Left to Implement

At the end of the game, if the user wins I would like counters to be generated on the board in a moving pattern and a happy sound to be played, to give positive feed back to the user. If the player loses, all the pegs to turn red and be static, with a bad sound being played.

Also more categorys for items to be purchased keeping the user intrested for a longer time. 


## Testing and Bugs

[Testing And Bugs](https://github.com/Fordalex/master-mind-project/blob/master/testing-bugs.md)

## Deployment

This project is hosted on github, the first page the user will be taken to after they have press the link will be `index.html`. As github understand this being the main page, without this nothing will be displayed.




## Credits

### Media

The photos used in this site were taken from:

* [Pexels](https://www.pexels.com/)

Audio was taken from:

* [Free Sounds](https://freesound.org/)


### Acknowledgements

I need some help with some of the git commands:

* [stack overflow](https://stackoverflow.com/questions/10510462/force-git-push-to-overwrite-remote-files)

Adding a modal using Jquery:

* [Bootstrap modal methods and events](https://www.youtube.com/watch?v=1yrTszHY-mQ)

Prevent the modal from opening:

* [Stack overflow](https://stackoverflow.com/questions/16152073/prevent-bootstrap-modal-from-disappearing-when-clicking-outside-or-pressing-esca)

All audio taken from:

* [Adding Audio](https://www.youtube.com/watch?v=p4OHVJxd2FI)


