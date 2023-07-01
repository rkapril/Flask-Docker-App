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

http://localhost:5000

Stop the container

```
docker stop 2ab1a76cb586
```

Remove the container

```
docker rm 2ab1a76cb586
```
