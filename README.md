# My CV in LaTeX
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/elahe-dastan/elahe-dastan.pdf/latex?label=latex&logo=github&style=flat-square)

The resume typesetting is done in XeLaTeX.

# Output File
Note that the final file will be in the build folder named: **_CV.pdf_**

# Requirements
* Up to date TeX distribution like TexLive

# How to Compile
Run the following command in a terminal:

`xelatex -synctex=1 -shell-escape --output-directory=build -interaction=nonstopmode  CV.tex`
