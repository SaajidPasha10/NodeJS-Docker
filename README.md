## INSTALL THE DOCKER FROM THE OFFICIAL WEBSITE

## Create a nodejs project `npx express-generator node-docker-demo`
## Install dependencies `npm install`

## CREATE A DOCKER FILE

## AFTER CREATING DOCKER FILE IN TERMINAL `docker build . -t app`
## THIS BUILDS THE DOCKER IMAGE FROM THE DOCKER FILE `.` MEANS THE CURRENT DIRECTORY WHICH WILL BE USED TO CREATE IMAGES FROM
## -t will assign a name tag to the image

## CHECK FOR THE IMAGES - `docker images`
## RUN THE CONTAINER COMMAND TO BUILD A CONTAINER - `docker run -d --name node-demo-container -p 5000:5000 app:latest`