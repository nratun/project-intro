# Boolean Bananza

## Elevator Pitch

*PITCH GOES HERE*

## Influences (Brief)

- *Yoshi's Cookie*:
  - Medium: *Console Game*
  - Explanation: *Yoshi's Cookie is our inspiration for determining how objects on the board could be moved. Columns/rows can be shifted vertically or horizontally to change the location of a block (i.e, the game is NOT a drag-and-drop).*
- *Candy Crush:*:
  - Medium: *Mobile Game*
  - Explanation: *Candy Crush is our inspiration for implementing a limited number of moves and required matches in order to complete each level (Ex. You need to get 2 expressions evaluated to True to pass), as well as having a score system that rewards players based off how many moves they took to complete a match.*
- *Sudoku*:
  - Medium: *Puzzle Game*
  - Explanation: *Sudoku is our inspiration for the grid-based board layout and how matches can be made (i.e, if the whole row/column is correct, then a match is made).*

## Core Gameplay Mechanics (Brief)

*Give a very high-level description of any core gameplay mechanics*

- *There is an NxN game board containing blocks with various values*
- *The size of the board increases in advanced levels* 
- *The initial board contains T, F, AND, NOT, and OR blocks, with other blocks being introduced in various levels*
- *Move around the board with WASD keys*
- *Shift the blocks in each row/column using arrow keys*
- *When all the blocks in a row/column evaluate to True or the specified value, a match is made and the row/column disappears*
- *New blocks take the place of any that were disappeared from a previous match (i.e, this is done by shifting blocks down and dropping new ones into the empty space)*
- *Players have limited moves, where each time a player moves off of a block whose position was shifted, their moves decrease by one*
- *A level is completed if players gather the required amount of specified matches, and lost if players run out of moves before gathering the required amount of specified matches*
- *Players who have trouble with understanding the logic behind matches can refer to a help section that offers examples and explanations*
- *When a level is completed, the player's score is shown on the screen and they can either replay the level, move to the next level, view the expressions they've created in that level, or return to the title screen. For those who failed to complete a level, a similar screen will be shown without the next level button*

# Learning Aspects

## Learning Domains

*Introductory comptational/programming logic*

## Target Audiences

- *Novice programmers with little/no prior programming experience*
- *Appropriate for all ages*

## Target Contexts

- *This could be offered as additional practice in a course that teaches conditional logic involving True/False expressions*
- *The game may also serve as an introduction to conditional logic concepts for unfamiliar players*
- *Due to the use of audio, it may not be appropriate for a classroom activity*
- *Because the controls rely on WASD and arrow keys, it may not work for devices that do not have a QWERTY keyboard (i.e, unsuitable for mobile gameplay)*

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- *Creating Boolean Expressions*: *By the end of the gameplay, players will be able to construct Boolean expressions by chaining together blocks of True, False, And, Or, Not, and other elements/expressions that can be equated to True or False*
- *Evaluating Truthiness*: *By the end of the lesson, players will be able to evaluate Boolean expressions and determine whether they equate to True or False*

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- *Prior to the game, players need to be able to define what Boolean values are*
- *Prior to the game, players must be able to identify the syntax and meaning of logical operators (Ex. NOT, AND, OR)*

## Assessment Measures

*A short pre-test and matching post-test should be designed to assess student learning.*

- *Given a boolean expression, determine whether it will evaluate to True or False*
- *Create a boolean expression given certain criteria (Ex. Use specific logical operators, make the expression evaluate to a given value)*
- *Given a boolean expression, explain why the answer does or does not evaluate to the answer that is provided*
- *Multiple choice questions that test students on how boolean operators work*

# What sets this project apart?

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- *The game doesn't teach players how to code, but prepares them to understand the logic behind conditional expressions*
- *The game can be played without Computer Science/programming principles in mind, and can be applied to mathematical concepts as well*
- *The gameplay mechanics of swapping blocks to create a match offer enjoyment beyond simply gaining satisfaction over learning the material*

# Player Interaction Patterns and Modes

## Player Interaction Pattern

*Describe how people play your game, how many players are involved at once, how they interact with the system works, etc.*

*This is a singleplayer game, players use the WASD and arrow keys to navigate through the board in a level, and click with the mouse to traverse the content between levels (Ex. next level button, replay)*

## Player Modes

