# 🎮 Arcade

A small browser arcade: three classic single-file games with a hub to switch between and download them.

## Games

| Game | Description | Controls |
| --- | --- | --- |
| [Ping Pong](pingpong.html) | Rally against the computer and keep the ball in play. | **Mouse** or **←/→** to move the paddle |
| [Snake](snake.html) | Eat, grow, and dodge the walls as long as you can. | **Arrow keys** or **WASD** to steer |
| [Minesweeper](minesweeper.html) | Clear the board without hitting a single mine. | **Click** to reveal, **right-click** to flag |

## Run

No server, build step, or install needed — every game is a single self-contained HTML file.

- Open `index.html` for the hub and pick a game.
- Or open any game file directly (e.g. `pingpong.html`, `snake.html`, `minesweeper.html`).
- Works offline from `file://` and in any modern browser.

## Download

- **Served over `http://` or `https://`:** click **Download** on any game card to save that game file.
- **Opened as a local file (`file://`):** the games are already saved on disk next to the hub, so open any game file directly to play. For a full copy, download the whole repo as a ZIP from GitHub (use **Code ▾ → Download ZIP** on the repo page).

```bash
git clone https://github.com/JonJac-agent/arcade.git
```

### Saving games locally

Each game's **← Arcade** link points back to `index.html`. To keep that link working, save all of the hub's files (`index.html`, `pingpong.html`, `snake.html`, and `minesweeper.html`) into one folder — don't save a single game file into an empty folder on its own.

> **Minesweeper tip:** the **Hard** difficulty uses a wide board, so it's best played on desktop (or a wide screen).
