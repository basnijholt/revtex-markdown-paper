---
title:  'Great and certainly not overstated contribution to the literature'
journal: 'Journal of Good Research'
author:
- name: Bas Nijholt
  affiliation:
    - TU Delft
    - Station Q
  email: bas@nijho.lt
- name: Anton Akhmerov
  affiliation:
    - TU Delft
  email: i@antonakhmerov.org
abstract: |
  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
bibliography: references.bib
acknowledgements: |
  We'd like to thank ...
contribution: |
  B.N. created the template with input from J.W.
  A.A. is a place holder.
  All authors looked at the manuscript.
...

# Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt **mollit anim id est** laborum.


<!---
Comments look like this and do not show up in the PDF
-->

References are cited as [@nijholt2016orbital].

# Methods

Footnotes can be entered using this code[^1].

[^1]: a footnote

Figures are included like this.

![This is gonna be the caption.](figures/dummy.pdf){#fig:dummy}

And referenced from here as Fig. @fig:dummy.

Complex tables can use standard LaTeX code as this one.

Equations can be used inline $y=\beta_0 + \beta_1 x + \epsilon$ or as usual $$f(x)=\frac{1}{x}$${#eq:example_eq} and referenced with Eq. \eqref{eq:example_eq}.


<!---
Table in LaTeX format because of fancy formatting
-->

\begin{table}[ht]
  \begin{center}
    \caption{Your first table.}
    \label{tab:table1}
    \begin{tabular}{l|c|r}
      \textbf{Value 1} & \textbf{Value 2} & \textbf{Value 3}\\
      $\alpha$ & $\beta$ & $\gamma$ \\
      \hline
      1 & 1110.1 & a\\
      2 & 10.1 & b\\
      3 & 23.113231 & c\\
    \end{tabular}
  \end{center}
\end{table}

# Results

# Discussion

# References