*Your game has one or more player modes. Describe each discrete mode, considering things like menus too. Generally describe the transitions between modes too.*

- *Singleplayer*: *You repeatedly advance through levels until you've successfully completed all of them (Levels can be repeated, there is not an official ending screen denoting end of gameplay)*

# Gameplay Objectives

- *Make matches on the board*:
    - Description: *Swap the blocks within a row/column to make the entire line evalate to a specific value*
    - Alignment: *Completing a match teaches players how to construct Boolean expressions to achieve a desired output, thus teaching them the syntax of the expressions and how chained values interact together*
- *Complete the requirements in each level*:
    - Description: *Finish each round by making matches on the board to meet the level criteria within the given number of moves*
    - Alignment: *Completing a round indicates players' proficiency in evaluating various Boolean expressions, as the criteria will differ based off of the level (Ex. Round 1 may care about matches involving AND/OR, while Round 2 introduces expressions involving different order of operations)*
- *Complete all levels*:
    - Description: *Finish every level by meeting all the required criteria in each round. Each level introduces a new concept to work with, and so the requirement/layout of one level will not look the same as another*
    - Alignment: *Completing all the levels shows mastery in both constructing and evaluating Boolean expressions of varying complexity*

# Procedures/Actions

*Players can click on buttons to do the following:
- *Show similar helpful examples & explain the functionality of various blocks*
- *Reset/restart the level*
- *Return to the level select or main menu screen*

*Players can use keyboard buttons to move across the board and swap the placement of blocks in each level*

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

- *If a player changes a block in a row/column and moves to a different selected block, it takes up a move*
- *When players click off of a level and click back into it, they resume from where they previously left off*
- *Selected blocks can only be changed with one in the same row/column (i.e matches can only be made horizontal/vertical, blocks can not be switched diagonally)*
- *If the player runs out of moves without completing a level, a "round incomplete" screen appears*
- *The player can click on the help button to gain more insight on the game and making matches*
- *When a player makes a row/column match, the entire row/column gets removed/disappears)*
- *Each level incorporates new blocks or increases board size to create advanced Boolean expressions*
  - *T, F, AND, OR, NOT, =, Parentheses*
  - *Board size: 5x5, 7x7, 9x9*

# Objects/Entities

- *There is a game board in the middle of the screen where players will create logical expressions*
- *There are multicolored blocks within the board that players will combine to make the Boolean expressions*
- *There is text displaying the current score above the board*
- *To the left of the board is text showing the number of moves remaining, and required matches needed to complete the level*
- *There are buttons on top of the game board to return to the menu screen or restart the level, and a help button to the left of the board*

## Core Gameplay Mechanics (Detailed)

- *NxN game board*: *The game board where the matches will be done is a grid-based square board that changes in dimension based off of the current level. Easier/introductory levels will begin on a 5x5 board, and harder levels that introduce new material will have boards that could be 7x7 or 9x9 depending on the content*
- *Moveable blocks in game board*: *The first level board contains T, F, AND, NOT, and OR blocks in a 5x5 grid. This initial board would only consider matches where the row/column equates to True (Ex. the row T & F OR T would be considered a match, since the entire expression is True). 

More advanced levels would introduce the parentheses and equal sign symbol, to allow for matches that may also equate to False and account for different orders of operation (Ex. the row F OR ( F AND T ) = F would be a match because the expression evaluates to True)*
- *Movement on the board and blocks*: *Players can traverse the board with WASD keys, where W moves the player to the block above, A moves them to the left, D to the right, and S to the block below.*

