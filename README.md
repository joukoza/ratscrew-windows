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

NOTES

Currently slaps aren't allowed after the last card has been played in face card mode.
Should this be changed?

If player makes a wrong slap while the game is in face_mode and they
don't have enough cards to give to other players, their remaining cards are
placed in card_pile and they aren't registered as cards having been played in
face_mode.

If the person putting down the cards in face_mode runs out of cards, the game counts
that as a win for the person who put the last face card.

Sandwich-rule is implemented, i.e. slapping when current and 2nd previous card
are the same value counts as a slap win.

TODO:
ratscrew.py:

Add more comments to the code.

BUGS

NONE
