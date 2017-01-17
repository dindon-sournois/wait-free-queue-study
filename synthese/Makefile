all:
	pdflatex main
	bibtex8 --wolfgang main
	pdflatex main

clean:
	rm -rf auto/ *.aux *.log *-blx.bib *.bbl *.blg *.dvi *.pdf *.run.xml
