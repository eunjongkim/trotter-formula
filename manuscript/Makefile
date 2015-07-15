

LATEXFILES=manuscript


all:
	for i in ${LATEXFILES}; do	        \
		echo "Building $$i...";		\
		(pdflatex $$i.tex < /dev/null);	\
		bibtex $$i;	 	\
		(pdflatex $$i.tex < /dev/null);	\
	done	
	
