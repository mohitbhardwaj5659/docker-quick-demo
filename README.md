# docker-quick-demo
Just a quick demo to show some basic functions of Docker

Pull an image
```
docker images 
docker pull busybox
docker images 
```

Start a container with this image
```
docker run busybox
```

Run it in interactive mode
```
docker run -it busybox
```

```
uname -a
ls
pwd
date
ifconfig
netstat -rn
exit
```

```
docker ps
docker ps -a
docker network ls
```

```
docker rmi busybox
docker run busybox
docker ps
docker ps -a
```

```
docker container rm <name>
docker run -it --name box1 busybox 
```

```
docker ps
docker ps -a
```

```
docker start box1
docker container ps -a
```

```
docker start -i box1
ifconfig
```

```
docker start -i box2
ifconfig 
ping <box1>
```

```
docker container ps -a
docker container rm box1
docker container ps -a
docker rmi busybox
```