*Similarly, players can switch the value of the current block they are on. This is done with the arrow keys, where ← arrow shifts the block to be the value of the one to the right of it, → shifts its value to the block on the left, ↑ shifts the value to the block below it, and ↓ shifts the value to the block above it. As a result, blocks can only be shifted with other blocks in the same row/column (Keep in mind, when blocks are shifted, every block in that row/column also shifts, and as a result the values within rows/columns will wrap around. Ex. Using the → arrow will change the value of the current block to be the one to the left of it, and so every other block in the row will shift to have the value of the one to the left of it--if it's a block at the beginning/end of a row, it will have the value of the block on the other end, thus wrapping around).*
- *Matches on the board*: *When all the blocks in a row/column evaluate to True or the specified value, a match is made and the row/column disappears. If a match is not made, the row/column remains as is. For example, because the row F OR ( F AND T ) = F evaluates to True, it is considered a match. The row F OR ( F AND T ) = T does not evalate to True, and so it is not a match.*

*When a match is made, the row/column containing the match is removed from the board, and all the blocks above it falls down to take its place. For rows, this would mean that the row above the one that was matched would move down by one row, and all the subsequent rows above would follow suit. For columns, this would mean that new blocks would drop down to fill in the empty space, but the rows would not change places.*
- *Limited moves each level*: *Players have limited moves each round, where each time a player moves off of a block whose position was shifted, their moves decrease by one. In other words, only when players switch to a new block with the WASD keys and attempt to shift its value does a move count as being used (i.e players can shift the currently selected block as many times as they want with the arrow keys, that will not take up a move until a new block is shifted).*

*The amount of moves for each level will vary, with harder levels (Ex. Ones with larger boards) possibly having more moves to account for more blocks needing to be shifted to make a match.*
- *Completing levels*: *A level is completed if players gather the required amount of specified matches, or lost if players run out of moves before gathering these matches. For example, the first round may ask players to make 5 matches consisting of the OR block, and 2 matches that contain only OR blocks within 15 moves (Ex. the match T AND T OR F would be a match, so it would clear from the board and increment the player's score, but it would not meet the criteria of containing only OR blocks since it also contains an AND).*

*Once a level is complete, a screen will show up congratulating the player and displaying their score for that round, as well as showing buttons that offer players the option to replay the level, view a list of all the matches they made in that level, return to the level select screen, or move to the next level. If the level is incomplete, players will be shown a screen similar to the complete version, but without the button that lets them move on to the next level.*
- *Help section*: *Players who have trouble understanding the game or how expressions are evaluated can refer to the help section by clicking on the button in the top right of the screen during a level. This section will offer players help with in-game controls and mechanics, explanations for each block, and examples on how to construct and evaluate Boolean expressions.*

## Feedback

*Explicitly describe what visual/audio/animation indicators there are that give players feedback on their progress towards their gameplay objectives (and ideally the learning objectives).*

*Describe what longer-term feedback you detect and give that guides the player in their learning and lets them know how they are doing in regards to the learning objectives.*

- *When a match is made, the blocks will be removed from the screen and a sound will be played indicating that you've earned more points*
- *When players complete a criteria, a sound will be played indicating they've finished that part*
- *When players have few moves remaining (Ex. 5 or less), a sound will be played to remind players that they do not have many moves left*
- *When a level is complete/incomplete, players will be given happy/sad noises alerting them of their success*
- *Text on screen indicates the player's current score, as well as which criteria they have met/still have yet to meet*
- *When all the levels are completed, players will be rewarded with an end screen showcasing a happy outcome of the story*

# Story and Gameplay

## Presentation of Rules

*Players will have an option to click on a button that outlines how to play the game. This section will offer a tutorial with a game board just like in the real levels where players will be guided through the process of how to move and make matches.*

*If players ever get confused or forget any instructions during levels, they can refer to the help button for simple instructions.*

## Presentation of Content

*Players will be taught the material with the aid of the in-game characters. When a level is introducing a new block/concept, a character in the game will explain how that feature integrates into the content (Ex. if players reach a new level that implements parenthesis, a new character will explain how parentheses change the order of operations to prioritize the operations within the parentheses first).*

*Additionally, because the game is not time-based and does not heavily penalize players for changing the value of a block they're on, there is ample opportunity for them to experiment with different combinations and learn the various ways of reaching a match.*

## Story (Brief)

*You come across a group of friendly frogs and help them construct Boolean expressions to light up their pond for the frog festival.*

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

*Give a sense of the aesthetics of your game, the spirit and atmosphere. Use descriptive, evocative words that can help the reader understand the emotional response of your game.*

*The aesthetics should be *

## Graphical

- Characters List
  - *Characters 1*
  - *Characters 2*
  - *...*
- Textures:
  - *Texture 1*
  - *Texture 2*
  - *...*
- Environment Art/Textures:
  - *Environment Texture 1*
  - *Environment Texture 2*
  - *...*


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *Game Interaction*: *Example 1*, *Example 2*
  - *Game Interaction*: *Example 3*, *Example 4*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
