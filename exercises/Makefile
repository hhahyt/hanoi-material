# ./Makefile

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

LATEX:=lualatex
#LATEX_OPTIONS:=
LATEX_OPTIONS:=-shell-escape

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

default: exam

exam:
	@$(LATEX) $(LATEX_OPTIONS) exam

ex7:
	@$(LATEX) $(LATEX_OPTIONS) ex7

ex9:
	@$(LATEX) $(LATEX_OPTIONS) ex9

.PHONY: clean

clean:
	@rm -f ex*-blx.bib \
	       ex*.aux \
	       ex*.out \
	       ex*.auxlock \
	       ex*.bbl \
	       ex*.blg \
	       ex*.log \
	       ex*.pdf \
	       ex*-figure*.pdf \
	       ex*-figure*.log \
	       ex*-figure*.dpth \
	       ex*.snm \
	       ex*.nav
	@rm -f sol*-blx.bib \
	       sol*.aux \
	       sol*.out \
	       sol*.auxlock \
	       sol*.bbl \
	       sol*.blg \
	       sol*.log \
	       sol*.pdf \
	       sol*-figure*.pdf \
	       sol*-figure*.log \
	       sol*-figure*.dpth \
	       sol*.snm \
	       sol*.nav
	@rm -f exam*-blx.bib \
	       exam*.aux \
	       exam*.out \
	       exam*.auxlock \
	       exam*.bbl \
	       exam*.blg \
	       exam*.log \
	       exam*.pdf \
	       exam*-figure*.pdf \
	       exam*-figure*.log \
	       exam*-figure*.dpth \
	       exam*.snm \
	       exam*.nav
	@rm -f missfont.log \
	       x.log
	@rm -f *~
