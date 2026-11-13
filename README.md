# vader

A lexicon- and rule-based sentiment analysis tool (VADER, Valence Aware Dictionary and sEntiment Reasoner) tuned to social media text.

Compatibility updates by Renova.

Version 0.2.1.9001 changes only the packaged `NEWS.md`: its plain-text headings and numbered items were rewritten as Markdown headings and lists. No R code, data or `DESCRIPTION` field was changed other than the Renova version and attribution line.

## Install

From R-universe:

```r
install.packages("vader", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/vader@renova-0.2.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

vader was written by Katherine Roehrick (maintainer). License: MIT + file LICENSE (see [LICENSE](LICENSE) and [LICENSE.md](LICENSE.md)).
