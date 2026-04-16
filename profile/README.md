<p align="center">
  <img src="https://raw.githubusercontent.com/echecsjs/.github/main/profile/banner.svg" alt="echecs — Build chess apps with confidence" width="800" />
</p>

<p align="center">
  TypeScript chess libraries following FIDE rules. Strict types, zero dependencies, ESM-only.
</p>

<p align="center">
  <a href="https://www.npmjs.com/org/echecs">npm</a> ·
  <a href="https://echecs.dev">echecs.dev</a> ·
  <a href="https://github.com/echecsjs/.github/blob/main/CONTRIBUTING.md">Contributing</a>
</p>

---

### Core

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/position`](https://github.com/echecsjs/position) | Chess position type and board utilities | [![npm](https://img.shields.io/npm/v/@echecs/position)](https://www.npmjs.com/package/@echecs/position) | [docs](https://position.echecs.dev) |
| [`@echecs/fen`](https://github.com/echecsjs/fen) | Parse and stringify FEN chess positions | [![npm](https://img.shields.io/npm/v/@echecs/fen)](https://www.npmjs.com/package/@echecs/fen) | |
| [`@echecs/san`](https://github.com/echecsjs/san) | Parse, resolve, and stringify SAN chess moves | [![npm](https://img.shields.io/npm/v/@echecs/san)](https://www.npmjs.com/package/@echecs/san) | |
| [`@echecs/pgn`](https://github.com/echecsjs/pgn) | PGN parser with comments, variations, NAGs, and annotations | [![npm](https://img.shields.io/npm/v/@echecs/pgn)](https://www.npmjs.com/package/@echecs/pgn) | |
| [`@echecs/game`](https://github.com/echecsjs/game) | Chess game engine with legal move generation and undo/redo | [![npm](https://img.shields.io/npm/v/@echecs/game)](https://www.npmjs.com/package/@echecs/game) | [docs](https://game.echecs.dev) |
| [`@echecs/zobrist`](https://github.com/echecsjs/zobrist) | Polyglot standard Zobrist hash keys for chess positions | [![npm](https://img.shields.io/npm/v/@echecs/zobrist)](https://www.npmjs.com/package/@echecs/zobrist) | |

### Engine

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/uci`](https://github.com/echecsjs/uci) | UCI engine wrapper for communicating with Stockfish and others | [![npm](https://img.shields.io/npm/v/@echecs/uci)](https://www.npmjs.com/package/@echecs/uci) | [docs](https://uci.echecs.dev) |

### Ratings

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/elo`](https://github.com/echecsjs/elo) | ELO rating system following FIDE rules | [![npm](https://img.shields.io/npm/v/@echecs/elo)](https://www.npmjs.com/package/@echecs/elo) | [docs](https://elo.echecs.dev) |

### Tournaments

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/swiss`](https://github.com/echecsjs/swiss) | Swiss tournament pairing and standings following FIDE rules | [![npm](https://img.shields.io/npm/v/@echecs/swiss)](https://www.npmjs.com/package/@echecs/swiss) | [docs](https://swiss.echecs.dev) |
| [`@echecs/round-robin`](https://github.com/echecsjs/round-robin) | Round-robin pairings following FIDE Berger tables | [![npm](https://img.shields.io/npm/v/@echecs/round-robin)](https://www.npmjs.com/package/@echecs/round-robin) | |
| [`@echecs/tournament`](https://github.com/echecsjs/tournament) | Stateful tournament orchestrator for any FIDE pairing system | [![npm](https://img.shields.io/npm/v/@echecs/tournament)](https://www.npmjs.com/package/@echecs/tournament) | [docs](https://tournament.echecs.dev) |

### Tiebreaks

| Package | Description | |
| --- | --- | --- |
| [`@echecs/buchholz`](https://github.com/echecsjs/buchholz) | Buchholz tiebreak family (Cut, Median, Average, Fore) | [![npm](https://img.shields.io/npm/v/@echecs/buchholz)](https://www.npmjs.com/package/@echecs/buchholz) |
| [`@echecs/sonneborn-berger`](https://github.com/echecsjs/sonneborn-berger) | Sonneborn-Berger tiebreak | [![npm](https://img.shields.io/npm/v/@echecs/sonneborn-berger)](https://www.npmjs.com/package/@echecs/sonneborn-berger) |
| [`@echecs/progressive`](https://github.com/echecsjs/progressive) | Progressive score tiebreak | [![npm](https://img.shields.io/npm/v/@echecs/progressive)](https://www.npmjs.com/package/@echecs/progressive) |
| [`@echecs/koya`](https://github.com/echecsjs/koya) | Koya tiebreak for round-robin tournaments | [![npm](https://img.shields.io/npm/v/@echecs/koya)](https://www.npmjs.com/package/@echecs/koya) |
| [`@echecs/direct-encounter`](https://github.com/echecsjs/direct-encounter) | Direct encounter tiebreak | [![npm](https://img.shields.io/npm/v/@echecs/direct-encounter)](https://www.npmjs.com/package/@echecs/direct-encounter) |
| [`@echecs/number-of-wins`](https://github.com/echecsjs/number-of-wins) | Win-counting tiebreaks (Wins, Black Wins, Standard Points) | [![npm](https://img.shields.io/npm/v/@echecs/number-of-wins)](https://www.npmjs.com/package/@echecs/number-of-wins) |
| [`@echecs/average-rating`](https://github.com/echecsjs/average-rating) | Average Rating of Opponents tiebreak | [![npm](https://img.shields.io/npm/v/@echecs/average-rating)](https://www.npmjs.com/package/@echecs/average-rating) |
| [`@echecs/performance-rating`](https://github.com/echecsjs/performance-rating) | Performance rating tiebreaks (TPR, Perfect TPR) | [![npm](https://img.shields.io/npm/v/@echecs/performance-rating)](https://www.npmjs.com/package/@echecs/performance-rating) |

### UI

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/react-board`](https://github.com/echecsjs/react-board) | React chessboard with drag & drop, animation, and theming | [![npm](https://img.shields.io/npm/v/@echecs/react-board)](https://www.npmjs.com/package/@echecs/react-board) | [docs](https://react-board.echecs.dev) |
| [`@echecs/react-movesheet`](https://github.com/echecsjs/react-movesheet) | React move notation panel with click navigation and variations | [![npm](https://img.shields.io/npm/v/@echecs/react-movesheet)](https://www.npmjs.com/package/@echecs/react-movesheet) | |

### File Formats

| Package | Description | | |
| --- | --- | --- | --- |
| [`@echecs/trf`](https://github.com/echecsjs/trf) | FIDE Tournament Report File (TRF) parser | [![npm](https://img.shields.io/npm/v/@echecs/trf)](https://www.npmjs.com/package/@echecs/trf) | [docs](https://trf.echecs.dev) |
| [`@echecs/tunx`](https://github.com/echecsjs/tunx) | SwissManager TUNX binary file parser/serializer | [![npm](https://img.shields.io/npm/v/@echecs/tunx)](https://www.npmjs.com/package/@echecs/tunx) | |
