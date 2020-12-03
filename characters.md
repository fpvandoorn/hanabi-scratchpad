## Characters

* Anxious: Cannot discard if there is an even number of clues available (including 0).
* Awkward: Cannot give any clues that touch [random number]s.
* Blind Spot: Cannot see the cards of the next player.
  * To be more precise: this is the player to their left / below them, which might be different in games with Contrarian.
* Color-Blind: Cannot receive a color clue.
* Compulsive: Can only clue if it touches the newest or oldest card in someone's hand.
* Conservative: Can only give clues that touch a single card.
* Contrarian: Play order inverts after taking a turn; 2-turn end game.
  * The game order changes after every turn of the Contrarian, for example if C is contrarian, the turns go `A B C B A E D C D E A B C B A E D C D E ...`
  * Moreover, after the last card is drawn, there are only two more turns before the game ends.
  * Without bottom-deck blind play, this means that the only way to play the bottom card of the deck is when the player just before the contrarian draws the last card of the deck
  * The Pace is displayed incorrectly with 3+ players. Subtract `#players - 2` to get the actual pace. (so in a 5-player game, subtract 3).
* Dumbfounded: Can only clue colors and [random number].
* Follower: Cannot play a card unless two cards of that same rank have already been played.
  * If the follower tries to play a card, and 0 or 1 cards of that rank have already been played, this is considered a misplay, and the card goes in the discard pile.
* Fuming: Can only clue numbers and [random color].
* Genius: Must clue both a color and a number (uses 2 clues).
  * The color clue **must** be given before the color clue. It is not legal to clue number first.
