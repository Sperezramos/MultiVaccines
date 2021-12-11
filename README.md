# RstudioCloudPackageLoad
Rscript and package list to configure your rstudio.cloud base package library in your rstudio shared library
First do not create your base project from an existing git repo instead you must download it from github as a zip file to your computer.  Then unzip its contents into a folder on your computer called "packageLoad".
create a new project in your shared space named mypaks
now upload from packageload the file loadMypaks.R
then upload from packageload the file mypaks
source the loadMypaks.R file
When that job finishes delete the loadMypaks.R file and also delete the mypaks file - this results in a project with only the list of packages within it
Finally delete the paks.Rproj file and the README.md file so there are no residual files left in this folder
Last put this project under configure control by git -- go to Tools->Version Control->git
Finally return to your shared library on rstudio.cloud and make the project "visible to all"
Then set mypaks as your default working directory in your rstudio.cloud shared space
