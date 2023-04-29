# Battleships game
This game is a single player game designed for users to compete against the computer in a game of logic and chance. The player must sink all the computers battleships by making estimations on where the computer's battleships are located on a 5 x 5, 8 x 8 or 10 x 10 battle grid. The game provides value to users who are interested in playing online games that provide them with the opportunity of playing against the computer.

## User Experience
### User Stories
- First time visitor goals
1. I want to play against the computer in a game of battleships
2. I want to see my score displayed as I play through the game
3. I want the ability to chose the size of the grid and how many battleships

- Returning visitor goals
1. I want to play against the computer using a different sized grid or different number of battlehsips
2. I want to beat the computer in fewer turns
3. I want to play the game without any errors occuring and to ensure the developer of the game is a trusted source.

- Frequent visitor goals
1. I want to see has the developer included additional features to allow the player a certain number of turns or missiles to sink all the computers ships.
2. I want to see has the developer updated the design of the site to include battleships image designs to improve the aesthetics of the game.
3. I want to see has the user included the option for players to save or share their highest scores or a leaderboard.

- Owner goals
1. I want to provide an interactive game that encourages users to play and gain encouragement and excitement from.
2. I want to provide a game that encourages healthy competition amongst users.
3. I want to gain recognition and develop an online presence in the area of online game development.

## Design
The grids are designed to display in the center of screens with the positions allocated by a number and letter system. The grid size displayed depends on the users game choice.

The functions and validation checks were planned and designed with lucidchart.

![Battelships lucid chart](assets/images/battleships-lucid-chart.PNG)

## Existing Features
The user is welcomed to the game where a short explanation is provided on how to play the game

The user is requested that they input their username and choose the grid size they wish to play.

The user grid is displayed showing the location of the user's battleships and the computers board is displayed. A prompt is issued to the user to choose a position. Validation is in place here so only numbers and letters can be used.

The user's score is displayed and incremented when a user sinks one of the computers battleships and vice versa. 

A game over screen appears whenever a player sinks the required number of battleships or the computer does.

## Accessibility

## Languages
[Python]()

## Frameworks, Libraries and Programs

[LucidChart](https://www.lucidchart.com/pages/)
- LucidChart was used to design the layout of the game and which functions would be required to run the game including areas where validation was in place.

[Git](https://www.gitpod.io/)
- Gitpod was used for adding commits each time a new feature was added to the game and for pushing the commits to Github.

[Github](https://github.com/)
- Github was used for storing the site after being pushed from gitpod.

[Heroku]()
- Heroku was used for deploying the website.

## Future Features
- I would like to include a variable for the number of missiles the player has to sink the computer's ships and provide a random variable to change the size of the hidden ships on the board.

## Validation & Testing
[PEP8 Python Validator](https://pep8ci.herokuapp.com/)

## Testing User Stories
- First Time Visitors

## Testing on Browsers and Devices

### Browser Testing

### Device Testing

### Lighthouse Testing

## Bugs

### Solved Bugs

### Unsolved Bugs

## Deployment

### Instructions

## Credits

### Code

[How to code battleship gameboard in python](https://www.youtube.com/watch?v=cwpS_ac8uk0&t=45s)
The code used in this (Youtube)[https://www.youtube.com/] tutorial was adapted to write the display board function based on the user's choice of grid size.

[Battleship - ASCII Art](https://ascii.co.uk/art/battleship)
This website was used to add a design feature of a battleship image to the welcome message at the beginning of the game. The image is displayed using several print statements.

[Portfolio Project 3 Scope](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+PE_PAGPPF+2021_Q2/courseware/b3378fc1159e43e3b70916fdefdfae51/605f34e006594dc4ae19f5e60ec75e2e/)
This video tutorial from the [Code Institute website](https://codeinstitute.net/ie/) was used and adapted to include the board class to the Battleships code to set the number of ships, the board type and provide methods to add ships to the player and computer boards and record the guesses made.

### Content

### Acknowledgements