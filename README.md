# Feed the Monster!

A game made by Yoav (age 7) and his dad.

Munchy the monster is SO hungry. Slide your finger (or use the mouse or arrow keys) to move him and catch the yummy food — but don't let him eat the socks, broccoli, trainers or caterpillars!

**Play it:** https://mordmaman.github.io/feed-the-monster/

## How it works

- Every yummy thing is a point. A 🌟 super snack is worth 5 and fills Munchy's tummy.
- 🥛 **Super milk** (Yoav's idea!) is very rare — catch it for 10 points and a full tummy.
- 🌾 **Hay** (also Yoav's idea) takes away 5 points.
- Munchy's tummy empties over time — if it goes empty, it's game over.
- Eat 3 yucky things and it's game over too.
- Every 10 points, Munchy BURPS and it gets harder: faster food, more yucky things, then drifting and zig-zagging food.

## Changing the game

Everything is in `index.html`. The easy settings are in the `CONFIG` block at the top of the script:

```js
const CONFIG = {
  monsterName: 'Munchy',
  monsterColour: '#8e5cf7',
  yummy: ['🍎', '🍌', '🍪', '🍕', '🧁', '🍓', '🍉', '🍩', '🥕', '🍇'],
  yucky: ['🧦', '🥦', '👟', '🐛'],
  golden: '🌟',
  milk: '🥛', milkChance: 0.015, milkPoints: 10,
  hay: '🌾', hayChance: 0.08, hayPenalty: 5,
  yuckyChance: 0.3,
  lives: 3,
  burpEvery: 10,
  startSpeed: 0.28,
  hungry: true,
};
```

Change something, commit, and GitHub Pages updates the game in a minute or so.
