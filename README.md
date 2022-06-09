# Sustainable (Small) Data Science

Exploring practices for sustainable (small) data science.

This document was developed as part of an IT Workshop for the Stanford Graduate School of Education.

## Useful tips, tools, and processes

The following list provides an opiniated overview of useful tools and processes that can help to setup a sustainable small data science project. The assumptions are that individual researchers or small teams will be responisble for the various kinds of tasks that are involved in these kinds of undertakings.

These tasks are categorized by three distinct project phases which usually involve different types of considerations and engagements with collaborators, readers, and users. 

1. Initiation phase: Setting up project/data structures
2. Ongoing phase: Development and analysis
3. Completion phase: Publishing and dissemination

### Initiation phase

#### Project structure

1. [Cookiecutter template](https://drivendata.github.io/cookiecutter-data-science/)
2. My own project structure (provide examples)
    1. Data, notebooks, scripts, outputs
3. Separate data work from scholarly articles
    1. Usual published project structure:
        1. Versioned code repository with DOI (Github + Zenodo)
        1. Versioned data repository with DOI (Dataverse)
        1. Versioned repository with code/data to reproduce article (Github + Zenodo)

### Ongoing phase

#### Utility

9. Progress bars: [tqdm](https://tqdm.github.io/)
10. APIs: [Postman](https://www.postman.com/)

#### Development

3. Dependency management: [Poetry](https://python-poetry.org/), [pyenv](https://github.com/pyenv/pyenv), [pipx](https://github.com/pypa/pipx)
6. Leverage notebooks and interactive development environments
    5. I can provide a deep dive into my local dev setup. But maybe not relevant for non-pythonistas
7. Serious development in notebooks: [nbdev](https://nbdev.fast.ai/)

#### Research process

8. Github Wiki as a research log

### Completion phase

#### Collaboration

11. Turn notebooks into slides: [RISE](https://rise.readthedocs.io/en/stable/)
12. [Github Pages](https://pages.github.com/)