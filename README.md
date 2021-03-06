Using funnel plots and CUSUM techniques to monitor hospital-standardised
mortality
================
Chris Mainey
22/05/2019

This repository contains the slides, a couple of scripts used for my
talk at the Royal Statistical Society Conference 2019, on 5th September
2019.

I did want to share more, but I can’t share patient data, nor anything
that is UHB’s intellectual property. Instead, we will use the Medicare
dataset `medpar` in the `COUNT` package see
[CRAN](https://cran.r-project.org/web/packages/COUNT/index.html) entry.

We will also be using my `FunnelPlotR` package:

``` r
install.packages("FunnelPlotR")
```

You can find it on GitHub
[here](https://cran.r-project.org/web/packages/FunnelPlotR/index.html)
and the package docs [here](https://chrismainey.github.io/FunnelPlotR/)
