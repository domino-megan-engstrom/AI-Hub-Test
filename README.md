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

## Known issues
Document all the known issues with the repo in this section

## References
Any references you'd like to include go here.

## Best Practices

### Code
1. Use Case templates should ideally contain an end-to-end experience from development to productionization
2. README should include usage instructions
3. Any links in the README should use absolute URLs
4. If the repo contains a notebook, ensure that the notebook well documented

### Testing
1. List the Domino versions that the code in this repo has been validated against: 5.8
2. If an automated test is included in the repo, document how it should be run:

### Release process
1. Development may continue from a main/active branch
2. Maintain a CHANGELOG for the repo, that documents major changes in the repo
3. Whenever the template code is ready to be released (prerogative of template creator, who will sign off on the release based on automated + manual testing), create a release branch
4. Follow semantic versioning for releases. Release branches should be created with a prefix ``release-X.Y.Z`` for every release.
5. Ensure that the release branch is protected.
6. Always make the latest release the default branch for the repo.
7. Once a new version is ready to be released, reach out to Domino by submitting the [intake form](https://docs.google.com/forms/d/e/1FAIpQLSe9OgI8eCzsu4WCyfG1xPV8C-xR9Wg--mo7Uq4UX1QBCEqyFw/viewform?usp=sf_link)
8. After submitting the form: Domino will reach out to start the process of including the new version in the Hub. At this point, the release branch should be provided git reference in the commit. The Domino team will ensure that the release branch name is mapped to the hub revision, and perform other checks as part of the review process.
