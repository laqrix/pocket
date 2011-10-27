.PHONY: all
all: pocket3.pdf

%.pdf: %.tex
	pdflatex $*

pocket1.pdf: example.pdf
pocket2.pdf: pocket1.pdf
pocket3.pdf: pocket2.pdf

.PHONY: clean
clean:
	-rm -f example.pdf pocket1.pdf pocket2.pdf pocket3.pdf
	-rm -f *.aux *.log
