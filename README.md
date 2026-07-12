# World Convergence Simulator — β & σ Convergence · Economic Development 2000–2025

**Interactive world map simulator exploring economic convergence theory: β-convergence, σ-convergence, and convergence clubs across 122 countries from 2000 to 2025.**

![Version](https://img.shields.io/badge/version-1.0.0-gold)
![License](https://img.shields.io/badge/license-MIT-blue)
![Built With](https://img.shields.io/badge/built%20with-D3.js%20%7C%20Chart.js%20%7C%20TopoJSON-0a1119)

## 🌍 Overview

A professional-grade, interactive world map simulation dashboard that models economic convergence — the tendency for poorer economies to grow faster than richer ones — across 122 countries using real data from the World Bank, Penn World Table, and UNDP.

Built with an **Economist magazine aesthetic**: dark theme, Playfair Display typography, gold accents, and publication-quality data visualization.

## 🎛️ Features

- **β-Convergence Engine**: Log-linear regression (Barro regression) — log initial values vs. annualized growth rates, with real-time R² and β coefficient
- **σ-Convergence Monitor**: Coefficient of variation, Gini coefficient, and Theil index tracked across 2000–2025
- **Convergence Clubs Map**: D3.js choropleth classifying countries into four clubs: Fast Catch-Up, Moderate Catch-Up, Stagnant, Diverging
- **3 Convergence Lenses**: GDP per Capita (PPP), Human Development Index, Trade Openness
- **Adjustable Parameters**: β convergence speed and club sensitivity sliders
- **Flexible β Range**: Select base year (2000/2005/2010) and end year (2015/2020/2025) for regression
- **Time Slider**: Animate through 2000–2025 with play/pause and variable speed
- **Country Detail Panel**: Convergence trajectory, frontier gap analysis, club membership
- **Global KPI Dashboard**: β coefficient, σ trend, 90/10 ratio, Gini, country counts by club
- **Live Rankings**: Top 15 fastest-converging countries by catch-up score
- **Keyboard Navigation**: Arrow keys for year stepping, Space for play/pause
- **Responsive**: Three-panel layout adapts to desktop and tablet

## 🧠 Methodology

| Framework | Application |
|-----------|------------|
| **β-Convergence** (Barro & Sala-i-Martin, 1992) | Log(initial) vs. growth regression — negative slope = convergence |
| **σ-Convergence** (Quah, 1996) | Dispersion metrics (CV, Gini, Theil) over time — falling = convergence |
| **Convergence Clubs** (Quah, 1997; Pritchett, 1997) | Multi-modal distribution — countries cluster into convergence regimes |

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/Hunterhghs/World-convergence-simulator.git
cd World-convergence-simulator

# Open in browser (zero build step!)
open index.html
```

Or visit the live deployment at:
**https://hunterhghs.github.io/World-convergence-simulator/**

## 📊 Data Sources

- **GDP per Capita**: World Bank, Penn World Table (PPP constant 2017 international $)
- **Human Development Index**: UNDP Human Development Reports
- **Trade Openness**: World Bank (trade % GDP)
- **Geography**: Natural Earth 110m via TopoJSON

## 🛠️ Tech Stack

- **D3.js v7** — Map projection, choropleth rendering, zoom/pan
- **TopoJSON** — World geography (Natural Earth 110m)
- **Chart.js v4** — β-convergence scatter, σ-convergence time series
- **Vanilla JS** — Convergence engine, club classification, state management
- **Zero build step** — Single self-contained HTML file

## 📁 Project Structure

```
├── index.html          # Main application (self-contained)
├── favicon.svg         # H Heuristics favicon
├── fable.toml          # Veles/Fable-5 AI agent config
├── .gitignore
└── README.md
```

## 🏗️ Built With

- **Reasonix** — AI-powered development environment
- **Veles** (Fable-5 × DeepSeek) — Hybrid AI agent pipeline for verification
- **H Heuristics Design System** — Economist aesthetic, dark theme

## 📝 License

MIT — H Heuristics 2025

## 🔗 Links

- [H Heuristics](https://hheuristics.com)
- [Hunter Hughes on Substack](https://hheuristics.substack.com)
- [GitHub Profile](https://github.com/Hunterhghs)
