#  Project


* Using ​HTML, ​CSS ​and ​JavaScript ​by created ​a ​complete browser-based ​card ​matching ​game ​(also ​known ​as ​Concentration). ​From ​building ​a ​grid ​of ​cards, ​adding functionality ​to ​handle ​user ​input, ​and ​implementing ​gameplay ​logic ​- ​combined ​all ​your ​web development ​skills ​to ​create ​a ​fully ​interactive ​experience ​for ​your ​users.

* The Memory Game Project is all about demonstrating your mastery of HTML, CSS, and JavaScript.

* Built a complete browser-based card matching game (also known as Concentration). But this isn’t just any memory game! It’s a shnazzy, well-designed, feature-packed memory game!


* Modal HTML and CSS code referenced from https://www.w3schools.com/howto/howto_css_modals.asp

## Table of Contents

* [How The Game Works](#memoryGame?)
* [Game Functionality](#functionality)
* [Project Specification](#specification)
* [Scoring](#scoring)
* [Instructions](#instructions)
* [Development Strategy](#developmentStrategy)
* [Output Screnshots](#screnshots)
* [What I learnt?](#learningHappened)


## MemoryGame

**How The Game Works**

The game board consists of sixteen "cards" arranged in a grid. The deck is made up of eight different pairs of cards, each with different symbols on one side. The cards are arranged randomly on the grid with the symbol face down. The gameplay rules are very simple: flip over two hidden cards at a time to locate the ones that match!

Each turn:

The player flips one card over to reveal its underlying symbol.
The player then turns over a second card, trying to find the corresponding card with the same symbol.
If the cards match, both cards stay flipped over.
If the cards do not match, both cards are flipped face down.
The game ends once all cards have been correctly matched.


## Instructions

This is a simple memory game that has been created from a a template provided by Udacity.
This game has been modifed to meet the requirements of the Front End project for the Intro to Programming Nano Degree.


### Scoring
3 stars = 14 moves or less
2 stars = 19 moves or less
1 star = 20 moves or more

## How To Play

* Super simple project to run.
* Download or fork the project.
* Open the index.html file and it should be working.
* The game starts automatically upon page load.
* Click the cards to reveal them.
* The goal is to reveal cards two at a time to match the pairs.
* The game ends when all pairs are revealed.

## Screnshots
* Game loaded in Browser
![Game](https://i.imgur.com/PFEgiEe.png)

### Videos
* A Correct Guess
[![Correct Guess](https://youtu.be/nZY0-TJtsgM/o.png)](https://youtu.be/nZY0-TJtsgM)
* An Incorrect Guess
[![Incorrect Guess](https://youtu.be/P5OfFEpcq28/0.jpg)](https://youtu.be/P5OfFEpcq28)
* Winning The Game
[![Winning The Game](https://youtu.be/r5YOzWxcbng)](https://youtu.be/r5YOzWxcbng)

## LearningHappened

* The memory game presents the first opportunity to fully combine your skills in HTML, CSS, and JavaScript into a large project.
* Aside from solidifying your skills with these three technologies, you'll discover how best to combine them in a complex application.

* The following are just some of the questions that you'll experience along the way:

    * What's the ideal workflow?
    * How many files do I need?
    * Do I modify the HTML first or the CSS?
    * How many JavaScript functions do I need?
    * Should my function be this many lines of code?
    * There's no one right answer to each question

## DevelopmentStrategy

* It's very important that you plan your project before you start writing any code.
* Break your project down into small pieces of work and plan out your approach to each one.
* It's much easier to debug and fix an issue if you've only made a small change.
* It becomes much harder if you wait longer to test your code.
* You don't build a house all at once, but brick by brick.

* Start by building a very simple grid of cards.
    * Don't worry about styling, just get something clickable on the page.
    * Figure out the HTML needed to represent a card. Remember, you have to represent two sides of the card. Are you going to have two separate elements stacked on top of each other?
* Add the functionality to handle clicks.
    * This should reveal the hidden side of each card.
* Work on the matching logic. How does your game "know" if a player guesses correctly or incorrectly?
* Work on the winning condition. How does your game “know” if a player has won?
* We recommend saving styling until the very end. Allow your game logic and functionality to dictate the styling.

## Specification

* Memory Game Logic
    * The game randomly shuffles the cards. A user wins once all cards have successfully been matched.

* Congratulations Popup
    * When a user wins the game, a modal appears to congratulate the player and ask if they want to play again. It should also tell the user how much time it took to win the game, and what the star rating was.

* Restart Button
    * A restart button allows the player to reset the game board, the timer, and the star rating.

* Star Rating
    * The game displays a star rating (from 1-3) that reflects the player's performance. At the beginning of a game, it should display 3 stars. After some number of moves, it should change to a 2 star rating. After a few more moves, it should change to a 1 star rating.
    * The number of moves needed to change the rating is up to you, but it should happen at some point.

* Timer
    * When the player starts a game, a displayed timer should also start. Once the player wins the game, the timer stops.

* Move Counter
    * Game displays the current number of moves a user has made.

* Styling
    * Application uses CSS to style components for the game.

* Usability
    * All application components are usable across modern desktop, tablet, and phone browsers.

* Readaiblity
    * * Code is formatted with consistent, logical, and easy-to-read formatting

* Documentation
    * A README file is included detailing the game and all dependencies.
    * Comments are present and effectively explain longer code procedure when necessary.

* Add CSS animations when cards are clicked, unsuccessfully matched, and successfully matched.

* Add unique functionality beyond the minimum requirements (Implement a leaderboard, store game state using local storage, etc.)

* Implement additional optimizations that improve the performance and user experience of the game (keyboard shortcuts for gameplay, etc).

## Functionality
The real-life game, players flip over cards to locate the pairs that match The goal is to recreate this effect in your project. There are a couple of interactions that you'll need to handle:

    * Flipping cards
        * What happens when cards match
        * What happens when cards do not match
        * When the game finishes
        * Below are some examples of how we implemented these interactions.
