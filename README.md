# telepathy_game
Development Steps:

- Draw board
    - [sun star eye moon circle bolt diamond hand heart] - Use font-icons for symbols.
[yellow orange red purple pink blue green silver white] - Standard or chosen constants for each color.
[A..R] [1..18]
- 1-Player game
    - Get name
    - Randomly select target square
    - Render Board
    - Offer player a chance to guess or solve
        - Entering in coordinates, fills out color and symbol, or
        - Click on square.
    - Compute results
        - Add guess to guesses list.
        - Compute Yes/No answer
        - Which squares are eliminated? (capture how many are eliminated with the guess, mark them)
        - Render Board
        - Provide Results
        - If player is solving, congratulate player and end game if correct, or show solution and wah-wah if incorrect.