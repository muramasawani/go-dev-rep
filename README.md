# introduction
This repository is meant to try in the docker [official practice go](https://golang.org/doc/code.html)

# use
add directry
```
cd go/app
mkdir bin pkg src
```

create image 
```
docker build -t golang:latest . -f go/Dockerfile
```

container up(background)
```
docker-compose up -d
```

entering the container
```
docker exec -it <container-name> sh
```

container down
```
docker-compose down
```


