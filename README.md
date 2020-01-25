# RstudioCloudPackageLoad
Rscript and package list to configure your rstudio.cloud base package library in your rstudio shared library
Go to your rstudio.cloud shared space then
1. create a new project in your shared space named mypaks, and have it created using this github repository as its basis
2. source the loadMypaks.R file
3. delete the loadMypaks.R file and also delete the mypaks file - this results in a project with only the list of packages within it
4. Finally delete the rproj file so there are no residual files left in this folder
5. exit your mypaks project and then set mypaks as your default working directory in your rstudio.cloud shared space
