# Henry Hub Futures Option Pricing

Master's thesis on pricing European plain-vanilla options on Henry Hub natural-gas futures with a volatility specification designed to reproduce hump-shaped mid-tenor variance patterns.

Published with the author's consent. The thesis reports results derived from Eikon Refinitiv market data; no raw licensed dataset is included in this repository.

## Contribution

The thesis develops a commodity-futures term-structure model that preserves lognormal futures-price dynamics while enriching the deterministic volatility function. The resulting specification is designed to capture hump-shaped behavior observed in natural-gas markets.

The work includes:

- A closed-form framework for European plain-vanilla futures options.
- Analytical expressions for the principal Greeks.
- In-sample comparison against two established benchmark specifications.
- A study of Greeks-based option-price approximations.
- Empirical evaluation using Henry Hub futures and option observations from January 2020 through May 2025.

## Paper

[Download the thesis PDF](paper/Henry_Hub_Futures_Option_Pricing.pdf)

The repository copy has a shorter external filename for GitHub. Its PDF bytes are unchanged from the source document.

## Citation

BibTeX citation metadata is available in [CITATION.bib](CITATION.bib).

## Reproducibility

The available source material contains the thesis PDF but not the underlying data, calibration scripts, or LaTeX source. This repository therefore documents the research but does not currently provide a reproducible computational package. Those assets should be added only if the author owns them and has the right to distribute any required data or derived files.

## Authors and academic context

- Author: Luis Berruguete
- Master's in Quantitative Finance and Banking
- Universidad Complutense de Madrid, 2024-2025
- Supervisors: M. Carme Frau (UIB) and M. Dolores Robles (UCM)

## License

No license has been selected. The absence of a license means reuse rights are not granted.

See [PUBLICATION_REVIEW.md](PUBLICATION_REVIEW.md) for the authorship and data-provenance record.
