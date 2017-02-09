## Tennis Kata

You have just been employed by a tennis club, and your job
is to create code that will update the scoreboard.

Tennis has a rather quirky scoring system, and to newcomers it
can be a little difficult to keep track of.

Create a system that allows you to the umpire to simply run a method
each time a point is scored.

- Step 1: Develop the API you want to use.
- Step 2: Person 1, Write a test, Person 2 fix it.
- Step 3: Get to Green as soon as possible. really ugly code.
- Step 4: Without ever making test suite go red, refactor

  >Take turns, person 1, change one line, Green

  >Person 2 change one line, Green

  >hint: Talk to each other
 

### Summary of Tennis scoring:

1. A game is won by the first player to have won at least four points
   in total and at least two points more than the opponent.
1. The running score of each game is described in a manner peculiar
   to tennis: scores from zero to three points are described as “love”,
   “fifteen”, “thirty”, and “forty” respectively.
1. If at least three points have been scored by each player, and the
   scores are equal, the score is “deuce”.

1. If at least three points have been scored by each side and a player
   has one more point than his opponent, the score of the game is
   “advantage” for the player in the lead.

# GO!

### Get Started
```
git clone git@github.com:enricribas/tennis_kata.git
cd tennis_kata
bundle
guard
```
