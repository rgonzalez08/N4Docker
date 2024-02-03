

Welcome to the N4 Docker test repo.  This repository contains a `docker-compose`

Installation Instructions: Ubuntu
-------------------------

First, install Docker
log into the docker hub 

```
$ sudo apt-get install docker docker-compose git
$ sudo docker login -u <username> -p <key>
```

After that, clone this repository:

```
$ git clone https://github.com/rgonzalez08/N4Docker.git
$ cd N4Docker
```

Finally, pull the containers and start Niagara:
```
$ sudo docker login -u <username> -p <key>
$ sudo docker-compose pull
$ sudo docker-compose up -d
```

After this step is finished, you should be able to access the Niagara Platform on 5011
