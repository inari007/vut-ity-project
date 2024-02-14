FILE_NAME=proj1

all:
	latex $(FILE_NAME).tex
	dvips -t a4 $(FILE_NAME).dvi
	ps2pdf $(FILE_NAME).ps

clean:
	rm -f ${FILE_NAME}.{ps,pdf,log,aux,out,dvi}