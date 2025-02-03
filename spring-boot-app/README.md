# Spring Boot based Java web application
 
This is a simple Spring Boot based Java application that can be built using Maven. Sprint Boot dependencies are handled using the pom.xml at the root directory of the repository.

This is a MVC architecture based application where controller returns a page with title and message attributes to the view.

## Execute the application locally and access it using your browser

Checkout the repo and move to the directory

```
git clone 
cd 
```

The above maven target stroes the artifacts to the `target` directory. You can either execute the artifact on your local machine
(or) run it as a Docker container.

** Note: To avoid issues with local setup, Java versions and other dependencies, I would recommend the docker way. **


### The Docker way

Build the Docker Image

```
docker build -t 
```

```
docker run -d -p 8010:8080 -t 
```

Hurray !! Access the application on `http://<ip-address>:8010`