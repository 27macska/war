# War

The card game War in your browser. Play against the computer or a friend online, in Classic mode or Draw 3 mode.

**Play now:** https://27macska.github.io/war/

## Classic rules

- The deck is shuffled and split in half: each player gets 26 cards in a **Draw** pile.
- Each round, both players flip their top card. The higher card wins both cards, which go to the winner's **Won** pile. Aces are high, and suits don't matter.
- When your Draw pile runs out, your Won pile becomes your new Draw pile, in the order you won the cards (it isn't shuffled).

### Duels

If both cards have the same rank, it's a **duel**:

1. Each player places 3 cards face down.
2. Each player flips one more card. The higher card wins every card on the table.
3. If those cards tie too, the duel repeats: a double duel, a triple duel, and so on.

If you run low on cards in a duel, you place fewer face down so you still have one to flip. If you have no cards left, your last face-up card stays in play.

### Winning

- You win if your opponent runs out of cards.
- **Deck passes** sets a limit on how long the game lasts. One pass is one trip through your Draw pile. When a player finishes the last pass, whoever has more cards wins.

## Draw 3 mode

Draw 3 is the default mode: you choose your cards instead of flipping the top one. Set **Mode → Classic** for the original game.

- Each player holds a hand of 3 cards. Click a card to play it.
- Both players pick at the same time, and the cards are shown together. Nobody sees the other player's card before picking.
- After each round, hands are topped back up to 3 from the Draw pile.
- **Duels** work as in Classic: the 3 face-down cards come off your Draw pile. Then you pick the deciding card from your hand.
- Solo, you play against a computer opponent. **Play a random card** picks for you.

## Controls

| Control | What it does |
| --- | --- |
| **Next round** | Plays the next round. In a duel, it places your face-down cards. |
| **Auto-play** | Plays rounds by itself. It stops at each duel so you can place the face-down cards. |
| **Speed** | How fast rounds play. **Instant** with Auto-play runs straight to the end of the game. |
| **Mode** | Draw 3 (the default) or Classic. Changing it starts a new game. |
| **Deck passes** | How many trips through the Draw pile before the game ends (see Winning). |
| **New game** | Shuffles and deals a new game. |
| **Music** / **Volume** | Turns the music on or off and sets its volume. |

A round won by a single rank is a **close call**, and an ace beating a king is a **kingslayer**. Both get their own animation.

## Playing online

1. Click **Play online**.
2. One player clicks **Host a game** and shares the 5-character room code, or clicks **Copy invite link** and sends the link.
3. The other player types the code and clicks **Join**, or opens the invite link.

The host deals and chooses the mode and deck passes. Either player can ask for a new game once one ends.

- **Classic:** players take turns. The winner of each round plays first in the next one.
- **Draw 3:** both players pick at the same time, and the cards are shown together.

Both players need the same version of the game. If you get a version message, both of you should reload the page.

## Running it yourself

Everything is in one file, `war.html`. Open it in a browser to play solo, even with no internet connection. Online play needs an internet connection, because the page loads a connection library (PeerJS) when you click **Play online**.
