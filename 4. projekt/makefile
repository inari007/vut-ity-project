FILE_NAME=proj4

all:
	latex $(FILE_NAME).tex
	bibtex $(FILE_NAME).aux
	latex $(FILE_NAME).tex
	latex $(FILE_NAME).tex
	dvips -t a4 $(FILE_NAME).dvi
	ps2pdf $(FILE_NAME).ps

clean:
	rm -f ${FILE_NAME}.{ps,pdf,log,aux,out,dvi}