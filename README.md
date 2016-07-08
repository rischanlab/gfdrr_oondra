# gfdrr_oondra

[![Join the chat at https://gitter.im/kartoza/gfdrr_oondra](https://badges.gitter.im/kartoza/gfdrr_oondra.svg)](https://gitter.im/kartoza/gfdrr_oondra?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
GFDRR Challenge Online Operational Natural Disaster Risk Assessment platform


## Steps to build and run geonode
* Clone this repository. 
* Enter to deployment directory. 
* Clone geonode repo, `git clone https://github.com/GeoNode/geonode.git`
* Rename geonode to `docker-geonode`.
* Copy Dockerfile , build.sh and 71-apt-cacher-ng file from the deployment directory into docker-geonode directory.
* Enter to docker-geonode directory.
* Run `build.sh`, it will build `kartoza/geonode` image
* Make sure that `kartoza/geonode` already there, by this command `docker images | grep geonode`
* Back to deployment directory.
* Run `make run` to start geonode container

