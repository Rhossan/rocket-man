## Sample JS Project Proposal: Conway's Game of Life with Variations

### Background

rocket man is a platform jumper with a twist - you jump by pressing space, activate rocket by multi-pressing space(there's a fuel tank). The game is scrolling up, and the platform begin to break. Collecting fuel will replenish tank


  

### Functionality & MVP  

With Rocket-man simulator, users will be able to:

- [ ] Start, pause, and reset the game 
- [ ] jump by pressing space, activate rocket by multi-pressing space
- [ ] move direction using direction pad
- [ ] collect fuel to replenish tank

Game ends when:
- [ ] when rocket man falls off the platform
- [ ] screen moving up, loses rocket-man 

In addition, this project will include:

- [ ] An About modal describing the background and rules of the game
- [ ] A production README

### Wireframes

This app will consist of a single screen with game board, game controls, and nav links to the Github, my LinkedIn,
and the About modal.  Game controls will include Start, Stop, and Reset buttons as well as options to select difficulty.


### Architecture and Technologies

**NB**: one of the main things you should be researching and deciding upon while you write this proposal is what technologies you plan to use.  Identify and create a plan of attack for the major technical challenges in your project.

This project will be implemented with the following technologies:

- `JavaScript` for game logic,
- `HTML5`, `CSS`, and `Canvas`. `Canvas` to help with physics for the rocket
- `Webpack` to bundle js files.

In addition to the entry file, there will be three scripts involved in this project:

`screen.js`: this script will handle the logic for creating and updating the necessary sprite elements and rendering them to the DOM.

`game_logic.js`: this script will handle the logic behind the scenes


### Implementation Timeline

**Day 1**: Setup all necessary Node modules and webpack. Write a basic entry file and the bare bones of the 2 scripts outlined above. Learn the basics of canvas including the physics. Goals for the day:

- Setup skeleton for project
- have sprites ready to render on a screen, learn canvas and physics for the rocket.

**Day 2**: Have a game map rendered, sprites rendered on screen, and basic functionality working.

**Day 3**: Install the controls for the user to interact with the game.  Style the frontend, making it polished and professional.  Goals for the day:

