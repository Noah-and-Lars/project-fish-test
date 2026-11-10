# Project Fish (test site)

A test copy of Project Fish, published here so it can be seen and played before it goes live on The Arcade
(https://noah-and-lars.github.io/projects/).

Open it at https://noah-and-lars.github.io/project-fish-test/

- **The home page** (`index.html`, with `arcade.css`, `games.js`, the logo and icons) looks like The Arcade's home page,
  so you can see Project Fish's cover among the other games: the featured banner, the game grid with search and
  category filters, the NEW and UPDATED badges and "What's new". The other games' covers load from the real arcade,
  and their tiles open them there. Nothing on this site connects to the arcade's server: no accounts, no chat, no
  live player counts (the Global chat, Players and Sign in links go to the real arcade).
- **The play page** (`play.html?game=project-fish`, with `intro.js`) plays Project Fish in a frame the way the real
  arcade's play page does, with the keys under it.
- **The game** is in `project-fish/` (its `index.html`, `style.css`, `src/`, `assets/` and `package.json`). It can also
  be opened on its own at https://noah-and-lars.github.io/project-fish-test/project-fish/

The game is copied from the work-in-progress branch `claude/youthful-pascal-llzq29` of
[Noah-and-Lars/projects](https://github.com/Noah-and-Lars/projects). Don't edit it here: changes are made on that
branch and copied over. The arcade's look (`arcade.css`, `intro.js`, the logo and icons) is copied from the branch
the real arcade is published from.

Last copied from Noah-and-Lars/projects branch claude/youthful-pascal-llzq29 at dadb461 (main menu over a live
night-city scene).

To try it locally: `python3 -m http.server 8000` in this folder, then open http://localhost:8000/.

Third-party models are credited in the game (the credits on the start screen).
