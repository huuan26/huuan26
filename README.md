<p align="center">
  <a href="https://github.com/huuan26/polars-anta">
    <img src="assets/cyber_quant_banner.svg" alt="Hi, I'm Huu An - Quantitative Researcher" width="100%" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-21262d?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-21262d?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Polars-21262d?style=flat-square&logo=polars&logoColor=white" alt="Polars" />
  <img src="https://img.shields.io/badge/PostgreSQL-21262d?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Linux-21262d?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/NumPy-21262d?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/SciPy-21262d?style=flat-square&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/PyTorch-21262d?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Docker-21262d?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-21262d?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

---

### Open-Source Contributions

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>
        <a href="https://github.com/OpenByteInc/QuantDinger">OpenByteInc / QuantDinger ↗</a>
        <a href="https://github.com/OpenByteInc/QuantDinger">
          <img src="https://img.shields.io/github/stars/OpenByteInc/QuantDinger?style=flat-square&logo=github&color=e3b341&labelColor=21262d" alt="stars" align="right" />
        </a>
      </h4>
      <p><em>Quantitative trading and systematic strategy research framework.</em></p>
      <ul>
        <li><a href="https://github.com/OpenByteInc/QuantDinger/pull/307"><b>PR #307 (Merged)</b></a>: Benchmark analytics (M&sup2;, Dual-Beta, Batting Average)</li>
        <li><a href="https://github.com/OpenByteInc/QuantDinger/pull/306"><b>PR #306 (Merged)</b></a>: Downside risk framework (Sortino, Calmar, Drawdown Recovery)</li>
        <li><a href="https://github.com/OpenByteInc/QuantDinger/pull/303"><b>PR #303 (Merged)</b></a>: Benchmark-relative metrics (Beta, Jensen's Alpha, Treynor)</li>
        <li><a href="https://github.com/OpenByteInc/QuantDinger/pull/300"><b>PR #300</b></a> &middot; <a href="https://github.com/OpenByteInc/QuantDinger/pull/298"><b>#298 (Merged)</b></a>: Multi-timeframe duration & metric annualization</li>
      </ul>
      <p>
        <code>Backtesting Engine</code> &middot; <code>Alpha Pipeline</code> &middot; <code>Time-Series Analytics</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>
        <a href="https://github.com/domokane/FinancePy">domokane / FinancePy ↗</a>
        <a href="https://github.com/domokane/FinancePy">
          <img src="https://img.shields.io/github/stars/domokane/FinancePy?style=flat-square&logo=github&color=e3b341&labelColor=21262d" alt="stars" align="right" />
        </a>
      </h4>
      <p><em>Valuation and risk management of financial derivatives.</em></p>
      <ul>
        <li><a href="https://github.com/domokane/FinancePy/pull/420"><b>PR #420 (Merged)</b></a>: Shifted Black–Karasinski (BKTree) for negative rates</li>
        <li><a href="https://github.com/domokane/FinancePy/pull/408"><b>PR #408 (Merged)</b></a>: Vectorized CDSCurve discount factors & day-count alignment</li>
        <li><a href="https://github.com/domokane/FinancePy/pull/406"><b>PR #406 (Merged)</b></a>: Extended Shifted Black–Derman–Toy tree (BDTTree)</li>
        <li><a href="https://github.com/domokane/FinancePy/pull/404"><b>PR #404 (Merged)</b></a>: Analytical closed-form & Monte Carlo cliquet option valuation</li>
      </ul>
      <p>
        <code>Derivatives Pricing</code> &middot; <code>Short-Rate Trees</code> &middot; <code>Monte Carlo Simulation</code>
      </p>
    </td>
  </tr>
</table>

---

### Research & Technical Notes

- **[Decomposing OLS Linear Regression into WMA/SMA for 100x Speedup in Polars](https://github.com/huuan26/polars-anta)** &mdash; `Oct 2026`  
  *Closed-form mathematical refactoring of rolling least-squares into prefix sums and weighted moving averages.*

- **[Lowdin Symmetric Orthogonalization for Cross-Sectional Alpha Factors](https://github.com/huuan26/OrthoQuant)** &mdash; `Sep 2026`  
  *Eliminating factor multi-collinearity via SVD-based unitary transformation while preserving maximal correlation.*

- **[Shifted Short-Rate Lattices (BK / BDT) in Negative Yield Regimes](https://github.com/domokane/FinancePy/pull/420)** &mdash; `Oct 2026`  
  *Extending log-normal short rate tree dynamics (Black–Karasinski & Black–Derman–Toy) to negative interest rates with state-price calibration.*

---

### Activity & Metrics

<p align="center">
  <a href="https://github.com/huuan26">
    <img src="https://github-readme-stats.vercel.app/api?username=huuan26&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&text_color=8b949e&icon_color=58a6ff&title_color=f0f6fc" alt="GitHub Metrics" height="165" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/huuan26">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=huuan26&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&text_color=8b949e&title_color=f0f6fc&hide=html,css" alt="Top Languages" height="165" />
  </a>
</p>
