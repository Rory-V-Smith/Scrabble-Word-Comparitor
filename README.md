# Scrabble-Word-Comparitor
Determine which of two Scrabble words is worth more.

Completed in part of Harvard's [CS50 - Introduction to Computer Science, 2020](https://cs50.harvard.edu/x/2020/)

This was Lab 2: [Scrabble](https://cs50.harvard.edu/college/2020/fall/labs/2/)

## Lab 2: Scrabble

### Background
In the game of [Scrabble](https://scrabble.hasbro.com/en-us/rules), players create words to score points, and the number of points is the sum of the point values of each letter in the word.
For example, if we wanted to score the word Code, we would note that in general Scrabble rules, the C is worth 3 points, the o is worth 1 point, the d is worth 2 points, and the e is worth 1 point. Summing these, we get that Code is worth 3 + 1 + 2 + 1 = 7 points.

### Implementation Details
The Scrabble-Word Comparitor determines the winner of a short scrabble-like game, where two players each enter their word, and the higher scoring player wins.
