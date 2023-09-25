# AI Hub Template

Use this repo as a GitHub template repository for creating new templates.

## About this template
A short description of the template goes here. Ideally, describe the use case, the machine learning task it uses, what kind of data is required, details about obtaining the data and any other information that will be useful to a data science practitioner using this template.

## Prerequisities

### Environment
Does this template work with a standard environment? If so, mention which environment is required. If not, please fill the sections below to indicate how a custom environment should be set up to use this template:

#### Base Image
Specify the base image for the custom environment. The base image should be publicly accessible. Domino should be able to download it without requiring credentials.

#### Dockerfile Instructions
Add Dockerfile instructions that a user will copy into the Dockerfile for their custom environment.

#### Workspace Tools
Specify which workspace IDEs are required for your project:
Jupyter
JupyterLab
VSCode
RStudio

### Hardware Requirements
Does this template require any specific hardware, such as GPUs? If so, mention the requirements in detail.

### Other prerequisities
Do any scripts need to be run after the project is created from the template? What are these scripts used for? Specify what each script does, and instructions for running it.
Please make sure that the scripts are all included in the source code of the project (the repo you are creating using this template).

## Usage Instructions
List step-by-step instructions for how to use a project created from this template

1. Run Notebook X.ipynb
2. Run Notebook Y.ipynb
3. Run script model.py
4. ...
5. ...

## Release process
Follow the best practices below for releasing templates from this repo:

1. Always release a template from a protected release branch.
2. Follow semantic versioning for releases. Create a protected branch with a prefix ``release-X.Y.Z`` for every release.
3. Always make the latest release the default branch for the repo.
4. <placeholder for jira>
