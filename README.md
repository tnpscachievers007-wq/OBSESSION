# Study Tracker

A single-page app to study 12 hours inside any 24-hour window you start yourself.

- **Study stopwatch** counts up to 12:00:00.
- **Rest countdown** (4 hours) runs only while study is paused.
- **Sleep countdown** (8 hours) has its own mode; sleeping longer than 8 hours uses up rest time.
- **Win** when you reach 12 hours of study. **Lose** when rest runs out or the 24 hours end.
- A green dot means studying, red means resting, blue means sleeping.

## Use it

Open the live page (GitHub Pages) or open `index.html` in Chrome or Edge.

## Controls

| Key | Action |
| --- | --- |
| Space | Start, then switch between study and rest |
| S | Sleep / wake |
| P | Pop out the always-on-top dot (Chrome or Edge 116+) |
| Shift + R | Reset |

Click the dot (in the page or the popup) to switch between study and rest.

With another app in front, use the keyboard's **Play/Pause** media key (study / rest) and **Next track** key (sleep / wake). These work after you press Start in the tab.

Progress is saved in your browser's local storage.

## Host it free on GitHub Pages

1. Create a repository and upload `index.html` and `README.md`.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute, your page is live at `https://<your-username>.github.io/<repo-name>/`.
