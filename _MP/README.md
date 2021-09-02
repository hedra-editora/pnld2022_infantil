README.md
======

```tex
\usepackage{pdfpages}
\includepdf[nup=2x2, 				% grid
			%offset=-15mm -5mm, 	% posição
			scale=.8, 				% tamanho da página
            delta=4mm 4mm, 			
            frame,
            pages={1-4}]{test.pdf}

% Mais info: https://www.physik.tu-cottbus.de/physik/tp1/nutzer/doc/texmf/latex/pdfpages/pdf-ex.tex
```

```tex
\usepackage{pagecolor}
\pagecolor{yellow!30!orange}  % Mais info: https://tex.stackexchange.com/questions/82498/change-background-colour-for-entire-document

```

```tex
\usepackage[printwatermark]{xwatermark}

\newwatermark[pagex=2]{\includegraphics{testc.png}}
\newwatermark[oddpages]{\includegraphics{test.png}}
\newwatermark[evenpages]{\includegraphics{testb.png}}

```

