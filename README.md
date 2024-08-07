# tensorflow-proj-template
* How to build
```
docker build -f docker/proj.dockerfile -t myproj .
```

* How to run
```
docker run -it --rm -p 8888:8888 -v $(pwd):/home/proj/ myproj

```

* Access to `http://127.0.0.1:8888`

# TODO
* access to data folder

