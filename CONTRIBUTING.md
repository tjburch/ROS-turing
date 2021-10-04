# Contributing

Contributions are welcome! Please read below for information.

## Philosophy

My philosophy in this conversion was to prioritize the following, in the order given:

1. True-to-text Model Conversion
2. True-to-text Figures
3. Instructive Julian code, clear DataFrames.jl manipulation
4. Copy original variable names, follow code progression of [original notebooks](https://avehtari.github.io/ROS-Examples/examples.html) line-by-line.

So, for example, if data manipulation in the original notebook could be reproduced in a more instructive way via DataFrames, I elected to do that.

If your changes improve on any of these points, please make a PR! Fully describe the changes and how they improve the codebase. If you've ported a notebook from the source code that hasn't been ported yet, that contribution is absolutely welcome too.

## Figure Style

For most cases of plots, [Plots.jl](https://docs.juliaplots.org/latest/) is used. For the sake of simplicity, the use the default `GR` backend.

Other plotting packages can be considered on a use-by-use basis (e.g. if plotting a map for example). If a different package is necessary, please note it in the PR.