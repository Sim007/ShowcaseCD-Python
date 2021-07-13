In this directory a very simple python app flask) and Docker workflow.

Requirements.txt (in directory) build with latest version of pip3:
```
 pip3 install Flask
$ pip3 freeze > requirements.txt
```

# Build and Run with play with Docker
``` Goto https://labs.play-with-docker.com/ ```
Not working anymore?

# Build and Run with GitHub actions

# Build and Run with Docker Desktop

```
cd ShowcaseCD-Python
```
Build with:
```
cd simple-dockerflow
docker build -t pythondemo .
```
Run with:
```
docker container run -p 5000:5000 pythondemo
```
Show in browser with:
```
localhost:5000
```

# Build and Run with docker 
