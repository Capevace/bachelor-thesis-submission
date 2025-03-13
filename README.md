# Bachelor Thesis – Lukas Mateffy

> Date of submission: 13.03.2025

## Abstract

In an era defined by extensive digitalization, the challenge of efficiently extracting structured infor-mation from unstructured digital documents remains a significant bottleneck for both people and organizations. Despite advancements in digital document formats, the embedded data often remains inaccessible to automated systems, necessitating time-consuming and error-prone manual data entry. This thesis introduces Data Wizard, a novel approach to address this challenge: a reusable and embeddable tool for structured data extraction leveraging the power of Large Language Models (LLMs). It aims to answer the question whether a solution can be built that is flexible enough to be useful in a variety of contexts while remaining simple and easy to work with. As such, Data Wizard is designed to be seamlessly integrated into existing software ecosystems, being adaptable to diverse document formats and extraction tasks. This work details the architecture, implementation, and evaluation of Data Wizard, showcasing its ability to create data extraction processes through configurable strategies, support for multiple LLM providers, and an intuitive user interface. The evaluation across various real-world scenarios demonstrates Data Wizard's effectiveness in extracting structured information with minimal configuration, highlighting its potential to provide access to LLM-powered data extraction and accelerate digital transformation initiatives across industries.

## Thesis

The thesis is available [here](./Thesis.pdf).

This repository contains the source code for the two resulting open-source projects in the state they were during submission.

Continously updated versions of the projects can be found in their respective repositories:

[Data Wizard](https://github.com/Capevace/data-wizard)
[LLM Magic](https://github.com/Capevace/llm-magic)

A prebuilt docker container can be found one the [Docker Hub (mateffy/data-wizard)](https://hub.docker.com/r/mateffy/data-wizard).
This container is continuously updated with the latest changes. The tag `mateffy/data-wizard:submission` contains the state of the project at the time of submission.
