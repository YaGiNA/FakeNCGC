# NCGC
News Classifier by Generated Comments

# How to use it in Docker
```
$ docker build -t fake_ncgc ./
$ docker run --runtime=nvidia -it -v ${PWD}/:/tf/fake_ncgc -p 8080:8080 -p 6006:6006 fake_ncgc /bin/bash
```