# Custom CV style 
This repository contains a custom CV-style sheet for latex and an example tex file with an example on how to use this specific style.

## Quick guide
Make a new tex file and add the following lines

```latex
% Preamble
\documentclass[10pt]{article}

% Packages
\usepackage{lebenslauf/cvstyle}

\begin{document}
    % Define the necessary parameters here, before the command '\printcv'
    % ...
    
    \printcv
\end{document}
```

## Colors
The default colors are:
````latex
\definecolor{highlightcolor}{RGB}{125,0,0}
\definecolor{leftpanelcolor}{RGB}{75,79,79}
\definecolor{leftpaneltextcolor}{RGB}{0,0,0}
\definecolor{rightpanelcolor}{RGB}{192,192,192}
\definecolor{maintextcolor}{RGB}{0,0,0}
````

Each one can be overwritten with the following lines:
````latex
\definecolor{highlightcolor}{RGB}{50,0,0}
%...

\begin{document}
\end{document}
````

## Example
The tex file is [src/example.tex](src/example.tex) with the generated pdf [out/example.pdf](out/example.pdf).
