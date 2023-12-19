

doc:
	pdflatex Ethik.tex
	bibtex Ethik.aux
	pdflatex Ethik.tex
	pdflatex Ethik.tex

pres:
	pdflatex ppp.tex
	bibtex ppp
	pdflatex ppp.tex
	biber ppp
	pdflatex ppp.tex
	pdflatex ppp.tex

clean:
	rm *.aux *.bbl *.log *.blg *.fls *.fdb_latexmk *.nav *.out *.snm *.toc *.bcf *.run.xml *.synctex.gz
