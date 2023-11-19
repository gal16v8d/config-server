# Getting Started

### Guides
The following guides illustrate how to use some features concretely:

* [Centralized Configuration](https://spring.io/guides/gs/centralized-configuration/)

### Pre-requisites

* Maven 3
* Java 21

### Docker Image

- In the project dir, build using the command:

```bash
docker build -t gsdd-config-server .
```

- Run the docker image as:

```bash
docker run -d -p 8888:8888 gsdd-config-server

### Running

1. Run [eureka-server](https://github.com/gal16v8d/eureka-server) project
2. Run this project
3. Finally you can check it is working by check any url like:

http://localhost:8888/dw2-svc/default

http://localhost:8888/fx-course-app/default