* Greedy: Can only give clues that touch 2+ cards.
* Hesitant: Cannot play cards from slot 1.
* Impulsive: Must play slot 1 if it has been clued.
* Indolent: Cannot play a card if they played on the last round.
* Inept: Cannot give any clues that touch [random color] cards.
* Insistent: Must continue to clue the same card(s) until one of them is played or discarded.
  * When cluing, this character goes in "insistent state" (if it's not in one already). While in "insistent state" they must keep giving a clue that touches at least one of the cards touched originally. Goes out of insistent state when one of the cards *originally* clued has been played or discarded.
* Insolent: Cannot clue the previous player.
  * To be more precise: this is the player to their right / above them, which might be different in games with Contrarian.
* Miser: Can only clue if there are 4 or more clues available.
* Mood Swings: Clues given must alternate between color and number.
  * Can start with any clue. From then on, if the previous clue was color, must clue number and vice versa.
* Oblivious: Cannot see the cards of the previous player.
  * To be more precise: this is the player to their right / above them, which might be different in games with Contrarian.
* Panicky: After discarding, discards again if there are 4 clues or less.
  * If a Panicky player discards, and before the discard there are 3 or fewer clues, then the player immediately discards another card on the same turn.
* Picky: Can only clue odd numbers or odd colors.
  * In No Variant can only clue red, green, purple, 1, 3, 5.
* Quacker: Can only quack instead of clue.
* Slow-Witted: Cannot see cards in slot 1.
  * This player still clues cards in slot 1 if they match the given clue.
* Spiteful: Cannot clue the next player.
  * To be more precise: this is the player to their left / below them, which might be different in games with Contrarian.
* Stubborn: Must perform a different action type than the player that came before them.
* Traumatized: Cannot discard if there is an odd number of clues available.
* Vulnerable: Cannot receive a number 2 or number 5 clue.
* Wasteful: Cannot discard if there are 2 or more clues available.
* Vindictive: Must clue if they received a clue since their last turn.

## Conventions

### General
* Take extra caution when interpreting moves as unnecessary moves, occupied moves or loaded moves.
  There might be a good other reason.
* 5 player character games are considered Hard Variants.
* Generally, when a player is forced to clue by their character they can give locked hand saves (but not 8 clue stalls) to other players if there is nothing better to do.

<!-- ### Anxious -->

### Awkward
* Make sure to mark all touched cards with negative [number].

### Blind Spot
* This is one of the characters that is hardest to play with for teammates.
* You can never bluff the player with Blind Spot.
* They always have to respect that it is a finesse on the next player.
* Can the player before Blind Spot bluff the player after Blind Spot? I think so, but it might be a true finesse?
* You can finesse the player with Blind Spot, but it will be slow, since they will wait a round for the next player to play into it.
  * Therefore, the player after the player with Blind splot should (almost) never hesitate into playing into finesses.
* You can't give a clue to the player with Blind Spot that is a reverse finesse on the player after the player with blind spot.

### Color-Blind
* 5s Compromise is on: when any 5 is playable, you cannot 5 chop move (5 stall/pull in the low score phase).
* 5 stalls when you have a locked hand are still on, but 5s in other hands should be favored if they are the same distance to chop.
* Recluing number generally means to play from the right (and if a single tempo clue is valuable enough, it doesn't promise the rest).

<!-- ### Compulsive -->

<!-- ### Conservative -->

### Contrarian
* The Pace is displayed incorrectly with 3+ players. Subtract `#players - 2` to get the actual pace. (so in a 5-player game, subtract 3).
* Efficiency in 5p No Variant is `1.39`.
* Order chop moves and other moves that affect the next player depend on the direction of the turn order.
* If you have two cards to play, one with higher priority than the other (for example if one card is finessed).
  Furthermore, suppose that the card with higher priority leads into a player's hand that doesn't have a turn before your next turn,
  and the card with lower priority leads into a player's hand that does have a turn before your next turn.
  Then you can play the card with lower priority.

<!-- ### Dumbfounded -->

### Follower
* Can be finessed on cards which are not yet playable??

<!-- ### Fuming -->

### Genius
* Both clues should generally be a play clue, save clue, early save clue (on a critical known unplayable), tempo clue, or fix clue.
* Genius should generally opt for a weaker clue (touching the focus of the card twice) if the more efficient clue can be misinterpreted as a finesse.
* On the first clue of the game, this is definitely not always the case.
  * The default interpretation is as follows:
    * non-1 + color: play the focus of the color clue, (early) save the number cards (assuming the color clue was given first)
    * 1 + color touching one of the 1s: gives tempo on the focus of the color clue (assuming 1 was given first)
    * 1 + color not touching a 1: early save on cards touched by color
  * The second clue is interpreted as a finesse if there is a clearly better clue available to Genius.

<!-- ### Greedy -->

### Hesitant
* Slot 2 is their finesse position.
* This applies to finesses, bluffs, Gentleman's discard, etc.
* If there is enough context that it is not slot 2, it is slot 1 (not slot 3).
* Layered finesses or stacked finesses go slot 2-1-3-4-5.
* Ejection position is slot 3, discharge position is slot 4.

### Impulsive
* All clues that touch slot 1 are focused on slot 1 (not on chop), and forward finesses if not currently playable.
* 5s on chop can be saved with color if slot 1 has the same rank. Non-critical 2s cannot be saved with color.
  However, they are play clues when it is loaded or occupied.
* Very early clues color clues on chop, when many other clues are available, are not save clues.

### Indolent
* Indolent can make small lies when Gentleman's discarding, if it's not too costly.

### Inept
* Make sure to mark all touched cards with negative [color].

### Insistent
* Reverse finesses do not apply if it can be a forward finesse (unless the ability doesn't trigger).
* Playing a card clued by Insistent has priority over playing into finesses.
* If the Insistent player gives a trash chop move, that is almost never unnecessary (since insistent doesn't want to give save clues)

<!-- ### Insolent -->

<!-- ### Miser -->

<!-- ### Mood Swings -->

### Oblivious
* This is mostly hard for teammates. Don't forget that the Oblivious character cannot see one hand when making decisions!
* The oblivious player does not have to respect a second-blind play from the player before them for finesses that also involve the oblivious player.
  * They do have to respect prompts that can get more than one card from the invisible player
  * The exception is when they have another playable card, or a good clue to give, then they should do the other action before playing the card that was clued in their hand (they cannot wait if they were also finessed).
  * If two separate finesses are given, the Oblivious character does not have to respect that both are on the hidden player, and can immediately play into one of them.

### Quacker
* Players do not have to respect finesses that other (not-too-occupied) players can give as well.
* Treat all clues given by Quacker as loaded play clues.
* Quacking on a 5 should be interpreted as a 5 color ejection.
* Read the [Duck conventions](https://github.com/Zamiell/hanabi-conventions/blob/master/variant-specific/Duck.md).

### Panicky
* 1-away saves should be respected (on low clues), and preferably be given with number.

<!-- ### Picky -->

### Slow-Witted
* Slow-witted finesses cards from slot 2 (of course)
* If slot 1 is touched by Slow-witted, it is not considered to be touched by the clue (and hence never the focus), except if it's known to be critical (e.g. it is clued 5).
* Giving a forward or reverse finesse that passes over the Slow-witted player, makes the finesse position slot 2.
  * In other words: if the Slow-witted player has a chance to play into a finesse, it must see the finessed card in order to not play into it yet.
  * In all cases where the Slow-witted player has no chance to respond to a finesse, it calls slot 1, as usual.
  * The slow-witted Finesse position is never moved to slot 2.
  * Example 1: Cathy is Slow-witted. Turn 1: Alice clues r4 with red in Emily's hand. Bob plays r1 from slot 1. Cathy sees r2 in Donald's slot 2, so doesn't play. Donald plays r2 from slot 2. Cathy has r3 in slot 1, so that is the last called card.
  * Example 2: Cathy is Slow-witted. Donald has a called y1, and Alice clues y to Donald, touching yellow 3. Emily plays y2 from slot 1, since Cathy didn't have a turn to play into it.
  * Example 3: Cathy is Slow-witted. Donald has a called y1, and Alice clues y to Donald, touching yellow 4. This time Cathy has y2 in slot 1, which this clue gets, and gets y3 from Emily's slot 1, since Cathy didn't have a chance to play the y3 yet.
  * Example 4: Cathy is Slow-witted. Alice clues y to Bob, touching y4. Donald has y2 y1 y3 r5. Donald will play y1, then y2, then y3 into this clue.
  * Example 5: Cathy is Slow-witted. Alice clues the r2 in Donald's hand, finessing Cathy's slot 1. Bob clues the b2 in Alice's hand. Since Cathy is already blind-playing, and could not respond to the blue clue yet, Donald plays b1 from slot 1.
* If the Slow-witted cannot possibly respond to a finesse (e.g. all cards in their hand are clued), then the finesse always calls slot 1.
  * Example 6: Cathy is Slow-witted. Alice clues 3 to Cathy, touching all cards in Cathy's hand. Donald plays b1 from slot 1, Emily plays b2 from slot 1, Cathy plays b3 from chop.
  * Example 7: Cathy is Slow-witted, and r2 is played. Alice clues 3 to Cathy, touching all cards in Cathy's hand. Cathy knows nothing beyond this. Since Cathy can immediately play the chop 3 as r3 if Cathy doesn't see finessable cards, the finesse calls b1 from Donald's slot 2 and b2 from Emily's slot 2.


<!-- ### Spiteful -->

### Stubborn
* The Stubborn player should respect that an out-of-order move is a priority bluff on the next player.
* Schrodinger's Cat principle applies: the Stubborn player should respect both possibilities.
* The player before the Stubborn player can discard rather than saving the Stubborn player.

<!-- ### Traumatized -->

### Vindictive
* They can give locked hand saves when they have to clue.
* Vindictive Rank Clue: the player just before the Vindictive player can rank 2, 3 or 4 clue any useful unplayable card (or rank when the color clue is equally good/better)
  * This is interpreted as a positional clue to the Vindictive player, to instruct them to play slot 2, 3, 4.
  * Exception 1: The player before vindictive has a character with clue-giving restrictions.
  * Exception 2: The player before vindictive is the only player who can give the clue, colour is blocked, and only one blindplay is called.
  * The touched cards are considered touched, but nothing is communicated about them being playable.
  * Because of this, the Vindictive player can usually not be bluffed with number.

### Vulnerable
* Color saves are on for 5s, but not for 2s. However, they are play clues when it is loaded
  or occupied (but beware: two color clues in a row could be two color saves on 5s).
* Very early clues color clues on chop, when many other clues are available, are not save clues.

<!-- ### Wasteful -->
