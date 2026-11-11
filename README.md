# Feed the Monster!

A game made by Yoav (age 7) and his dad.

Munchy the monster is SO hungry. Slide your finger (or use the mouse or arrow keys) to move him and catch the yummy food — but don't let him eat the socks, broccoli, trainers or caterpillars!

**Play it:** https://mordmaman.github.io/feed-the-monster/

## How it works

- Every yummy thing is a point.
- Eat 3 yucky things and it's game over.
- Every 10 yummy things, Munchy BURPS and the food falls faster.

## Changing the game

Everything is in `index.html`. The easy settings are in the `CONFIG` block at the top of the script:

```js
const CONFIG = {
  monsterName: 'Munchy',
  monsterColour: '#8e5cf7',
  yummy: ['🍎', '🍌', '🍪', '🍕', '🧁', '🍓', '🍉', '🍩', '🥕', '🍇'],
  yucky: ['🧦', '🥦', '👟', '🐛'],
  yuckyChance: 0.3,
  lives: 3,
  burpEvery: 10,
  startSpeed: 0.22,
};
```

Change something, commit, and GitHub Pages updates the game in a minute or so.
