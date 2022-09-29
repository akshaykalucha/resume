A resume of type "single page, one column". Uses latex font and templates to easily manage and install resume. Different sections of resume are clearly documented for ease of understanding and quick setup. The main sections consist of Education, Work Experience, Projects and Programming Skills.

### Motivation

I made this template because it was tough to manage a resume in Google Docs and it was too difficult to change any formatting because it had to be applied many times.

For employment fairs or online applications, the majority of the currently accessible templates either concentrate on two columns or are lengthy (several pages).



### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex AkshayKaluchaResume.tex

```

### License

Format is MIT but all the data is owned by Akshay Kalucha.
