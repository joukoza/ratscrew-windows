# ratscrew-windows

Keys:
P1: "w" for a card
    "e" for a slap
    
P2: "u" for a card
    "i" for a slap
   
P3: "s" for a card
    "d" for a slap
    
P4: "j" for a card
    "k" for a slap

TODO:
ratscrew.py:

Possibly add a separate function that handles all window updates.

Add more comments to the code.

Add the sandwich rule (and possibly a way to easily turn it off).

Currently slaps aren't allowed after the last card has been played in face card mode.
Should this be changed?


Bugs,
At least for player 3.
After winning cards and starting next turn, automaticly win the played card back, if the card is J, Q, K or Ace.
Caused by the next player having no cards.

The game crashes if somebody makes a wrong slap and doesn't have enough cards
to give to other players.
