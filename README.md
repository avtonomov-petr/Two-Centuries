# Two Centuries of Russian Regional Dualism: Spatial Anatomy of Income Inequality in 1904 vs. 2025

[![License: MIT](https://shields.io)](LICENSE)

This repository contains the reproducible Python/Jupyter pipeline, high-resolution figures, open-access Global Price and Income History Group (GPIHG) and Rosstat EMISS datasets, and LaTeX manuscript sources for the study:

> **Avtonomov, P. (2026g).** *Two Centuries of Russian Regional Dualism: Spatial Anatomy of Income Inequality in 1904 vs. 2025.*

This work concludes a seven-part empirical audit of Russian and Eurasian market integration from 1700 to 2025 alongside [doi:10.5281/zenodo.24436177](https://doi.org), [doi:10.5281/zenodo.24461586](https://doi.org), [doi:10.5281/zenodo.24498028](https://doi.org), [doi:10.5281/zenodo.24508139](https://doi.org), [doi:10.5281/zenodo.24530102](https://doi.org), and [doi:10.5281/zenodo.24532590](https://doi.org).

## Key Empirical Findings

* **From Two Capitals to a Resource-Capital Archipelago ($\mathrm{PR}_{\mathrm{reg}}$ Doubles):** On an identical six-indicator distributional panel, spatial localization decreases substantially over 121 years: $\mathrm{PR}_{\mathrm{reg}}(u_1)$ rises from `0.072` (`1904`, $N = 50$) to `0.161` (`2025`, $N = 87$). While `Sankt-Peterburg` (`38.65%`) and `Moskva` (`25.29%`) captured `63.9%` of Mode 1 energy in 1904, the top two regions in 2025 (`Chukotka AO` `14.82%` and `Yamalo-Nenets AO` `13.61%`) capture `28.4%`, forming a five-pole resource-capital core (`Chukotka`, `Yamalo-Nenets`, `Nenets`, `Moscow`, `Tyumen`) accounting for `50.9%` of spatial energy.
* **Robustness Within European Russia ($N = 58$):** Restricting the 2025 sample strictly to European Russia confirms that spatial diffusion is structurally robust: $\mathrm{PR}_{\mathrm{reg}}(u_1) = 0.131$, with `Nenets AO` (`22.48%`) matching `Moscow` (`22.44%`) and `St. Petersburg` moderating to `6.20%`.
* **Intra-Regional Gini Compression vs. Inter-Regional Income Divergence:** Maximum regional Gini fell from `0.611` (`St. Petersburg`, 1904) to `0.470` (`Yamalo-Nenets AO`, 2025) as cross-regional median Gini rose from `0.312` to `0.382` ($\mathrm{PR}_{\mathrm{feat}}(v_1) = 0.989$), while the richest-to-poorest regional per capita income ratio widened from `3.03x` (1904) to `7.10x` (2025).

## Repository Contents

* `reproduce_two_centuries.ipynb` / `reproduce_two_centuries.py` — End-to-end reproducible Python pipeline generating all summary metrics, 95% subsampling bootstrap confidence intervals, and `300 dpi` figures.
* `Figure_1_Russia2025.png` — Top 10 regional Mode 1 energy shares in 1904 (`N = 50`) and 2025 (`N = 87`), two-mode structural map of 87 Russian regions in 2025, and regional Gini distributions.
* `Figure_2_Russia2025.png` — Regional Gini vs. relative mean income across two centuries (`1904` vs. `2025`) and comparison of spatial localization across `1904`, all `2025` regions (`N = 87`), and strictly European `2025` regions (`N = 58`).
* `Two_Centuries_of_Russian_Regional_Dualism.pdf` / `main.tex` — Compiled preprint and LaTeX manuscript source.
* `1904_Medium-ineq_distrib_14dec'11.xlsx`, `gini.xls`, `mean_inc.xls` — Open-access GPIHG (1904) and Rosstat EMISS (2025) source datasets.

## License

Code is released under the MIT License; manuscript text and figures are licensed under [CC BY 4.0](https://creativecommons.org).
