master-book.pdf: master.pdf Makefile
	pdfbook --quiet --signature 52 master.pdf

master-nup.pdf: master.pdf
	pdfnup --quiet master.pdf

clean:
	rm -f *.log *.aux *.toc *.pdf
