# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
  - I will be using a single page application that has an API for server side requests as well as game logic.
-   How you will take the markup of the game board and represent it in JS
  - The answer to this is in the game states object, where in the API there are HTML inputs which go to a Game object marking the cell, index and value.  In this instance, I would use those names on the divs and use jQuery to put the X or O in the cell and get it to the Game Object.  Each cell would have a class of cell, which would correspond to the cell object, an ID of index such as 0-9, and the value X or O.
-   How you plan to approach this project.
  - This is my first programming project in a single file that will be modular.  I will approach it be heavily leaning on the examples for the API and other applications in class, with modular structures, specifically making sure that they are not global or interdependent.
-   4-8 user stories for your game project.
  - "As a user, I would like to be able to change my password at any time"
  - "As a user, I would like to be able to know when I win or lose the game"
  - "As a developer, I would like to separate my markup, styling and logic so I can create a more modular app"
  - "As a user, I would like to keep track of the number of games I've played"
  - "As a user, I want a cheat mode that will tell me how to win so I can crush my foes"
  - "As a user, I would like to be able to play my friends/anyone in the same game on the same page"
-   How you plan to keep your code modular.
  - I plan to keep the mechanisms of the game API in separate areas, mainly starting a game, updating/playing a game, and ending a game.  There will have to be a check at every turn to see whether the game is over or not.
-   What creative spin will you add to your project?
  - I am hoping to put in a fun option called cheat mode where you can click a button and the cells you need to get in order to win would be highlighted.
-   How will you use version control to backup / track your project?
  - I will be doing commits after virtually any change.  In addition, I will set up several branches, a master branch, and a branch for each major code module.
-   Do you plan to attempt any of the bonuses?
  - I hope to be able to add a win counter, use some hover/flip animations and keep track of multiple game rounds.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).

Wireframe: [wireframe](http://imgur.com/vfEc5af "Wireframe")

Game Logic: [gamelogic](http://imgur.com/NGiAYz8 "Game Logic")
