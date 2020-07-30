```bash
docker run --rm -v $PWD:/workdir paperist/alpine-texlive-ja sh -c "pdflatex root; bibtex root; pdflatex root; pdflatex root"
```
