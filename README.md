<!--
SPDX-FileCopyrightText: 2017-2022 Contributors to the lfenergyarchitecturemodel project

SPDX-License-Identifier: CC-BY-4.0
-->

# LF Energy Functional Architecture Model

The repos in this github org contains Functional Architecture Model in Archimate language. 

# View 
The model can be viewed [here without the need to install Archi](https://lcrowleyepri.github.io/).


# Edit  
To contribute to the LF Energy Archimate models you need [Archi](https://www.archimatetool.com/). 

## Step-by-step guide for Archi
For Step-by-step guide to use the model see: https://github.com/lfenergyarchitecturemodel

## License
This project is licensed under the [Creative Commons Attribution 4.0 International License](https://github.com/lfenergyarchitecturemodel/.github/blob/main/LISENSE).

## Contributing
Please read [CONTRIBUTING.md](https://github.com/lfenergyarchitecturemodel/.github/blob/main/CONTRIBUTING.md) for details on the process for submitting pull requests to us.

## Modelling Guidelines
In order to maintain consitency in the model whilst facilitating collaboration and contributions from all parties, a set of modelling guidelines have been created.
### Contribute using a feature branch
If you wish to contribute to the model, (e.g., Create new diagrams or edits to existing diagrams) please create a new branch from the main model. When your draft is stable, create a pull request to merge your development branch into the master branch. The lfenergy functional architecture team will review the pull request and accept/edit the contribution from the development branch via github.

The lfenergy functional architecture team will review draft branches on a monthly basis and merge them into the master branch.

### Adding a new lfenergy project (X)
Please add a sub-folder for each lfenergy project in the 'Views' folder. (See OpenSTEF as an example)
In this sub-folder, create two diagrams:
- X Detailed. This diagram describes the behavior (functions and data flows) of each lfenergy project.
- X Realized. This diagram relates the lfenergy project to the generic reference archietcure by pointout out which generic functions are realized by the lfenergy project.

Any model object that is specific and exclusively used by a specific LFenergy project should be stored in the folder for that project. If such a folder does not already exist, please create it under the Applications folder (e.g., see the Open STEF folder as an example).

### (Re-) using model objects
When creating diagrams, re-use model objects wherevere possible, to avoid creating duplicate objects for the same concept. Existing  generic model objects are stored in the subfolders of the Application folder:
1 Generic Application Components
2 Generic Application Functions
3 Generic Application Service / Data Exchange Standard
4 Generic data objects

In #2 you will find the functions, and in #4 you will find the data objects that have been created for generic modelling. Please re-use these wherever possible, and only create a new object if the concept has not already been modelled. Every object must have a definition when it is created in order to help users to understand the meaning of a model object.


## Contact
Please read [SUPPORT.md](https://github.com/lfenergyarchitecturemodel/.github/blob/main/SUPPORT.md) for how to connect and get into contact with the lfenergyarchitecturemodel project.
