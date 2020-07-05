XEL=xelatex
PDF=pdflatex
CMP=$(PDF)
BIB=bibtex
LATEXOBJS= *.aux *.log *.out *.pdf *.bbl *.blg

RHEADER=flashcards
RSRCS=$(RHEADER).tex

.PHONY: clean flashcards

all: flashcards

flashcards:
	$(CMP) $(RSRCS)

clean:
	rm -rf $(LATEXOBJS)
