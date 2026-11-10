# Performance of RIS-Assisted Systems in Mixed Fading Conditions

[![DOI](https://zenodo.org/badge/1452053600.svg)](https://doi.org/10.5281/zenodo.24095338)

Code accompanying the article:

> M. C. Luna Alvarado, C. R. Nogueira da Silva, N. Simmons, P. C. Sofotasios,
> S. L. Cotton, and M. D. Yacoub, "Performance of RIS-Assisted Systems in Mixed
> Fading Conditions," *IEEE Transactions on Communications*, vol. 73, no. 11,
> pp. 12577–12592, Nov. 2025.
> DOI: [10.1109/TCOMM.2025.3581005](https://doi.org/10.1109/TCOMM.2025.3581005)

## Contents

| File | Description | Figures in the paper |
|---|---|---|
| `Figs1-2.nb` | Simulated vs. α-µ approximated PDF of the RIS channel and outage probability | Figs. 1 and 2 |
| `Figs3-4-5.nb` | Average symbol error rate (ASER) under α-µ, κ-µ and extended η-µ fading, with the asymptotic ASER | Figs. 3, 4 and 5 |
| `Fig6.nb` | ASER when the transmitter-RIS, RIS-receiver and direct links experience different fading conditions | Fig. 6 |
| `Fig7.nb` | Outage probability: α-µ approximation vs. central limit theorem (CLT) approximation | Fig. 7 |

Each notebook implements the corresponding expressions of the paper and
generates the figures. [Analytical results are compared against Monte Carlo
simulations included in the notebooks.]

## Requirements

- Wolfram Mathematica 13

## Usage

Open the desired notebook in Mathematica and evaluate all cells
(*Evaluation → Evaluate Notebook*). The figures are generated at the end of
each notebook.

## Citation

If you use this code, please cite the article above:

```bibtex
@article{LunaAlvarado2025TCOM,
  author  = {Luna Alvarado, Maria Cecilia and Nogueira da Silva, Carlos Rafael and Simmons, Nidhi and Sofotasios, Paschalis C. and Cotton, Simon L. and Yacoub, Michel Daoud},
  title   = {Performance of {RIS}-Assisted Systems in Mixed Fading Conditions},
  journal = {IEEE Transactions on Communications},
  volume  = {73},
  number  = {11},
  pages   = {12577--12592},
  year    = {2025},
  doi     = {10.1109/TCOMM.2025.3581005}
}
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
