A single-page, one-column resume tailored for software developers, crafted by Cyprian Aarons. This resume leverages basic LaTeX templates and fonts to simplify updates and maintenance. It features well-documented sections and custom commands to ensure uniform formatting. The primary sections include education, experience, and projects.

### Motivation

This template was developed to address the complexities of managing a resume on platforms like Google Docs, where formatting changes can be cumbersome and repetitive.

The design avoids common pitfalls of other templates, such as multi-column or multi-page formats, which are less effective for career fairs and online submissions.

### Quick start

Begin swiftly with the [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Preview

![Resume Screenshot](/preview.png)

### License

Format is MIT but all the data is owned by Cyprian Aarons.
