In this directory a very simple python app flask) and Docker workflow.

Requirements.txt (in directory) build with latest version of pip3:
```
 pip3 install Flask
$ pip3 freeze > requirements.txt
```

# Build and Run with play with Docker
``` Goto https://labs.play-with-docker.com/ ```



# Build and Run with Docker Desktop

```
cd ShowcaseCD-Python
```
Build with:
```
cd simple-dockerflow
docker build -t sim007/pythondemo:1.0.0.0 .
```
Run with:
```
docker container run -p 5000:5000 sim007/pythondemo:1.0.0.0
```
Show in browser with:
```
localhost:5000
```
Application ok?
Share the container to Docker Hub
```
docker push sim007/pythondemo:1.0.0.0
```

Run the container in Play with Docker with:
```
docker container run -p 5000:5000 sim007/pythondemo:1.0.0.0
```

# Build and Run with GitHub actions


# Build and Run with docker 
