## A Standard LaTeX Presentation Template ##

(A follow-up to my [latex-paper-template](https://github.com/hrs/latex-paper-template))

Every time I set up a new `LaTeX` presentation in Beamer, I need to copy over my usual `Makefile`, set up a git repo, create an empty document, and relearn `BibTeX`. That's tedious.

Cloning this repo is much easier.

### Prerequisites ###

I've used this setup successfully on Macs, FreeBSD, and a few Linuxes. It might work on Cygwin, but I haven't tested it.

You'll need:

- `LaTeX`
- `make`
- `git`

### Installation ###

`git clone https://github.com/hrs/latex-presentation-template.git YOUR_PROJECT_NAME`

I've creatively named the default project `presentation`. If you want to change that, rename the `presentation.tex` and `presentation.bib` files, fix the bibliography reference in `presentation.tex`, and change the value of the `project` variable in the `Makefile`.

### Usage ###

`make`
: Build the project, generating a `pdf`.

`make clean`
: Deletes files created by `LaTeX` (`aux`, `dvi`, `pdf`, etc.)

`make fresh`
: Delete intermediate files and rebuild. Equivalent to `make clean && make`

### "This is stupid, why don't you just..." ###

Nah, I like my setup. Shush.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/hrs/latex-presentation-template/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

