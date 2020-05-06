
## An open-source design for a shipping container lab optimised for high-throughput COVID testing

This repository contains the initial literature review for this publication. The document is formatted in latex to make it to format the citations. The folder contains the finished .pdf for review and commenting. The original .tex and .bib files are included for building. The easiest way to build the document is to use sublime text. It usually autodetects .tex files and `cmd` + `b` will build the .pdf file (I usually use pdflatex build engine).

In some cases you may need to add specific style features. theis is done by adding the style package `XXXX.sty` to the directory and simply adding in the header section `\usepackage{XXXX}`. For instance I have included the `authblk.sty` file and this allows an easy implementation of multiple affiliation authors. 

Spell checking is important. This is a [useful stackexchange discussion](https://tex.stackexchange.com/questions/42843/is-there-a-spell-check-package-for-latex) on the topic. I tend to agree with the author who uses terminal spell checkers to complete the task. In this case you might do `aspell -t -c publication.tex` where the `-t` means ignore latex macros. It may be desirable to use a wordlist since scientific terms/jargon are constantly evolving and field specific terms are usually targeted by the checker. 



[A Mendeley group with the related publications](https://www.mendeley.com/community/d6275608-cf07-3f35-819c-1e394ff6fc6d/) has been set up so anyone can easily review the backgorund literature.
