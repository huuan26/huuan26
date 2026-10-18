<!-- GitHub Profile README -->

<h1 align="center">Phan Bùi Hữu Ân</h1>

<p align="center">
  <b>Quantitative Researcher | Data Scientist</b><br>
  <i>Bridging rigorous numerical mathematics with systematic quantitative trading and deep learning.</i>
</p>


## Featured Research & Open-Source Projects

### 1. FinancePy (Open-Source Contributor)
**Valuation & Risk Management of Financial Derivatives in Python**  
*Upstream Repository*: [domokane/FinancePy](https://github.com/domokane/FinancePy) &bull; *Merged PRs*: [#404](https://github.com/domokane/FinancePy/pull/404), [#406](https://github.com/domokane/FinancePy/pull/406)  
*Tech Stack*: Python, Quantitative Finance, Analytical Pricing, Short-Rate Trees, Monte Carlo  
- **Shifted Black–Derman–Toy Short-Rate Tree ([PR #406](https://github.com/domokane/FinancePy/pull/406))**:
  - Extended `BDTTree` with shifted lognormal short-rate dynamics $d\ln(r_t + s) = \theta(t)\,dt + \sigma\,dW_t$ ($r_t + s > 0$) to support lattice calibration and fixed-income derivative valuation under negative interest rates (resolving Issue #20).
  - Propagated shifted states $x_{m,i} = r_{m,i} + s$ for root-finding and Arrow–Debreu state price calibration while preserving true short-rate discounting across backward-induction pricers (`bond_option`, `bermudan_swaption`, `callable_puttable_bond_tree`), validated via European bond option put–call parity and zero-volatility shift invariance.
- **Equity Cliquet Option Valuation ([PR #404](https://github.com/domokane/FinancePy/pull/404))**:
  - Extended `EquityCliquetOption` to support periodic local caps/floors and maturity global caps/floors (resolving Issue #221).
  - Derived and implemented analytical closed-form pricing for return cliquets via forward-start vanilla option decomposition under the risk-neutral measure.
  - Implemented multi-period Monte Carlo pricing with exact lognormal state transitions, validated against analytical Black-Scholes spreads with error $< 10^{-12}$.

### 2. ANN-ODE-Solver
**Artificial Neural Networks for Differential Equations in PyTorch**  
*Repository*: [huuan26/ANN-ODE-Solver](https://github.com/huuan26/ANN-ODE-Solver)  
*Tech Stack*: Python, PyTorch, NumPy, Matplotlib  
- Implements deep feed-forward neural network solvers for linear, non-linear, oscillatory, second-order, and coupled ODE systems based on the foundational framework by Lagaris et al. (1998).
- Utilizes hard-constrained trial solution formulations that strictly satisfy initial and boundary conditions analytically, eliminating the need for boundary penalty tuning.
- Employs exact PyTorch computational graph automatic differentiation (`torch.autograd`), achieving over 100x lower error compared to classical Forward Euler integration.


---


## Education

- **Bachelor of Mathematics (Talent Program), Specialization in Numerical Analysis**  
  VNU-HCM University of Science (Đại học Khoa học Tự nhiên - ĐHQG TP.HCM)  
  *Focus*: Numerical Methods, Differential Equations, Optimization, Probability & Mathematical Statistics.

---

## Contact & Links

- **Email**: [phanbuihuuan261103@gmail.com](mailto:phanbuihuuan261103@gmail.com)
- **LinkedIn**: [linkedin.com/in/an-phan-6b6365350](https://www.linkedin.com/in/an-phan-6b6365350/)
- **GitHub**: [github.com/huuan26](https://github.com/huuan26)
- **Location**: Ho Chi Minh City, Vietnam
