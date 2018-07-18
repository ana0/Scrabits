# Scrabits

## Setup

Lay out a scrabble board and six letter tiles. These six tiles - the
*mempool* - can be used by anyone.

Fill out a *transaction input* for each player, sending them 50 Scrabits
from *Genesis Block*. Each of these inputs should be given a face-up letter
tile from the tile bag.

Make sure each player has three *difficulty cards* (one of each, red,
blue, and green).

## Play

There are no turns in Scrabits (although we recommend playing a few
turned rounds at the beginning of the game).

Players try to *mine blocks* by using the letter tiles in the mempool to
add words to the board. When a block is mined, see *Block Ceremony*.
Initially words must be at least 4 letters long, although this will
change with the Difficulty (see *Block Ceremony*).

Players can also send transactions (see *Sending Transactions*) by
filling out transaction output cards and putting them, along with the
associated input cards, input the *mempool* (remember that each
transaction card in the *mempool* should have a letter on it).

## Block Ceremony

When a block is mined (ie, a word is put on the board):

1. Tally the points (following normal scrabble rules), and make the
block reward transaction (don’t forget to include a letter on it).

2. Look at everyone’s difficulty cards. If at least 50% of people are
voting to adjust (either make it harder or easier), adjust the
difficulty: if easier, remove one letter from the minimum word length;
if more difficult, add one letter.

3. Replenish the *mempool* if necessary (make sure there are six tiles)

4. Give out any transaction output cards included in the block, making
sure each output gets a scrabble tile on top of it.

## Sending Transactions

To send a transaction:

1. Fill out transaction output cards such that the amount being sent
sums up to the amount of a transaction input card.

2. Stack the transaction output cards under the transaction input and
put them into the mempool. The scrabble tile from the input card can
now by used by anyone to mine a block (ie, form a word).

3. When the tile from this transaction is used in a block, the
transaction recipients are given the output cards. See step 4 of *Block
Ceremony*.

## Terminology

**Mempool** - the collection of transactions waiting to be mined into a
block. In Scrabits, this is the six communal tiles, plus any
transactions that have not been used.

**Mining blocks** - when a player uses the letter tiles in the mempool to
make a word on the scrabble board, a block is mined. See *Block
Ceremony*.

**Transactions** - a collection of *transaction input* and *transaction
output* cards.

**Transaction input / Transaction output** - a completed transaction card.

**Difficulty cards** - each player has one red, one blue, and one green
difficulty card which they can use to vote on whether the game is too
difficult, just right, or too easy. See *Block Ceremony*.