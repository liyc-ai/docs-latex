# Compile

We provide two ways to compile:

1) Using latexmk

```bash
latexmk -r latexmkrc main.tex
```

2) Using xelatex and bibtex

```bash
xelatex -synctex=1 -output-directory=./ main
bibtex main
xelatex -synctex=1 -output-directory=./ main
xelatex -synctex=1 -output-directory=./ main
```
