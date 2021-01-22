```bash
docker run --rm -it -v $(pwd):/source schickling/latex
pdflatex root; bibtex root; pdflatex root; pdflatex root
```

After each push to GitHub, it is compiled in GitHub's CI (GitHub Actions) as well
