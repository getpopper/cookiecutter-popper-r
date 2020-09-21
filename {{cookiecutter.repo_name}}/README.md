# {{ cookiecutter['project name'] }}

{{ cookiecutter['author(s)'] }}, {% now 'local', '%d/%m/%Y' %}

{{ cookiecutter['description']}}

## Requirements

- [Popper](https://getpopper.io/)
- Docker

## Reproducing the results

```
popper run -f wf.yml
```

## Project structure
```
├── LICENSE
├── README.md                       <- The top-level README.
├── data                            <- Data used in workflow.
├── paper                           <- Generated paper as PDF, LaTeX.
├── output
|   ├── models                      <- Model predictions, serialized models, etc.        
|   └── figures                     <- Graphics created during workflow.
└── R                               <- R source code for this project.
    ├── notebooks                   <- R Markdown notebooks.
    ├── data                        <- Scripts to download or generate data.
    ├── models                      <- Scripts to fit models.
    └── figures                     <- Scripts to generate graphics.

```
## License

This project is distributed under the  BSD-3 license.
