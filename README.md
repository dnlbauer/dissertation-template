# A tufte-derived Dissertation/Thesis LaTeX-template
A LaTeX-template that can be used for dissertations. I developed
this template while writing my own PhD thesis. You can see the template in use
here: [Example](https://tuprints.ulb.tu-darmstadt.de/18611/)

### Requirements:
- texlive-full
- biber (for biblatex)
- latexmk, xelatex
- Fonts: Vollkorn (http://vollkorn-typeface.com), Gillius ADF No2 (https://blogfonts.com/gillius-adf-no2.font)

### Compilation

Compile with `latexmk` (there is a  `.latexmkrc`):
```bash
latexmk thesis.tex -pdf
```

or use ninja:
```bash
ninja thesis.pdf
```

### License
Copyright 2017–2021 by Daniel Bauer.

This template uses a modified version of the original [tufte-latex](https://github.com/Tufte-LaTeX/tufte-latex)
template which was published under the Apache 2.0 License, so this work will also use it.
