# Spelling Practice

A spelling practice game for Alina and Monty. Two games (Word Scramble and Memory Flash), stars, weekly badges, and three themes, including Wild Woods and Crystal Shrine.

## How it works

This is a single file, `index.html`. There's no server, no account, no sign-in. Open it in a browser and it runs.

Progress (word lists, scores, badges, theme choice) saves to the browser's own local storage, the same way the chess game does. That means:

- It's saved per browser, on the device it was played on. Alina's list on the iPad stays on the iPad. It doesn't travel to a phone or a different browser automatically.
- Whoever opens the page on their own device gets their own separate save. If Sonia opens it on her laptop, her session is independent of yours, same as with the chess game.
- If a browser's storage is cleared (private/incognito mode, "clear browsing data", or similar), that device's saved progress is gone. There's no backup copy anywhere else.

If everyone playing needs to see the same shared progress from any device, this version isn't set up for that. This is "the same game, works anywhere, remembers you on that device."

## Hosting on GitHub Pages

1. Push this file to a repo (public or private, either works for Pages).
2. In the repo, go to Settings → Pages, set the source to the branch and root folder this file lives in.
3. GitHub gives you a URL like `https://yourusername.github.io/reponame/`. That's the link to share.

No build step, no dependencies. It's one HTML file with everything inlined, aside from the Google Fonts it loads over the internet, so it needs an ordinary internet connection to look right (it'll still work offline, just with fallback fonts).

## Files

- `index.html` — the game itself.
