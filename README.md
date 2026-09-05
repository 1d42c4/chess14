# Finish the Game

**[Open the live GitHub Pages course](https://knightway8.github.io/chess14/)**

Practical endgames with exact-result practice. Coordinate king and pawns, learn essential mating and rook-ending methods, and make informed decisions about exchanges.

## Who it is for

Players ready to turn extra material into wins and recognize realistic drawing methods.

This is an extensive course through a defined practical skill area, not a claim to cover all of chess. The full four-course route is aimed at human learners building reliable habits from the basics toward club play.

## What is included

- 24 distinct lessons in four modules, each with an explanation, task, answer, common mistake, and recall prompt.
- 96 interactive exercises with saved answer data.
- A six-week study plan and links to the full 24-week route.
- Browser-local progress, a review queue, private study notes, and progress import/export.
- A printable workbook with an answer key, Markdown notes, PGN positions, and structured JSON exercises.
- Offline scripts and styles; no account, analytics, remote fonts, or runtime engine service required.

## Modules

1. Kings, mates, and draws
2. King and pawn technique
3. Rooks and practical piece endings
4. Convert and defend under pressure

## Start here

[Lesson directory](https://knightway8.github.io/chess14/) · [Practice lab](https://knightway8.github.io/chess14/practice.html) · [Study plan](https://knightway8.github.io/chess14/study-plan.html) · [Downloads](https://knightway8.github.io/chess14/downloads.html) · [Sources and verification](https://knightway8.github.io/chess14/sources.html)

## The four-course collection

| Repository | Course | Live site |
| --- | --- | --- |
| [chess11](https://github.com/knightway8/chess11) | See the Board | [Open](https://knightway8.github.io/chess11/) |
| [chess12](https://github.com/knightway8/chess12) | Calculate with Purpose | [Open](https://knightway8.github.io/chess12/) |
| [chess13](https://github.com/knightway8/chess13) | Make a Plan | [Open](https://knightway8.github.io/chess13/) |
| [chess14](https://github.com/knightway8/chess14) | Finish the Game | [Open](https://knightway8.github.io/chess14/) |

## Use offline

Choose **Code → Download ZIP**, extract the archive, and open `index.html` in a browser. External reference and analysis links require internet access. Progress is browser-local; export it before clearing storage or changing devices.

## Verification

All 96 endgame exercises were checked against the Lichess Syzygy tablebase service. Win, draw, and loss are from the side-to-move perspective. Accepted move answers preserve the recorded result. The diagrams use a zero halfmove clock and no invented repetition history. The saved move categories make the answers available offline.

See [VALIDATION.json](VALIDATION.json) for check results. The original prose is AI-created educational material; report a concrete correction with its lesson or exercise ID. No rating improvement is promised.

## Maintain and publish

The editable source is [data/course.json](data/course.json). Run `node tools/build.mjs` to regenerate the pages, then `node tools/validate.cjs` for content, answer-legality, PGN, and link checks. The browser data and downloadable files are regenerated from the same source.

GitHub Pages serves the root of `main` with `.nojekyll`. Active branch rules require pull requests, prevent force pushes, and prevent deleting the default branch, with no bypass actors. Repository owners can still change settings or delete the repository.

## Credits

Original course writing, interface, and generated practice positions were prepared with AI for knightway8. Cburnett SVG chess pieces by Colin M. L. Burnett are included unmodified under GPL-2.0-or-later, with [source and attribution](assets/pieces/README.md) and the [full license](assets/pieces/COPYING.txt). The bundled chess.js library is BSD-2-Clause licensed; its full notice is in [vendor/chess-LICENSE.txt](vendor/chess-LICENSE.txt). Stockfish was used for local analysis and is not redistributed here. Tablebase facts are credited to the Lichess Syzygy service.
