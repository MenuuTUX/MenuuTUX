<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0b1d2a,50:0f3d3e,100:16a34a&text=MenuuTUX&fontColor=ffffff&fontSize=60&fontAlignY=36&desc=portfolio%20construction%20%C2%B7%20backtesting%20%C2%B7%20valuation&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="MenuuTUX: portfolio construction, backtesting, valuation">

<p align="center">
  I build tools for investing decisions: portfolio construction, backtesting, risk simulation and valuation.<br>
  Every number shows its assumptions, and every projection says what it is not.
</p>

<p align="center">
  <a href="https://portfolio-compass.vercel.app"><img src="https://img.shields.io/badge/live%20demo-portfolio--compass-16a34a?style=for-the-badge&logo=vercel&logoColor=white" alt="Live demo"></a>
  <a href="https://github.com/MenuuTUX/Portfolio-Compass/blob/main/docs/example-backtest.md"><img src="https://img.shields.io/badge/case%20study-200--day%20trend%20filter-0f3d3e?style=for-the-badge&logo=googlesheets&logoColor=white" alt="Backtest case study"></a>
</p>

<br>

## Featured: Portfolio Compass

<a href="https://portfolio-compass.vercel.app">
  <img src="https://raw.githubusercontent.com/MenuuTUX/Portfolio-Compass/main/docs/screenshots/01-landing.png" alt="Portfolio Compass landing page" width="100%">
</a>

A free planning tool for Canadians who have just opened a TFSA: check contribution room against CRA limits, compare stocks and ETFs on fees, yield and history, build a portfolio, and test how it would have held up.

- **Backtesting (Compass Lab):** rule-based and coded strategies over daily bars, with next-bar-open fills, slippage and commissions, dividends and rebalancing. Reports CAGR, volatility, Sharpe, Sortino, Calmar, max drawdown, beta, alpha and turnover.
- **Overfitting checks:** every result splits the first 70% and last 30% of history, a walk-forward test refits the rule year by year, and the app warns when many variants have been tried.
- **Risk simulation:** Monte Carlo paths from a portfolio's own covariance, with reshuffle, resample and randomized modes and reproducible seeds.
- **Valuation:** a DCF with WACC built from SEC filings, a regression beta against the market, and readiness checks that refuse to value a company when the inputs are not there.
- **Portfolio construction:** a budget-aware allocator for stock and bond mixes across risk profiles, total return by default, and CAD/USD handled with Bank of Canada FX.

<p><a href="https://github.com/MenuuTUX/Portfolio-Compass/blob/main/docs/example-backtest.md"><b>Case study:</b></a> a 200-day trend filter on SPY from 2005 to 2026 cut maximum drawdown from 55% to 26%, and the benefit disappeared on the hold-out period from 2020. The write-up covers why that result might be wrong.</p>

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Bun-fbf0df?style=flat-square&logo=bun&logoColor=black" alt="Bun">
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Pyodide-3776AB?style=flat-square&logo=python&logoColor=white" alt="Pyodide">
  <a href="https://github.com/MenuuTUX/Portfolio-Compass"><img src="https://img.shields.io/github/last-commit/MenuuTUX/Portfolio-Compass?style=flat-square&color=16a34a" alt="Last commit"></a>
</p>

<br>

## Also built

<sub>Graphics and native tooling from before the finance work.</sub>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MenuuTUX/maya-scene-io">maya-scene-io</a></h3>
      Import and export Maya scenes (.ma / .mb) in Blender.<br><br>
      <img src="https://img.shields.io/github/stars/MenuuTUX/maya-scene-io?style=flat-square&color=16a34a" alt="Stars">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MenuuTUX/LiToStudio">LiToStudio</a></h3>
      Apple's Lito tech, used to make 3D objects on Mac.<br><br>
      <img src="https://img.shields.io/github/stars/MenuuTUX/LiToStudio?style=flat-square&color=16a34a" alt="Stars">
      <img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MenuuTUX/jojo-hftf-native">jojo-hftf-native</a></h3>
      Native macOS port of JoJo's Bizarre Adventure: Heritage for the Future (PS1).<br><br>
      <img src="https://img.shields.io/github/stars/MenuuTUX/jojo-hftf-native?style=flat-square&color=16a34a" alt="Stars">
      <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/MenuuTUX/Zlender">Zlender</a></h3>
      ZBrush for Blender.<br><br>
      <img src="https://img.shields.io/github/stars/MenuuTUX/Zlender?style=flat-square&color=16a34a" alt="Stars">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
    </td>
  </tr>
</table>

<br>

## Toolbox

**Finance:** backtesting · Monte Carlo simulation · DCF and WACC · factor beta · portfolio optimization · SEC EDGAR filings · TFSA rules

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

<br>

<p align="center">🎹 Off the clock I learn songs on the piano.</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:16a34a,50:0f3d3e,100:0b1d2a&section=footer" width="100%" alt="">
