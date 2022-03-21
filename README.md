# Modularized_App_Development

This repository has been designed to maintain the large scale App development in modularize enviroment where multiple teams are working on different modules of an application. Instead, team mates develop within the same project, using this architectur3/development cycle they develop in different modules. Once a module has been developed, it will be used using below explained sturture.

### Project Structure on Git
The structure of the Modularized App Development evolves around the repositorie's branhes and the below structure can be scaled upto desired limits.

**Master Branch** -> Merged/Final prject for release 

**Feature Development Branch** -> Develop a Feature/Module in this branch, this branch also include the module along the project.

**Feature Branch** -> Holds the Feature/Module in Feature Development Branch, this branch will only have the module.


### Project Structure on your local machine
In your local mechine the structure will look like below

    - Root Folder
      - Master Project
        - Module 
      - Module Project
        - Module

### Development Procedure
Create a new project and generate a new module in it. Push the poject into Feacture_Development_Branch (of your name choice). A .git file will be generated with the head at Feacture_Development_Branch. At this point the local sturcture should look like
      
      - Root Folder
        - Master Project
        - Module Project
          - Module

there is no module in master project because it has not been imported into Master project
