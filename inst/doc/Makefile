# Makefile for LaTeX files

LATEX	= pdflatex
BIBTEX	= bibtex

SRC	= abcvignette.tex 

all 	: abcvignette.pdf 

%.pdf:	%.tex
	$(LATEX) $*
	$(BIBTEX) $*
	$(LATEX) $*
	$(LATEX) $*
	rm -f Rplots* *.ps abcvignette-* $*.dvi $*.log $*.bbl *.tex $*.aux $*.blg $*.log
