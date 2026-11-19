# Lumen Arcade

A free, play-money casino-style arcade: Sky Crash, Orchard Climb, Mine Field, Plinko, Lucky Dice, Fortune Wheel, Gold Slots and Coin Flip.
Credits (LC) have no cash value. There are no deposits, withdrawals or payments.

Static site, no build step.

## Run locally
    npx serve .
or open `index.html` in a browser.

## Deploy to Vercel
1. Push this folder to a GitHub repo, then "Add New Project" in Vercel and import it.
   Framework preset: Other. Leave build command and output directory empty.
2. Or from this folder: `npx vercel --prod`.

## Files
- `index.html` page markup and SVG symbols
- `style.css` all styles
- `app.js` games, wallet, settings and fairness logic
- `vercel.json` headers and clean URLs
