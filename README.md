# Dockerized Baobab

Baobab running in a docker container with NoVNC to figure out what is taking up space on a headless server. 

## How to use
```
docker run -it -v /place/to/mount:/data -p 6080:6080 zerodivide1/docker-novnc
```
Then open a web browser and goto
http://<server-ip/dns>:6080 

## Credits

* [NoVNC](http://kanaka.github.io/noVNC/)
* [Original docker-novnc project](https://github.com/paimpozhil/docker-novnc)
