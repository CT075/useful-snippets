export TEXINPUTS:=$(TEXINPUTS):{texpath}

FILE := {fname}

pdf: $(FILE)
	pdflatex $(FILE) && pdflatex $(FILE)

clean:
	rm *.pdf *.log *.aux *.out

