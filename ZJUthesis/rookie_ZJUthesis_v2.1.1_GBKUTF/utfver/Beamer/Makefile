FileName=thesisPPT
PDFPara=
TEXPara= -synctex=-1

$(FileName).pdf : $(FileName).tex
	xelatex $(TEXPara) $(FileName)
	xelatex $(TEXPara) $(FileName)

clear :
	-rm $(FileName).aux
	-rm $(FileName).log
	-rm $(FileName).pdf
	-rm $(FileName).toc
	-rm $(FileName).idx
	-rm $(FileName).nav
	-rm $(FileName).out
	-rm $(FileName).bbl
	-rm $(FileName).lof
	-rm $(FileName).lot
	-rm $(FileName).snm
	-rm $(FileName).blg
	-rm $(FileName).synctex.gz
	-rm $(FileName).synctex

