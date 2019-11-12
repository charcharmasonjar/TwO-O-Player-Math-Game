# TwO-O-Player-Math-Game

## About the exercise
### Instructions
Create a 2-Player math game where players take turns to answer simple math addition problems. A new math question is generated for each turn by picking two numbers between 1 and 20. The player whose turn it is is prompted the question and must answer correctly or lose a life.

### Details
Both players start with 3 lives. They lose a life if they mis-answer a question. At the end of every turn, the game should output the new scores for both players, so players know where they stand.
The game doesn’t end until one of the players loses all their lives. At this point, the game should announce who won and what the other player’s score is.

## Tasks
### Task 1: Extract Nouns for Classes
Read the description above again and extract / write down the nouns that you feel could make for important entities (manifested in the form of classes) to contain (encapsulate) logic as part of this app.
- Player
- Game
- Turn
- Question


### Task 2: Write their roles
What is the role for each class? Write out a brief paragraph describing the role that class will play in your app.

Remember that objects are important for two things:

1. State: Storing data describing themselves (variables)
2. Behavior: Defining actions that can be performed on them (methods)

Write down the methods for each class while also speaking to the following points:
- What information is relevant to each class?
- What will they need in order to be initialized?
- What public methods will be defined on them?

Furthermore:
- Which class will contain the game loop (where each instance of the loop is the other players turn)?
- Which class should manage who the current_player is?
- Which class(es) will contain user I/O and which will not have any?

#### Player
- initialized with three lives
- initialized with player number (either one or two)
- method to update the number of lives 

#### Game
- initialized with turn set to 1
- creates two players (player one and two)
- keeps track of turn 
- method to start question 
#### Turn
#### Question

##### Steps 
- file is run 
- create two players (player 1 and 2), each of whom have three lives 
- set the turn to player one
- output "new turn"
- output question using two random numbers between one and ten
- receive input from the command line
- output whether or not the answer was correct
- if incorrect, decrease the number of lives of that player by one
- if number of lives is 0, output final score and exit game
- if not, output the updated scores of both players
- switch the turn to player two 
