# Lightning Game Zone ⚡

A free indie game collection. Built one weekend at a time.

**Live**: https://arlong6.github.io/lightning-game-zone/

## Games

| Title | Status | Repo |
|---|---|---|
| [Voltline](https://arlong6.github.io/voltline/) | Shipped (v0.80.1) | [Arlong6/voltline](https://github.com/Arlong6/voltline) |
| Untitled #02 | Planning | — |
| Untitled #03 | Planning | — |
| Untitled #04 | Planning | — |

## Adding a New Game

1. Build the game in its own repo with a Web export (see `voltline` as template)
2. Deploy that repo to GitHub Pages
3. In this repo's `index.html`, replace one of the `coming-soon` cards with a `playable` card pointing at the new game's URL
4. `git commit && git push` — GitHub Pages auto-redeploys

## Stack

- Pure static HTML / CSS
- No JS frameworks, no build step
- Hosted on GitHub Pages
