# docker-quick-demo
Just a quick demo to show some basic functions of Docker


'''
docker images 
docker pull busybox
docker images 
'''

'''
docker run busybox
'''

'''
docker run -it busybox
'''

'''
uname -a
ls
pwd
date
ifconfig
netstat -rn
exit
'''

'''
docker container ps
docker container ps -a
'''

'''
docker rmi busybox
docker run busybox
docker container ps -a
'''

'''
docker container rm <name>
docker run -it --name box1 busybox 
'''

'''
docker container ps
docker container ps -a
'''

'''
docker start box1
docker container ps -a
'''

'''
docker start -i box1
ifconfig
'''

'''
docker start -i box2
ifconfig 
ping <box1>
'''

'''
docker container ps -a
docker container rm box1
docker container ps -a
docker rmi busybox
'''
