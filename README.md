# revtex-markdown-paper

REVTeX paper in markdown using LaTeX.

The paper (`paper.md`) is written in [Markdown](https://daringfireball.net/projects/markdown/) and then translated to LaTeX using [pandoc](http://pandoc.org/) and the `revtex.template`.
References are in `paper.bib` using the [BibTeX](http://www.bibtex.org/) format.

The `Makefile` contains the conversion commands.
If you are on a unix system, call `make paper.pdf` in this directory and it will compile the paper to `pdf` if all dependencies are installed.

## Usage

Make sure you have a working TeX installation and then

1. Install the dependencies

    ~~~{bash}
    conda-env create -f environment.yml
    ~~~
2. Clone this repository

    ~~~{bash}
    git clone https://github.com/basnijholt/revtex-markdown-paper.git
    ~~~
3. Write paper in `paper.md`, refs in `paper.bib`, compile with `make paper.pdf`

The file `paper.md` contains example code for tables, figures, equations, references and so on.
