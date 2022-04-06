## WAR - Project One

## War Overview

War is a simple card game where a single, standard deck of 52 cards is split in half and divided between two players. Both decks are face down and on each turn, both players flip the top card. The player with the highest card wins the round and gets to keep the losing players card(s) that were turned up.

## Spefifc Rules

* How to win:
    -  The player who ends up with all the cards in the deck wins
        OR
    - players can play using a point system and first to a certain number wins
* If the players tie on a round, they turn over another card. If they tie again, they keep turning cards until there is a winner.
* Suits are ignored in War
* Aces are high!

## Pseudocode / Planning

* create an object of a deck of cards
    -  object includes card rank, suit, and score
* randomize the order of the deck (shuffle)
* divide the shuffled deck in half
* assign each player to a half
* have both decks sit on page in containers
* hide deck with image of back of card
* when button (or decks) are clicked, show top card
* cards are compared and winner of round is determined
* cards added to winners deck if playing biggest deck winning system OR points added to scoreboard if playing point system 
* for next round, cards transition away like slideshow and next card is either revealed or hiding behind back of card until clicked. 

## Styling considerations
* front of card should be just number and either words saying suit or image of suit (4 pictures will take a lot less time to store in code rather than 52 images - one for each individual card)
* back of card can be image as well

## User Stories
* As a user:
- I want to draw the top card from my deck
- I want to see my score
- I want the previously flipped card to be discarded after turn is over
- I want next card to be face down before drawing it next

## Wireframing
![wireframe image](https://github.com/JCollinJones25/GA-proj-1-War/blob/main/proj-1-wireframe.png?raw=true)
