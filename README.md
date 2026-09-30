# Pocket Arcade

Twelve self-contained browser games made for Devesh, in one compact responsive library.

## Play locally

Run `python -m http.server 8080 --directory dist`, then open http://localhost:8080. No build, backend, external assets, or paid services are required. The `dist` folder can also be downloaded and opened locally with `index.html`.

Each game is preserved in its own HTML file and runs inside an isolated iframe. Use the Library link or browser Back to return; Restart reloads only the selected game. Desktop full screen keeps the game focused. Original keyboard and touch controls remain inside each game.

Games: Neon Dodge, Echo Sequence, Grapple Climb, Tower Stack, Tiny Tactics, Garden Merge, Prism Breaker, Rail Switch, Circuit Flip, Crate Escape, Gravity Golf, Orbit Courier.

The public website and this private GitHub source repository are separate. Publishing configuration is in `.openai/hosting.json`.

