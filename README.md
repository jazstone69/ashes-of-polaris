# Ashes of Polaris

A free sci-fi strategy RPG that runs entirely in the browser. The first explorers reached the planet Aurelia by following the star Polaris. A thousand years of war later, you found a city in the Central Meridian, hire a team of heroes, and push the Warmonger of Meridian off the map.

**Play:** https://jazstone69.github.io/ashes-of-polaris/

- No server and no account. Progress saves on the player's device, with a downloadable backup file.
- Works offline after the first visit, and can be added to an iPhone or iPad home screen (Share → Add to Home Screen).

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole game (layout, styles and code) |
| `icon.svg`, `icon-*.png` | Logo and home-screen icons |
| `manifest.webmanifest`, `sw.js` | Home-screen install and offline play |

After changing any file, bump `CACHE` in `sw.js` (for example `polaris-v2`) so players get the new version.

Made by Stone Familia Media · https://www.stonefamiliamedia.com
