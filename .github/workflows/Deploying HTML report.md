# Deploying Archi HTML Reports on GitHub Pages

These actions leverage the code written by @WoozyMasta specifically for deploying Archi html reports with github pages.
The documentation of @WoozyMasta's code can be found [here](https://github.com/marketplace/actions/deploy-archi-report) and an example repository can be found [here](https://github.com/WoozyMasta/archimate-ci-image-example).
The rest of this markdown file describes how the automated deployment of the html report is set-up using the github actions provided by @WoozyMasta. 

## To set-up this workflow
1. Add a new branch to the repository named 'gh-pages'
2. Go to the settings of the repository:
  - Make sure the repository is 'public'
  - Go to Settings > Pages and choose 'Deploy from a branch', set the Branch to 'gh-pages', and press 'Save.
3. Add the worflow code to the repository by copying the files that are in the '.github/worflows' folder in this repository
4. Add the '.archi_report' to the .gitignore for the repository

## Running this worflow
This workflow will run whenever there is a push to main.
Go to the Actions tab of the worflow to watch the status of the workflows and examine any errors if they occur.

## Viewing the webpage
This workflow will deploy the html report on the webpage with the following url where <repository-name> is the name of the repo: "https://<repository-name>.github.io/<repository-name>".
e.g., https://lfenergyarchitecturemodel.github.io/lfenergyfunctionalarchitecturemodel/
