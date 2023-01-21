# Docker

> **in website " docker with play " **

**docker version**

```
To know information about version docker
```
**docker info:**

```
T o know information about container :
containe:0 "number"
Running:0 "pause"
```

**docker container run -it alpine:latest sh**

```
To make container contain image linux with small size 9.9MB  "  alpine:latest  "

and " -it "  to allow me to make interact " i " with terminal " t " and i can see input and output
```

## Now, we are inside terimal of this container

> **hostname**
>
> ```
> To know name of container
> ```
>
> **cat/etc/*release***
>
> ```
> To know details of image "alpine"
> ```
>
> **ls**
>
> ```
> To know som info
> ```
>
> **echo "hello container"**
>
> ```
> To print "hello container" --> we make test for this container that is working or not
> ```
>
> **exit**
>
> ```
> To exit from this container
> ```
>
> 

**docker image ls**

```
To know information about all images that i have 
REPOSITORY,TAG, IMAGE ID, CREATED SIZE  
IMAGE -->"alpine"
 
```

$ docker container run -d -p 80:80 nginx:latest

```
we make container with image "nginx:latest" --> this is a web service
and " -d " this container will run in background and cannot see the terminal -->"-t "opposite "-p"
" -p 80:80 " we make mapping

```

## while this container is running

> **curl http://localhost:80**
>
> ```
> this give us "welcome to nginx " and some info and after exit from this container we cannot acess on this url again
> ```
>
> ***to exit from this container*** 
>
> **docker container stop "id of container"**
>
> ```
> to know id of container you can know it from " docker container ls -a "
> ```
>
> 

## Then , I can make more containers using the above
