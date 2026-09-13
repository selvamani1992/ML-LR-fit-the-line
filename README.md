# Machine Learning - Linear Regression - Fit the Line

An interactive linear regression teaching tool. Drag the slope and intercept
sliders to fit a line to a scatter of data points, watch the residuals and
R² update live, then compare your line to the least-squares best fit.

**[Live demo →](https://selvamani1992.github.io/ML-LR-fit-the-line/)**


## Why

Built for classroom use when teaching linear regression. Students can see,
before any formula is introduced, what "slope" and "intercept" physically do
to a line, and what "minimizing error" means by watching the sum of squared
residuals shrink as they adjust the fit.

## Features

- Drag sliders to change slope (m) and intercept (b) of `y = mx + b`
- Live-updating equation, sum of squared error, and R²
- Toggle residual lines (the vertical gaps being minimized)
- **Snap to best fit** — animates to the true least-squares solution
- **New data set** — generates a fresh random dataset with a different
  underlying slope, intercept, and noise level
- No build step, no dependencies — a single static HTML file

## Running locally

Clone the repo and open `index.html` directly in a browser:

```bash
git clone https://github.com/selvamani1992/ML-LR-fit-the-line.git
cd fit-the-line
open index.html   # or just double-click the file
```

## Tech

Vanilla HTML, CSS, and JavaScript — Canvas 2D for the plot, no frameworks
or build tools. Fonts loaded from Google Fonts (Space Grotesk, JetBrains
Mono).

## License

MIT — feel free to reuse or adapt for your own class.
