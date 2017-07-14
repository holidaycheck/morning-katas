# Tennis Kata

We want to implement the scoring system for Tennis, read up in details on [wikipedia][tennis-scoring]

## Instructions
taken from [this post][tennis-game-easy]

- Scores from zero to three points are described as “love”, “fifteen”, “thirty”, and “forty” respectively.
- If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is “advantage” for the player in the lead.
- If at least three points have been scored by each player, and the scores are equal, the score is “deuce”.
- A game is won by the first player to have won at least four points in total and at least two points more than the opponent.

## Rules
1. Code without tests simply doesn’t exist.
2. Come Without Your Relics. Do it right now, explain it to us.
3. We can learn from other people’s mistakes as well as from our own if we listen carefully.
4. Slow down. You cannot go faster and learn at the same time.
5. If it seems easy to you, explain it to others who find it difficult until they don't find it difficult anymore.

from the [Coding Dojo Handbook][codingdojohandbook] 

## Tools
http://www.cyber-dojo.org
http://tddbin.com - just JavaScript (incl. ES8)

## Week 2

The days:

1. TDD Basics - Arrange, Act, Assert, get familiar with the task, write the first tests and just get rolling.
2. Ping Pong Pairing - give the keyboard to the partner once a new test is red, don't keep the keyboard for longer than 3min, if you didn't get to green and write a new red test in that time, rethink and try to make it simpler, it was probably too complex.
3. No returns - Work in pairs. Write the code so that it does NOT use any return statements. Think different. It might get ugly and uncomfortable, that's ok. It underlines the importance of functions returning things. [Read more.][no-returns].
4. No conditionals - Write the code without conditionals, no IF, no ternary, no switch-case, nothing alike. It is ok to get the test green using a conditional. Before writing the next test refactor away the conditional.
5. TDD as if you Meant It - Force yourself to go even smaller steps, write code inside the test (function) don't abstract out until you really have duplication. Do a stronger refactoring phase, instead of planning and designing up front. [Read more on TDDaiymi][tddaiymi]

[codingdojohandbook]: https://leanpub.com/codingdojohandbook
[tennis-scoring]: https://en.wikipedia.org/wiki/Tennis_scoring_system#Game_score
[tennis-game-easy]: https://technologyconversations.com/2014/04/23/java-tutorial-through-katas-tennis-game-easy/
[no-returns]: https://ramonanger.wordpress.com/tag/coderetreat/
[tddaiymi]: https://cumulative-hypotheses.org/2011/08/30/tdd-as-if-you-meant-it/