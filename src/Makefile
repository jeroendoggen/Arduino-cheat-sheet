ALL: Arduino-Cheat-Sheet.pdf

%.pdf: %.tex Makefile
	pdflatex $< &&	pdflatex $< && pdflatex $<

clean:
	  rm -f *.aux *.bbl *.blg *.log Arduino-Cheat-Sheet.pdf *.aux *.bit *.blg *.bbl *.lof *.log *.lot *.glo *.glx *.gxg *.gxs *.idx *.ilg *.ind *.out *.url *.svn *.toc *.nav *.snm *.backup
	  
