[![View article](https://img.shields.io/badge/CodeCut-View_article-blue)](https://codecut.ai/how-to-structure-a-data-science-project-for-readability-and-transparency-2/) [![View on YouTube](https://img.shields.io/badge/YouTube-Watch%20on%20Youtube-red?logo=youtube)](https://youtu.be/TzvcPi3nsdw) 

# Data Science Cookie Cutter

## Why?
It is important to structure your data science project based on a certain standard so that your teammates can easily maintain and modify your project.

This repository provides a template that incorporates best practices to create a maintainable and reproducible data science project.  

## Tools used in this project
* [hydra](https://hydra.cc/): Manage configuration files - [article](https://codecut.ai/stop-hard-coding-in-a-data-science-project-use-configuration-files-instead/)
* [pdoc](https://github.com/pdoc3/pdoc): Automatically create an API documentation for your project
* [pre-commit plugins](https://pre-commit.com/): Automate code reviewing formatting
* [Pixi](https://pixi.sh): Dependency management 
* [uv](https://github.com/astral-sh/uv): Ultra-fast Python package installer and resolver
* [pip](https://pip.pypa.io/): Traditional Python package installer

## How to use this project

Install Cookiecutter:
```bash
pip install cookiecutter
```

Create a project based on the template:
```bash
cookiecutter https://github.com/khuyentran1401/data-science-template
```

You will be prompted to choose your preferred dependency manager:
- `pixi`: Modern Python package and dependency manager
- `uv`: Ultra-fast Python package installer and resolver
- `pip`: Traditional Python package installer

## Book: Production-Ready Data Science

Want to learn more about building production-ready data science projects? Check out my upcoming book:

[Production Ready Data Science: From Prototyping to Production with Python](https://codecut.ai/production-ready-data/?utm_source=github&utm_medium=repository&utm_campaign=data_science_template)

The book will cover:

- Best practices for structuring data science projects
- Tools and techniques for reproducible research 
- Deploying and monitoring machine learning models
- And much more!

Sign up now to receive the first 3 chapters for free! You'll also be notified when the full book becomes available.

## Other Resources:
- [Article](https://codecut.ai/how-to-structure-a-data-science-project-for-readability-and-transparency-2/)
- [Video](https://youtu.be/TzvcPi3nsdw)

