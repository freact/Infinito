# Infinito
Small playable demo of infinito

Infinito rules
Played on a finite square grid (I originally wrote it for 8x8, but any fixed size works).

Pieces:

One player is Black, the other is White.

Each player has one copy of each label k in N (0, 1, 2, 3, ...). No duplicates.

Neutral “∞” stones exist (grey). They have no owner and no value.

Goal:

The game ends when the board is full.

You want the smallest possible sum of the numbers printed on YOUR stones on the board at the end. Neutral “∞” stones do not count for either player.

Turn structure (two steps, in this order):

Optional move. You may move one of your stones like a chess queen (any number of squares orthogonally or diagonally) to an empty square. After the move: if your moved stone is now adjacent (including diagonals) to one or more enemy stones with a smaller value, and it was NOT adjacent to those enemy stones before the move, then for each such enemy stone you must: replace any one of your own stones on the board (but NOT the stone you just moved) with a neutral “∞” stone. Any stones you remove from the board go back to your supply and can be placed again later.

Compulsory placement. You must place one stone from your supply on any empty square.

More info at: https://www.reddit.com/r/abstractgames/comments/1qbucw9/infinito_an_infinite_game_and_myriades_its_finite/
