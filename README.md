```bash
docker run --rm -v $PWD:/workdir paperist/alpine-texlive-ja sh -c "uplatex root; pbibtex root; uplatex root; uplatex root; dvipdfmx root.dvi"
```
