
# IoBroker  

Docker image for http://www.iobroker.net  

 iobroker.vis v1.1.4
 ioBroker.admin v3.4.6

Base on node:6-alpine,

Package compressed size 119MB

# Run IoBroker
```
$ docker run --name iobroker -d -p 8081:8081 -p 8082:8082 -p 1880:8083 -it salenss/iobroker
```

## Notes

## Update
* Update v1.3
* Update v1.2
* Update v1.1
* update v1.0.3
## Fix version v1.0.3
* Fix admin vis install.
## Fix version v1.0.2
* Fix Hostname.
## Fix version v1.0.1
* Fix error start IoBroker.
* Fix serialport.
## v1.0.0
