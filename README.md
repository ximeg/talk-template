# talk-template
LaTeX template for a presentation

## Features
This template produces three output files:
 * **main-beamer.pdf** – the presentation itself
 * **main-article.pdf** – article version
 * **handout.pdf** – printable version of presentation

## How to use
1. Fill in info about talk (author, company, title) into the **preamble.tex**
2. Place your slides into **main.tex** and images to **img/** folder
3. Run `./compile.sh` to get output
4. Clean intermediate files using *git*: `git clean -xf -e '*.pdf'`

## Requirements
* **TexLive** (ideally full version)
* **xelatex** if you use fancy fonts
* **Libertine Open Fonts** are used by default
  (in particular the *Linux Biolinum* font)
* **latexmk** to run *compile.sh* script
* [optional] **python** to run *authors.py* script. This script is used to
  produce two different list of authors with affiliations from a single
  database.



