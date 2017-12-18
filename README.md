Docker for Janus WebRTC Gateway
=

To start a container just execute
```
$ ./run.sh
```

Inside the container are running:
- Nginx (to serve examples)
- Janus server

To play with examples open `https://192.168.99.100:8443/demos.html` in your browser.  
Here `192.168.99.100` is your Docker Machine IP address.  
You can get it by running
```
$ docker-machine ip YOUR-MACHINE-NAME
```
