# Front End Simple Project

A collection of small front-end projects built with plain **HTML**, **CSS**, and **JavaScript**. Each project is self-contained in its own folder and demonstrates a small, focused UI interaction or utility.

## Projects included

1. **budget-website** — Simple personal budget tracker (income, expenses, balance).
2. **drawing-app** — Canvas-based drawing app with pen, eraser, color and brush size.
3. **e-commerce-website** — Static product listing and simple cart interactions.
4. **leaf-loss-calendar** — A seasonal/leaf-loss calendar visualizer (interactive calendar).
5. **pokemon-card-generator** — Generate printable Pokémon-style cards from inputs.
6. **simple-clock** — Analog and/or digital clock showing the current time.

## How to run

Each project is static — no build or server required. To run a project:

1. Open the project folder.
2. Open `index.html` (or the named entry file) in your browser.

> Tip: For full features in some browsers (e.g., accessing local files), you can run a simple static server from the project folder:

```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

## Recommended structure

```
front-end-simple-project/
├─ budget-website/
│  ├─ index.html
│  ├─ style.css
│  └─ script.js
├─ drawing-app/
├─ e-commerce-website/
├─ leaf-loss-calendar/
├─ pokemon-card-generator/
├─ simple-clock/
└─ README.md
```

## Contribution

If you want to add improvements (bug fixes, accessibility, tests, enhancements):

1. Fork the repo.
2. Create a feature branch: `git checkout -b fix/some-feature`.
3. Commit and push: `git push origin fix/some-feature`.
4. Open a PR describing the change.

## License

This collection uses the **MIT License** by default. Add a `LICENSE` file at repository root if you want to apply it.
