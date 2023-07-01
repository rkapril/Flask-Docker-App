## Command

Build Image

```
docker build -t "flask_docker" .
```

List Images

```
docker image ls
```

Run image as container

```
docker run -p 5000:5000 -d flask_docker
```
