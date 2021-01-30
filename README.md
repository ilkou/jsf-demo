# JSF-DEMO

## Build the project

`
mvn package
`

After executing above command "jsf-demo.war" file will generate in target folder of the project.

## Run it

### Method 1

Copy the generated "jsf-demo.war" file from target folder to your tomcat webapp folder and start the server.

After successful start of server open web browser and enter http://localhost:8080/jsf-demo/ in URL bar.

### Method 2 (Docker)

#### Build image

`
docker build -t jsf-demo .
`

#### Run container

`
docker run --rm --name jsf-demo -p 8080:8080 jsf-demo
`

:)
