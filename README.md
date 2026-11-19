# ENPASSANT

Think beyond the board. Chess game review for Chess.com players: enter a username, pick a game, choose a cartoon coach and get every move graded by Stockfish, with evaluation, accuracy and move-quality charts.

How it works
- Games: public Chess.com API (api.chess.com/pub/player/{username}/games/archives)
- Rules and PGN parsing: chess.js
- Analysis: Stockfish.js in a Web Worker (change the `SF` constant in `index.html` to use another build)

Roadmap
React + TypeScript + Vite front end, Express back end, puzzles, openings explorer.

ENPASSANT is an independent project and is not affiliated with Chess.com.
