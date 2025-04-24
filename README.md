# Adrian Padin's Resume
My resume, updated periodically. Latest version is [AdrianPadinResume.pdf](AdrianPadinResume.pdf)

## Building with LaTeX
You can generate the PDF yourself from the TeX files.

### Installing LaTeX Compiler

On Windows you will need to download and install a LaTeX compiler. I recommend [MiKTeX](https://miktex.org/download).

On Ubuntu/Debian Linux you can install the most common LaTeX distribution with this command:

```
sudo apt install texlive-latex-extra texlive-bibtex-extra texlive-science
```

### Building from Source

To get the source files, you can either clone this git repository or download
the files. At the bare minimum you need `AdrianPadinResume.tex` and `res.cls`.

Place both of these files in the same folder. Then open your respective
terminal and type in the following command:

```
pdflatex AdrianPadinResume.tex
```

This will generate a file named `AdrianPadinResume.pdf` in the same folder.
