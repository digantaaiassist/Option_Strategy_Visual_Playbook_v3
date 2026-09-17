OPTION STRATEGY VISUAL PLAYBOOK — PWA

This version is designed as a visual quick-reference based on the uploaded 36-page option notes.

FEATURES
- Select market condition, volatility context and expected movement.
- Automatically filter strategies documented in the notes.
- Open a strategy to see:
  1) Schematic option chain: CALLS on the left, PUTS on the right, STRIKE in the middle.
  2) Animated BUY/SELL highlighting of the strategy legs.
  3) Payoff graph image taken from the notes where available.
  4) Deployment condition and execution steps.
  5) Animated adjustment flow showing trigger -> action -> resulting positioning.
  6) Risk / important points and source page references.

IMPORTANT
The option-chain visual is schematic, not live market data. Relative strike labels (ATM, ATM+1, ATM-1 etc.) are visual aids only. The app does not fetch live option-chain prices or Greeks.

SOURCE FIDELITY
The detailed strategy rules and adjustment rules are based on the uploaded notes. Strategies that are only named in the notes are intentionally not given invented execution or adjustment rules.

GITHUB PAGES
1. Extract the ZIP.
2. Upload the contents of Option_Strategy_PWA/ to a GitHub repository (index.html must be in the published root).
3. Go to Settings -> Pages.
4. Select Deploy from branch -> main -> /(root).
5. Save and open the generated GitHub Pages URL.

LOCAL TEST
Because service workers generally require localhost/HTTPS, run a simple local web server in the folder, for example:
python -m http.server 8000
Then open http://localhost:8000/
