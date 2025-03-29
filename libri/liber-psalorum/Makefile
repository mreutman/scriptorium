all: latex pdf

latex:
	./main.py
pdf:
	xelatex -halt-on-error ./out.tex
clean:
	rm out.aux
	rm out.log
	rm out.pdf
	rm out.tex
	rm texput.log
