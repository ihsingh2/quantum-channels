once:
	mkdir -p .tmp/sections
	latexmk -pdf --aux-directory=.tmp/ main.tex

nonstop:
	mkdir -p .tmp/sections
	latexmk -pdf -pvc -interaction=nonstopmode --aux-directory=.tmp/ main.tex

clean:
	rm -rf .tmp/
