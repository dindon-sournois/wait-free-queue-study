all:
	pdflatex slides
	bibtex8 --wolfgang slides
	pdflatex slides

clean:
	rm -rf auto/ *.aux *.log *-blx.bib *.bbl *.blg *.dvi *.run.xml *.nav *.out *.snm *.toc
