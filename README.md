# Permutations
Permutations is a card game for three or four players.
It is designed for players who are at least eight years old and can be played in
approximately thirty minutes.

## Components
Permutations is played with a deck of forty-eight cards.
There are twelve cards in each of four colours: red, yellow, green, and blue.
Each card displays a unique number between one and forty-eight.

## Set Up
  - Sort the cards by colour.
  - For a three-player game, set one colour aside. You will not use these cards.
  - Draw a random card of each colour that you are using and place them face up on the table.
  - Give each player all of the remaining (eleven) cards of a single colour.
  - Prepare a notepad that you can use to track players' scores throughout the game.

## Playing the Game
The game takes place over a series of _rounds_.
Each round is comprised of a series of eleven _auctions_.
During each auction, each player will _draft_ one card.
At the end of each round, you will score points based on the cards that you drafted during that round.

You will also use the cards that you draft during each round as your hand for the next round.

The game ends when any player has scored a total of one hundred points or more.
You win if you have the highest score at the end of the game.

### Auctions
During an auction, each player will draft one card from a _pool_ of available cards.
For the first auction, the pool is comprised of one random card of each player colour.
Subsequently, the pool is comprised of the players' bids from the previous auction.

To conduct an auction, secretly choose one card from your hand to be your _bid_.
The value of your bid is the number displayed on your card.
After everyone has chosen, you should reveal your bids.
In decreasing order of bid values, each player should draft one card from the pool.
Place the card that you draft face down in front of you.

### Scoring
Your score for each round depends on the cards that you drafted during that round.
To determine your score, first count how many cards you drafted of each colour.
Your score depends only on the largest of these counts, your _max_.
The following table describes your score for each possible max.

| Max |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  | 11  |
| -------- | --: | --: | --: | --: | --: | --: | --: | --: | --: |
| Score    |  6  | 10  | 15  | 21  | 28  | 36  | 45  | 55  | 66  |

These are triangular numbers. If your max for a given round is $m$, then your score is $m(m+1)/2$.

###  Additional Rounds
Record the total points each player has scored on a notepad.
If no one has scored a total of one hundred points or more, you should play another round.
You will use the cards that you drafted in the previous round as your hand for the next round.
