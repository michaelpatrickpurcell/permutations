# Permutations
A card game for three or four players.
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
The game ends when any player has scored a cumulative total of one hundred points or more.
The winner of the game is the player with the highest score at the end of the game.

## Auctions
During an auction, each player will draft one card from a _pool_ of available cards.
A pool will always consist of one card per player.
During the first auction of the first round, the pool is comprised of one randomly chosen card of each colour that you are using.
In subsequent auctions, the pool is comprised of the players' bids from the previous auction.

To conduct an auction, you will secretly choose one card from your hand to be your _bid_.
The value of your bid is the number displayed on the card that you choose.
After everyone has chosen, you should simultaneously reveal your bids.
In decreasing order of bid values, each player should draft one card from the pool.
Place the card that you draft face down in front of you.

## Scoring
Your score for each round depends on the cards that you drafted during that round.
To determine your score, first count how many cards you drafted of each colour.
Your score depends only on the largest of these counts, your _maxcount_.
The following table describes your score for each possible maxcount.

| Maxcount |  3  |  4  |  5  |  6  |  7  |  8  |  9  | 10  | 11  |
| -------- | --: | --: | --: | --: | --: | --: | --: | --: | --: |
| Score    |  6  | 10  | 15  | 21  | 28  | 36  | 45  | 55  | 66  |

Notice that these are triangular numbers. That is, if your maxcount for a given round is $m$, then your score for that round is $m(m+1)/2$. 
