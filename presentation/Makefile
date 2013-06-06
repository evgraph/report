all: presentation.pdf speech.pdf

clean:
	/bin/rm -f *.mps *.gps *.log *.aux *.toc *.dvi *.ps *.pdf *.nav *.snm *.out *.vrb *.mpx

presentation.pdf: presentation.tex ../resources/*/* ../resources/*
	rubber -d presentation.tex
	/bin/rm -rf *.log *.aux *.toc  *.ps *.nav *.snm *.out *.mps *.vrb *.mpx *.gps

speech.pdf: speech.tex
	rubber -d speech.tex
	/bin/rm -rf *.log *.aux *.toc  *.ps *.nav *.snm *.out *.mps *.vrb *.mpx *.gps
