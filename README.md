# jfp-natbib-hack

The [Journal of Functional Programming (JFP)’s LaTeX styles][JFP] aren’t
compatible with [`natbib`][natbib].  But I like `natbib`!  So this package is a
hack to make `jfp1.cls` and `jfp.bst` compatible with `natbib`.  You have to
include it after including `natbib`.  As a hack, be warned that this package is
probably somewhat fragile.

Usage:

```latex
\documentclass{jfp1}
% ...
\usepackage{natbib}
% ...
\usepackage{jfp-natbib-hack}
% ...
```

[JFP]: https://www.cambridge.org/core/journals/journal-of-functional-programming/information/instructions-contributors
[natbib]: https://ctan.org/pkg/natbib
