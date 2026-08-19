### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex nguyen_ethan_resume.tex
```

### Build using Latex

```sh
pdflatex -interaction=nonstopmode -halt-on-error nguyen_ethan_resume.tex
```
