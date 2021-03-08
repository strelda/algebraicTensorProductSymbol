# algebraicTensorProductSymbol
There was a need for algebraic tensor product symbol in LaTeX

tenzorový součin dvou vektorových prostorů, without any regard k nějaké topologii
semitenzorový hypersoučin na kompaktních direktních algebrách

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
