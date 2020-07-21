### Heuristics for when you can discard in the early game of hanabi.

Uses terminology from https://github.com/Zamiell/hanabi-conventions/blob/master/Reference.md
Probably too complicated as a convention, and has exceptions, but pretty good as a heuristic.
The basic idea is: if someone could save your hand without losing much efficiency/tempo, then you should be allowed to discard

* If you have a (non-delayed) play you are not allowed to discard
* If you can do a clean 2-for-1 (i.e. no bad touch) you are not allowed to discard
* If the next player that has nothing to do on their next turn has a critical chop, you are not allowed to discard
* Otherwise, you are allowed to discard if someone gave you permission to discard. Someone gives you permission to discard if they could have saved you instead of what they actually did, without losing much, like in the following situations:
  * If someone gives a 1-for-1, they give everyone permission to discard. Exception: the clued card enables an efficient clue.
  * If someone saves a card, they give everyone other than the clue receiver permission to discard. Exception: the clue receiver needs 2+ save clues or this save clue enables more efficient a play clue.
  * If someone 5 stalls, that gives everyone (including the clue giver) permission to discard.
  * If someone plays a card that doesn't lead to another player's hand, and they don't have another known playable card, that gives the first player that doesn't have an action permission to discard.
  * If you have absolutely nothing to do (not even low-efficiency clues like 5 stalls, early fix clues or 2 saves where you see both 2s), you have permission to discard.
  * If there is at most 1 clue left, you have permission to discard.
* Clarifications:
  * You don't give permission to discard to yourself: if you gave a 1-for-1 on your previous turn, and then everyone else did important actions, it is possible you don't have permission to discard. The exception is that a 5 stall does signal that everyone is now allowed to discard (we don't want someone 5-stalling twice)
  * If you save a card, that doesn't give the clue receiver permission to discard: maybe their next card is also critical
  * If you save a card, that does give everyone else permission to discard: we assume that people can look ahead well enough into the future to know who the first player is that is likely to discard.