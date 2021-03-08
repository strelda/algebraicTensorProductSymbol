# Algebraic tensor product symbol
There was a need for algebraic tensor product symbol in LaTeX, so here it is.

tensor product of two vector spaces, without any regard to topology
semitenzor hypermultiplication on compact direct algebras

```
\documentclass{article}
\usepackage{xcolor}
\usepackage{mathtools}

\newcommand{\halfW}{\mathrlap{\otimes}\raisebox{2.5pt}{\textcolor{white}{\rule{8pt}{5pt}}}}
\newcommand{\atprod}{\mathrlap{\halfW}{\times}}

\begin{document}
$$ \atprod $$
\end{document}
```

![img](https://github.com/strelda/algebraicTensorProductSymbol/blob/main/alprod.png?raw=true)
