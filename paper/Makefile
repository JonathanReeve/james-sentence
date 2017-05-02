james-sentence.pdf: james-sentence.md
	pandoc -o $@ $< \
		--latex-engine=xelatex \
		-V colorlinks \
		-V mainfont='Linux Libertine O' \
		--filter pandoc-crossref \
		--filter pandoc-citeproc
	GDK_SCALE=0 zathura $@ &
