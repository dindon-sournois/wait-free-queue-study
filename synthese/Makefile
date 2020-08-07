all:
	pdflatex main
	bibtex8 --wolfgang main
	pdflatex main
	mv main.pdf llucido-synthese.pdf

clean:
	rm -rf auto/ *.aux *.log *-blx.bib *.bbl *.blg *.dvi *.run.xml *.out
