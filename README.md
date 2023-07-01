# dominoes

An implementation of the game of dominoes in Javascript.

Demo [here](https://ppyne.github.io/dominoes/).

## The rules

The game is the double 6, has 28 pieces and 2 players (the computer).
The dominoes are shuffled and distributed, 5 pieces per player, and the 18 dominoes left, face down, constitutes the boneyard. Each player must hide his game.
The player with the highest double starts. He puts down the double and plays the next piece. If none of the players has a double, the dominoes are returned to the boneyard, shuffled and redistributed until a game can start.
The pieces must follow each other to form a chain, from a 6 to a 6, from a 5 to another 5, etc. When the piece is a double it is placed vertically in the chain.
Each player, one after another, places a domino at one end of the chain to lengthen the chain. If a player does not have a domino allowing him to continue the chain in an appropriate way, he must draw from the boneyard until he finds a satisfactory piece.
The player who has placed all his dominoes in the chain wins. If there is no more dominoes left in the boneyard and a player is unable to play, the player with the fewest pieces wins. If the players are execo, no one wins the game.