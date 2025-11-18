# Angular Portfolio (ported)

This folder contains a minimal Angular CLI project that hosts a port of the original static portfolio.

Quick start

1. Make sure you have Node.js installed (v18+ recommended).
2. From this folder (where `package.json` lives) run:

```powershell
cd angular_portfolio
npm install
npx ng serve --open
```

or simply:

```powershell
npm install
npm start
```

Notes
- The original `styles.css` was copied to `src/styles.css`.
- The original `script.js` was copied to `src/assets/script.js` and is included in `src/index.html` to preserve interactive behaviour quickly.
- For a full Angular conversion we can split the template into granular components and port `script.js` into Angular services and lifecycle hooks — tell me if you want that.
