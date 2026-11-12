# 👶 Calm the Baby

A fast browser game where a baby is crying and you have to work out why. Read the thought bubble, pick the right task, win the mini-game, and get the baby to sleep before the neighbours knock on the door.

### 🎮 [Play it now](https://jyotisihagjaat.github.io/calm-the-baby)

## The goal

Meet **15 needs** to put the baby to sleep. If the meltdown bar reaches 100%, you lose.

## How to play

1. Look at the bubble under the baby. It shows what the baby needs right now.
2. Pick the matching task from the five buttons. A wrong choice makes the baby cry more.
3. Win the mini-game for that task.
4. Each finished task calms the baby and brings the next need.

| Task   | Mini-game                                   |
| ------ | ------------------------------------------- |
| Feed   | Press and hold the bottle                   |
| Change | Tap quickly                                 |
| Rock   | Tap left and right in turn                  |
| Play   | Tap quickly (progress fades if you slow down) |
| Burp   | Short burst of taps                         |

## Difficulty

- The baby cries faster with every need you meet.
- After a few rounds, **two needs can appear at once**, so you must decide which one to handle first.
- Your best result is saved in your browser.

## Built with

- HTML, CSS and vanilla JavaScript
- `requestAnimationFrame` game loop
- Pointer events for mouse and touch input
- `localStorage` for the best score
- GitHub Pages for hosting
- Works on phones and desktops, with dark mode support

## Run it locally

```bash
git clone https://github.com/jyotisihagjaat/calm-the-baby.git
cd calm-the-baby
```

Open `index.html` in any browser. Nothing to install.

## What I learned

- Writing a game loop with a delta-time update
- Building different mini-games with one input system (hold, tap and alternate)
- Balancing difficulty so it rises gradually
- Managing game states: ready, playing, won and lost
- Shipping a finished project with GitHub Pages

## Roadmap

- [ ] Sound effects and a lullaby
- [ ] More needs (teething, too hot, too cold)
- [ ] Levels with different babies
- [ ] Online leaderboard

## Contributing

Ideas and pull requests are welcome. Open an issue if you have a new need or mini-game idea.

## License

MIT
