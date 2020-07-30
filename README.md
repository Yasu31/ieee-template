```bash
docker run --rm -it -v $(pwd):/source schickling/latex
pdflatex root; bibtex root; pdflatex root; pdflatex root
```
