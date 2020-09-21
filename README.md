# cookiecutter-popper-r

Cookiecutter template for research projects in R on the 
[Popper](https://github.com/getpopper/popper) workflow execution engine. 

The goal is to provide a  structure for developing 
reproducible projects in computational research (machine learning, statistics, bioinformatics, ...)
following best practices in a container-native environment.

Resource:
- A guide for developing R workflows for computational research with Popper is available in the
 [Popper documentation](https://popper.readthedocs.io/en/latest/sections/guides.html).
- An example project following this structure is available at [popper-examples](https://github.com/getpopper/popper-examples/tree/master/workflows/comp-research/rstudio).

## Requirements

- Python >= 3.5
- [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/advanced/directories.html) >= 1.1

Additionally, to run the generated project:

- Popper
- Docker

## Generating a project template

Run
```sh
cookiecutter gh:getpopper/cookiecutter-popper-r
```
