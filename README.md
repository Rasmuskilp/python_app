#description of the cookbook:
## this cookbook contains the python app development environment
## the cookbook installs all the necessary software in order for the app to production
## the app is also used to create an AMI
## which is then used to start a service on AWS that is used as a slave node on jenkins
## you can test the cookbook by doing kitchen test



# python_app - miscellaneous instructions:
## In order to install packer
### Touch Berksfile
### berks install
#berks vendor
## CSV file path ~/Downloads/ItJobsWatchTop30.csv - this is for the app

## General project objectives:
## 1.Have a github repo for the app
## 2.Have a working app environment that installs and updates all the necessary plugins - use packer to create an - AMI
## 3. Have a cookbook for the reverse nginx proxy . - AMI
## 4. Create a Jenkins CI pipeline, that listens to the app - will do the environment and the pytests - if successful sends it forward.
## 5. If successful creates an production environment - AMI
## * for part 5 the task was to do it manually instead
