all: latex pdf

latex:
	./main.py
pdf:
	xelatex -halt-on-error ./out.tex
clean:
	rm -fv out.aux
	rm -fv out.log
	rm -fv out.pdf
	rm -fv out.tex
	rm -fv texput.log
