# cdelim.github.io

Developer website for games by Cem Bektaşoğlu, served by GitHub Pages at https://cdelim.github.io.

- `index.html` lists all games.
- `app-ads.txt` is shared by every game. Ad networks read it from the root of the website listed in each store listing. Add each ad network's lines once.
- Each game has its own folder with a game page and a privacy policy, e.g. `junction-jam/privacy-policy.html`.

## Adding a new game
1. Copy the `junction-jam/` folder and rename it (for example `my-new-game/`).
2. Change the name, the description and the list of SDKs in its `privacy-policy.html`.
3. Add a card for the game to `index.html`.
4. In the store listing, use `https://cdelim.github.io` as the website and `https://cdelim.github.io/<folder>/privacy-policy.html` as the privacy policy.
