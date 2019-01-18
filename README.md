## NOTE - Superceded by stuff on BitBucket (back when they had better "free group" policies) 

* see:  https://bitbucket.org/npdgroupc/ar_explorations_for_engager/src/master/
* also : https://npdgroupc.bitbucket.io/  (small tech demos for engager)

## (old, deprecated stuff) 

# AR_explorations_for_engager

## Test AR ideas for an engaging system that reduces waiting-stress

## Assumes : node,  unix (MacOs or Linux)

````
 # to create self-signed serts for https:
 openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
````


````
# to run local https server (assuming npm http-server) :
http-server -p  9999   -S .

# then open your browser to "https://localhost:9999/"
# note - you may have to use chrome's Advanced feature to access site
# from the chrome Advanced setting - use 'proceed to localhost (unsafe)

````

## TODO
* explore : https://letsencrypt.org/ rather than self-signed certs
* figure out why A-Frame seems to disregard some events
* minimal 'paint' of geometric figures
* combining figures
