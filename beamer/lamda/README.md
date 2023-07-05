# Beamer Template for LAMDA

Modified from [NJUAI-Beamer Template](https://github.com/typoverflow/NJUAI-Beamer-Template). Please use `pdflatex` to build and compile your documents. 

To support Chinese, please uncomment line 4-6, like below

```tex
% add Chinses support
\usepackage[UTF8]{ctex}
\ctexset{today=old}
```

Then use `xelatex` to build your `.tex` file.

## Latex-Workshop VSCode plugin (Optional)

Please refer to [使用VSCode编写Latex](https://zhuanlan.zhihu.com/p/38178015) or [Latex-Workshop Wiki](https://github.com/James-Yu/LaTeX-Workshop/wiki).

## Format `.tex` File (Optional)

```bash
latexindent main.tex -o main.tex
```

**Note**: To install `latexindent`, there are two ways:

1. Install `texlive`. Please refer to [NJU-CTAN](https://mirror.nju.edu.cn/help/CTAN) or [NJU-Mirror](https://mirrors.nju.edu.cn/CTAN/systems/texlive/tlnet/), and add `/usr/local/texlive/2022/texmf-dist/scripts/latexindent` to your PATH.
2. Download `latexindent.pl` from [latexindent.pl](https://github.com/cmhughes/latexindent.pl).